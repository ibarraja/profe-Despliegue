# **Tema - Módulo 2: Docker y Apache**

## **Ejercicio 1: Instalación de Docker en Kubuntu**
### 1. Explica brevemente qué es Docker y cuál es su utilidad en el despliegue de aplicaciones web.
*Respuesta*:
   ```txt
   
   ```
### 2.  Realiza la instalación de Docker en Kubuntu siguiendo los pasos adecuados.
*Respuesta*:
   ```txt
   
   ```
### 3.  Comprueba que la instalación ha sido exitosa ejecutando el comando adecuado y captura la salida.
*Respuesta*:
   ```txt
   
   ```
### 4.  Explica la diferencia entre una imagen y un contenedor en Docker.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 2: Configuración y despliegue de Apache en Docker**
### 1. Busca una imagen de Apache en **Docker Hub** y descárgala en tu sistema.
*Respuesta*:
   ```txt
   
   ```
### 2.  Crea y ejecuta un contenedor basado en la imagen de Apache, asegurando que el servicio sea accesible desde el navegador.
*Respuesta*:
   ```txt
   
   ```
### 3.  Detén y elimina el contenedor de Apache.
*Respuesta*:
   ```txt
   
   ```
### 4.  Explica la diferencia entre exponer puertos con `-p` y definir volúmenes con `-v` en Docker.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 3: Docker Compose - Automatización del despliegue**
### 1. Explica qué es **Docker Compose** y para qué se utiliza.
*Respuesta*:
   ```txt
   
   ```
### 2.  Crea un archivo `docker-compose.yml` para levantar un servicio Apache con un volumen persistente para los archivos del servidor.
*Respuesta*:
   ```txt
   
   ```
### 3.  Ejecuta el archivo `docker-compose.yml` y verifica que el contenedor se haya iniciado correctamente.
*Respuesta*:
   ```txt
   
   ```
### 4.  Detén el servicio usando Docker Compose y comprueba que los archivos del volumen no se pierden tras reiniciar el contenedor.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 4: Verdadero o Falso**
Determina si las siguientes afirmaciones son verdaderas o falsas, justificando tu respuesta en caso de ser falsa:
### 1. Docker Compose permite gestionar múltiples contenedores como una sola unidad.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 2.  Un contenedor Docker puede ejecutarse sin necesidad de una imagen previa.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 3.  Los volúmenes en Docker permiten almacenar datos de manera persistente.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 4.  `docker stop` y `docker kill` realizan exactamente la misma acción.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 5.  Docker permite ejecutar aplicaciones en cualquier sistema operativo sin necesidad de adaptaciones.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```

### **Entrega:**
- Un documento en formato PDF con capturas de pantalla y explicaciones de cada paso realizado.
- Código y configuraciones relevantes utilizadas en los ejercicios.
---



# **Tema - Configuración de un Servidor Apache**

## **Ejercicio 1: Instalación de Apache en Kubuntu**
### 1. Explica qué es Apache y cuál es su función principal en un servidor web.
   *Respuesta*:
   ```txt
   
   ```

### 2.  Instala Apache en Kubuntu utilizando los comandos adecuados.
*Respuesta*:
   ```txt
   
   ```

### 3.  Verifica que Apache se ha instalado correctamente y está en ejecución.
*Respuesta*:
   ```txt
   
   ```

### 4.  Accede a la página de prueba de Apache desde un navegador.
*Respuesta*:
   ```txt
   
   ```

### 5.  Explica cómo se gestionan los servicios en Linux y cómo iniciar, detener y reiniciar Apache.
*Respuesta*:
   ```txt
   
   ```


## **Ejercicio 2: Configuración Básica de Apache**
### 1. Explica qué es un archivo de configuración en Apache y dónde se encuentran ubicados.
*Respuesta*:
   ```txt
   
   ```

### 2.  Edita el archivo de configuración principal para cambiar la página de inicio predeterminada.
*Respuesta*:
   ```txt
   
   ```
### 3.  Cambia el puerto en el que escucha Apache y comprueba que el servicio sigue funcionando correctamente.
*Respuesta*:
   ```txt
   
   ```
### 4.  Configura Apache para que su directorio raíz sea una carpeta personalizada en lugar de la predeterminada
*Respuesta*:
   ```txt
   
   ```

### 5.  Configura Apache para que su directorio raíz sea una carpeta personalizada en lugar de la predeterminada.
*Respuesta*:
   ```txt
   
   ```
6. Modifica el mensaje de error 404 de Apache para mostrar una página personalizada.
*Respuesta*:
   ```txt
   
   ```
7. Activa y desactiva el módulo mod_rewrite, luego configura una regla básica en .htaccess para redirigir una URL a otra.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 3: Seguridad y Optimización en Apache**
### 1. Explica con tus palabras la importancia de asegurar un servidor Apache.
*Respuesta*:
   ```txt
   
   ```

### 2.  Deshabilita la lista de directorios para evitar que se muestren archivos de manera no intencionada.
*Respuesta*:
   ```txt
   
   ```

### 3.  Habilita y configura HTTPS en Apache utilizando un certificado SSL auto-firmado.
*Respuesta*:
   ```txt
   
   ```

### 4.  Optimiza la configuración de Apache para mejorar el rendimiento del servidor.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 4: Verdadero o Falso - Apache**
Determina si las siguientes afirmaciones son verdaderas o falsas, justificando tu respuesta en caso de ser falsa:

