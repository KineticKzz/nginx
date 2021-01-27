## COMPARATIVA CON APACHE
Nginx fue inicialmente desarrollado con el fin explícito de superar el rendimiento ofrecido por el servidor web Apache. Sirviendo archivos estáticos, Nginx usa dramáticamente menos memoria que Apache, y puede manejar aproximadamente cuatro veces más solicitudes por segundo. Este aumento de rendimiento viene con un costo de disminuida flexibilidad, como por ejemplo la capacidad de anular las configuraciones de acceso del sistema por archivo (Apache logra esto con un archivo .htaccess, mientras que Nginx no tiene desarrollada tal funcionalidad). Anteriormente, incorporar módulos de terceros en Nginx requería recompilar la aplicación fuente con los módulos enlazados estáticamente. Esto fue parcialmente superado en la versión 1.9.11 de febrero de 2016, con la adición de carga dinámica de módulos. Sin embargo, los módulos aun deben ser compilados al mismo tiempo que Nginx, y no todos los módulos son compatibles con este sistema; algunos requieren el antiguo proceso de enlazado estático.

Una pagina muy interesante donde ver estadisticas y rankings sobre servidores web es la siguiente:

https://w3techs.com/technologies/cross/web_server/ranking

En ella encontramos una grafica con un porcentaje que muestra la caida de paginas web con los distintos servidores web como Apache, Nginx y Cloudflare Server
