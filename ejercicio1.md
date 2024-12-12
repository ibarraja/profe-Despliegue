# Ejercicio 1: Instalación y configuración inicial de Apache
## Explicación:
Apache es un servidor web que permite servir contenido a través de HTTP. En este ejercicio, aprenderás a instalarlo, verificar su estado y personalizar su configuración básica.

## Enunciado:
- Instala Apache en tu sistema operativo.
- Verifica que el servicio Apache está activo y en funcionamiento.
- Accede a la página predeterminada de Apache en tu navegador (http://localhost).
- Modifica el archivo de configuración principal (/etc/apache2/apache2.conf) para que Apache escuche en el puerto 8080.

## Solución:
**1. Instalo Apache:**
```bash
  # Primero actualizo el SO
  sudo apt update
  sudo apt upgrade -y

  # Segundo instalo Apache
  sudo apt install apache2
```

**2. Verifico que Apache esta funcionando:**
```bash
  sudo systemctl status apache2
```

**3. Accedo a la página predeterminada de Apache:**
Uso el navegador y accedo a `http:\\localhost`:

<p align="center">
<img src="/assets/browser.png">
</p>


**4. Modificar el archivo para que escuche en el puerto 8080:**
Accedo con la terminal al archivo de configuración de los puertos de Apache:
```bash
  sudo nano /etc/apache2/ports.conf
  
  #Cambio:
  Listen 80
  # Por:
  Listen 8080
```
Reinicio Apache:
```bash  
  sudo systemctl restart apache2
```

Uso el navegador y accedo a `http:\\locahost:8080`:

<p align="center">
<img src="/assets/browser8080.png">
</p>
