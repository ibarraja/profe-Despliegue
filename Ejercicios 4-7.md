# Ejercicio 4: Configuración de Virtual Hosts
## **Explicación**
Los Virtual Hosts permiten a Apache alojar múltiples sitios web en un solo servidor. En este ejercicio, configurarás dos sitios virtuales diferentes.

## **Enunciado**
1. Configura dos Virtual Hosts en Apache:
   - `sitio1.local` con la carpeta raíz `/var/www/sitio1`.
   - `sitio2.local` con la carpeta raíz `/var/www/sitio2`.
2. Crea un archivo `index.html` distinto en cada carpeta.
3. Configura el archivo `hosts` para que los nombres `sitio1.local` y `sitio2.local` apunten a `127.0.0.1`.
4. Reinicia Apache y verifica que puedes acceder a los dos sitios desde el navegador.

## **Pistas**
- Usa los archivos de configuración en `/etc/apache2/sites-available/`.
- Habilita los sitios con `a2ensite`.

# Ejercicio 5: Configuración SSL con HTTPS
## **Explicación**
La configuración de SSL permite servir contenido seguro mediante el protocolo HTTPS. Utilizarás un certificado autofirmado para la práctica.

## **Enunciado**
1. Habilita el módulo SSL en Apache.
2. Genera un certificado autofirmado usando `openssl`.
3. Configura un Virtual Host en Apache que sirva contenido seguro desde `/var/www/sslsite` en el puerto `443`.
4. Verifica el acceso al sitio a través de `https://localhost` y comprueba que el certificado está activo.

## **Pistas**
- Usa los comandos `a2enmod ssl` y `openssl req`.
- Configura el archivo `/etc/apache2/sites-available/default-ssl.conf`.

# Ejercicio 6: Redirección y Reescritura con mod_rewrite
## **Explicación**
El módulo `mod_rewrite` permite realizar redirecciones avanzadas. En este ejercicio, crearás reglas para redirigir tráfico según condiciones.

## **Enunciado**
1. Habilita el módulo `rewrite` si aún no lo has hecho.
2. Configura las siguientes reglas de redirección en el Virtual Host principal:
   - Redirigir todo el tráfico HTTP a HTTPS.
   - Redirigir la ruta `/antigua` a `/nueva`.
   - Redirigir todo tráfico a `/index.html` si la página solicitada no existe.
3. Prueba cada regla accediendo a las URL correspondientes desde el navegador.

## **Pistas**
- Modifica el archivo `.htaccess` o directamente el Virtual Host.
- Usa directivas como `RewriteEngine`, `RewriteCond` y `RewriteRule`.

# Ejercicio 7: Control de Acceso con .htaccess
## **Explicación**
El archivo `.htaccess` permite aplicar configuraciones específicas de Apache a directorios individuales, como restringir el acceso por IP o proteger directorios con contraseñas.

## **Enunciado**
1. Crea un directorio protegido en `/var/www/protegido`.
2. Configura el archivo `.htaccess` para:
   - Restringir el acceso únicamente a la dirección IP `127.0.0.1`.
   - Proteger el acceso con usuario y contraseña.
3. Crea un usuario con contraseña usando `htpasswd` y verifica que la autenticación funciona.

## **Pistas**
- Habilita el módulo `mod_auth_basic` si no está habilitado.
- Usa la directiva `AllowOverride All` en la configuración del Virtual Host.
