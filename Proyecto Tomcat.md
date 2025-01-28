# **Proyecto: Instalación y Configuración de Apache Tomcat en Kubuntu**

## **Objetivo**
El objetivo de este proyecto es instalar, configurar y documentar un servidor de aplicaciones Apache Tomcat en un entorno Kubuntu. Los alumnos deberán crear un manual técnico que detalle cada paso realizado, complementado con capturas de pantalla y explicaciones claras. Además, deberán incluir una introducción explicando qué es Apache Tomcat y para qué se utiliza.

---

## **Instrucciones**

### **1. Introducción**
- Explicar **qué es Apache Tomcat** y cuáles son sus principales usos en el desarrollo y despliegue de aplicaciones web Java.

### **2. Preparación del entorno**
- Instalar y verificar que el sistema tiene instalado el **JDK (Java Development Kit)**.
- Configurar la variable de entorno `JAVA_HOME`.

### **3. Instalación de Apache Tomcat**
- Descargar la versión estable más reciente de Apache Tomcat desde su [página oficial](https://tomcat.apache.org/).
- Extraer y mover los archivos al directorio correspondiente.
- Configurar los permisos necesarios para ejecutar Tomcat.

### **4. Configuración básica**
- Configurar el archivo `server.xml` para personalizar el puerto HTTP (por ejemplo, cambiar el puerto 8080 por 8081).
- Configurar el archivo `tomcat-users.xml` para definir un usuario con permisos de administración.

### **5. Despliegue de una aplicación de prueba**
- Crear una aplicación Java simple (por ejemplo, una página web básica con un formulario o un mensaje "Hello, World!").
- Generar un archivo WAR y desplegarlo en el servidor Tomcat.

### **6. Pruebas y verificación**
- Acceder a la consola de administración de Tomcat desde el navegador y probar el despliegue de la aplicación.
- Verificar los logs (`catalina.out`) para asegurar que el servidor y la aplicación se están ejecutando correctamente.

### **7. Documentación**
- Crear un manual técnico en formato MarkDown que incluya:
  - Introducción explicando qué es Apache Tomcat y para qué se utiliza.
  - Descripción del proceso de instalación y configuración.
  - Capturas de pantalla de cada paso (con un breve texto explicativo).
  - Explicación de posibles errores y cómo solucionarlos.
  - Pruebas de funcionamiento (incluyendo capturas del navegador mostrando la aplicación desplegada).
  - Conclusión.


## **Requisitos del manual**
- **Formato**: Documento MarkDown introducción, desarrollo y conclusiones.
- **Estructura**:
  1. Introducción: ¿Qué es Apache Tomcat y para qué se utiliza?
  2. Requisitos previos.
  3. Instalación y configuración (detallado paso a paso).
  4. Despliegue de una aplicación.
  5. Problemas encontrados y soluciones.
  6. Conclusión.
