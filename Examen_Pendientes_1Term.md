# **Tema - Configuración de un Servidor DNS con BIND en Kubuntu**

## **Ejercicio 1: Instalación y Configuración Básica de BIND**
### 1. Explica con tus palabras qué es un servidor DNS y cuál es su función en Internet.
   *Respuesta*:
   ```txt
   
   ```
### 2.  Instala BIND en Kubuntu utilizando los paquetes adecuados.
   *Respuesta*:
   ```txt
   
   ```
### 3.  Verifica que el servicio BIND se ha instalado correctamente y está en ejecución.
   *Respuesta*:
   ```txt
   
   ```
### 4.  Configura un **servidor DNS local** que resuelva nombres de dominio internos.
   *Respuesta*:
   ```txt
   
   ```
### 5.  Comprueba que la resolución de nombres funciona correctamente con el comando adecuado.
   *Respuesta*:
   ```txt
   
   ```

---

## **Ejercicio 2: Configuración de Zonas DNS**
### 1. Explica qué es un archivo de zona en DNS y cuál es su propósito.
   *Respuesta*:
   ```txt
   
   ```
### 2.  Configura una zona directa con un dominio personalizado (ejemplo: `midominio.local`).
   *Respuesta*:
   ```txt
   
   ```
### 3.  Configura una zona inversa para resolver direcciones IP a nombres de dominio.
   *Respuesta*:
   ```txt
   
   ```
### 4.  Reinicia BIND y verifica que los archivos de zona están correctamente configurados.
   *Respuesta*:
   ```txt
   
   ```
### 5.  Explica la diferencia entre un **servidor autoritativo** y un **servidor recursivo** en DNS.
   *Respuesta*:
   ```txt
   
   ```

---

## **Ejercicio 3: Configuración Avanzada y Seguridad**
### 1. Explica qué es un **servidor DNS caché** y cuál es su utilidad.
   *Respuesta*:
   ```txt
   
   ```
### 2.  Configura BIND como servidor caché y verifica su funcionamiento.
   *Respuesta*:
   ```txt
   
   ```
### 3.  Habilita la seguridad en BIND restringiendo las consultas a IPs específicas.
   *Respuesta*:
   ```txt
   
   ```
### 4.  Configura registros **A, CNAME, MX y TXT** en la zona de tu dominio y explica su función.
   *Respuesta*:
   ```txt
   
   ```

---

## **Ejercicio 4: Verdadero o Falso**
Determina si las siguientes afirmaciones son verdaderas o falsas, justificando tu respuesta en caso de ser falsa:

### 1. Un servidor DNS autoritativo responde consultas sobre dominios específicos para los que tiene configuradas zonas.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 2.  La zona inversa permite resolver nombres de dominio a direcciones IP.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 3.  BIND permite configurar servidores DNS recursivos y autoritativos al mismo tiempo.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 4.  Un servidor DNS puede funcionar sin conexión a Internet si solo resuelve nombres locales.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 5.  `dig` y `nslookup` son comandos utilizados para diagnosticar problemas en servidores DNS.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```


