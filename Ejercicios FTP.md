# Ejercicios de Configuración y Administración de un Servidor FTP en Linux

## Ejercicios Básicos

**1. Instalación de vsftpd**
   - Instala el servidor FTP vsftpd en una máquina Linux.
   - Verifica que el servicio está corriendo utilizando el siguiente comando:
    ```bash
    sudo systemctl status vsftpd
    ```

**2. Configuración Básica**
   - Modifica el archivo /etc/vsftpd.conf para permitir que los usuarios locales puedan subir y descargar archivos.
   - Reinicia el servicio y verifica que los cambios se aplican:
    ```bash
    sudo systemctl restart vsftpd
    ```

**3. Creación de Usuarios**
   - Crea un nuevo usuario llamado ftpuser y establece una contraseña.
   - Accede al servidor FTP con este usuario utilizando un cliente FTP como ftp o FileZilla.

**4. Probar Conexión FTP**
   - Conéctate al servidor FTP desde otra máquina en la misma red utilizando un cliente FTP.
   - Sube y descarga un archivo de prueba.

## Ejercicios Intermedios

**5. Habilitar Conexiones Pasivas**
   - Configura el servidor FTP para permitir conexiones pasivas.
   - Asegúrate de abrir los puertos necesarios (10000-10100) en el firewall.

**6. Restringir Usuarios a Su Directorio Home**
   - Configura el archivo `/etc/vsftpd.conf` para que los usuarios no puedan acceder fuera de sus directorios home.
   - Prueba que la restricción funciona.

**7. Configurar FTPS**
 - Genera un certificado SSL/TLS autofirmado.
 - Configura vsftpd para usar este certificado y permitir conexiones FTPS.
 - Conéctate al servidor usando un cliente que soporte FTPS y verifica la conexión segura.

**8. Configurar Permisos de Archivos**
 - Crea un directorio compartido para todos los usuarios.
 - Configura permisos para que los usuarios puedan leer y escribir archivos en este directorio, pero no puedan borrar los archivos de otros.

## Ejercicios Avanzados

**9. Control de Acceso por IP**
 - Configura vsftpd para permitir conexiones solo desde ciertas direcciones IP.
 - Prueba conectarte desde una IP no autorizada y verifica que el acceso es denegado.

**10. Monitoreo de Actividad**
 - Usa el archivo de logs de vsftpd para analizar las actividades del servidor.
 - Encuentra información sobre quién se conectó, qué archivos se descargaron y cuándo.

**11. Automatización con Scripts**
 - Crea un script Bash que realice lo siguiente:
 - Cree un nuevo usuario FTP.
 - Configure su directorio home con permisos específicos.
 - Agregue la información del usuario a un archivo de texto.

**12. Integración con Docker**
 - Crea un contenedor Docker que ejecute un servidor FTP basado en vsftpd.
 - Monta un volumen local para que los datos del servidor FTP persistan incluso después de detener el contenedor.