### 1. Los archivos de configuración de Apache suelen encontrarse en `/etc/apache2/` en distribuciones basadas en Debian.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 2.  Apache solo puede escuchar en el puerto 80 y no se puede cambiar a otro puerto.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 3.  El archivo `.htaccess` permite realizar configuraciones específicas sin modificar los archivos de configuración global de Apache.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 4.  Un servidor Apache sin HTTPS es completamente seguro si está configurado correctamente.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 5.  Los módulos de Apache pueden activarse y desactivarse sin necesidad de reiniciar el servicio.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```


# **Tema - Configuración de un Servidor FTP**

## **Ejercicio 1: Instalación de un Servidor FTP en Kubuntu**
### 1. Explica con tus palabras qué es un servidor FTP y para qué se utiliza.
*Respuesta*:
   ```txt
   
   ```

### 2.  Instala un servidor FTP en Kubuntu utilizando `vsftpd`. Verifica que el servicio está en ejecución y configurado correctamente.
*Respuesta*:
   ```txt
   
   ```

### 3.  Configura el acceso anónimo y explica sus implicaciones de seguridad.
*Respuesta*:
   ```txt
   
   ```

### 4.  Explica cómo detener, iniciar y reiniciar el servicio FTP en Linux.
*Respuesta*:
   ```txt
   
   ```


## **Ejercicio 2: Configuración de Usuarios y Permisos**
### 1. Crea un usuario específico para la conexión FTP.
*Respuesta*:
   ```txt
   
   ```

### 2.  Configura permisos adecuados para restringir el acceso a determinadas carpetas.
*Respuesta*:
   ```txt
   
   ```

### 3.  Habilita el acceso solo para usuarios locales y deshabilita el acceso anónimo.
*Respuesta*:
   ```txt
   
   ```

### 4.  Prueba la conexión al servidor FTP desde otro equipo o mediante un cliente FTP.
*Respuesta*:
   ```txt
   
   ```

### 5.  Explica con tus palabras la diferencia entre los modos de transferencia **activo** y **pasivo** en FTP.
*Respuesta*:
   ```txt
   
   ```


## **Ejercicio 3: Seguridad y Encriptación en FTP**
### 1. Explica los riesgos de seguridad de usar FTP sin cifrado.
*Respuesta*:
   ```txt
   
   ```

### 2.  Configura el servidor para usar **SFTP** o **FTPS**.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 3: Verdadero o Falso - FTP**
Determina si las siguientes afirmaciones son verdaderas o falsas, justificando tu respuesta en caso de ser falsa:

### 1. FTP es un protocolo que permite la transferencia de archivos entre un cliente y un servidor.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 2.  `vsftpd` es un servidor FTP disponible en sistemas Linux y es conocido por su seguridad y eficiencia.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 3.  En modo activo, el servidor FTP inicia la conexión con el cliente.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 4.  FTPS y SFTP son exactamente lo mismo y funcionan de la misma manera.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 5.  Un usuario FTP puede ser restringido para que solo acceda a su propio directorio sin ver archivos de otros usuarios.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```

# **Tema - Configuración de un Servidor Tomcat**

## **Ejercicio 1: Instalación de Tomcat en Kubuntu**
### 1. Explica con tus palabras qué es Apache Tomcat y para qué se utiliza.
*Respuesta*:
   ```txt
   
   ```

### 2.  Instala Tomcat en Kubuntu utilizando los paquetes adecuados o descargándolo manualmente desde la web oficial.
*Respuesta*:
   ```txt
   
   ```

### ### 3.   Verifica que Tomcat está en ejecución y accede a la página de administración.
*Respuesta*:
   ```txt
   
   ```
### 4.  Explica la estructura de directorios de Tomcat y su propósito.
*Respuesta*:
   ```txt
   
   ```
### 5.  Configura Tomcat para que se inicie automáticamente con el sistema.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 2: Despliegue de Aplicaciones en Tomcat**
### 1. Descarga y despliega una aplicación de ejemplo en Tomcat en formato `.war`.
*Respuesta*:
   ```txt
   
   ```

### 2.  Accede a la aplicación desde el navegador y verifica su correcto funcionamiento.
*Respuesta*:
   ```txt
   
   ```
### 3.  Explica cómo gestionar aplicaciones desde el **Tomcat Manager**.
*Pista:*
Tomcat Manager esta disponible en:
   ```bash
   http://localhost:8080/manager/html
   ```

*Respuesta*:
   ```txt
   
   ```


### 4.  Modifica la configuración del puerto de Tomcat y verifica que los cambios se aplican correctamente.
*Respuesta*:
   ```txt
   
   ```
### 5.  Explica la diferencia entre un despliegue manual y un despliegue automático en Tomcat.
*Respuesta*:
   ```txt
   
   ```

## **Ejercicio 3: Determina si las siguientes afirmaciones son verdaderas o falsas, justificando tu respuesta en caso de ser falsa:**
### 1. Tomcat es un servidor web especializado en la ejecución de aplicaciones Java.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 2.  Los archivos `.war` deben ubicarse en la carpeta `webapps` para ser desplegados en Tomcat.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 3.  Tomcat incluye una herramienta para gestionar aplicaciones de forma gráfica.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 4.  La configuración de Tomcat no permite ajustes de seguridad.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```
### 5.  HTTPS puede configurarse en Tomcat mediante certificados SSL.
   *Respuesta*: 
   ```py
   True
   False # Justificación
   ```

### **Entrega:**
- Un documento en formato PDF con capturas de pantalla y explicaciones de cada paso realizado.
- Configuraciones y comandos utilizados en cada ejercicio.

Puedes cambiar el ejercicio 3 de cada Ficha por un ejercicio de verdadero-falso?
