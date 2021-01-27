### CASOS PRACTICOS

Realizaremos algunos ejemplos para tener soltura con nginx y aprender sus principales funcionalidades

1- Versión de Nginx instalado.

    Entrada:
      nginx -v

    Salida:
      nginx version: nginx/1.14.2
    
2- Servicio Asociado

    systemctl status nginx

3- Ficheros de configuración

   Aqui encontraremos todos los ficheros de configuracion para nginx ```/etc/nginx```. El fichero mas genérico, o mas globalizado por asi decirlo (que su configuracion va a estar en todas las paginas) es ```nginx.conf```.


4- Pagina web por defecto

   - Vamos a cambiar la pagina web por defecto.
    
    ```cp /var/www/html/index.html /var/www/html/index.html.ORIGINAL``` --> Realizamos una copia del index para no perderlo
    ```echo "<h2> Bienvenidos a Mi servidor web nginx</h2>" > /var/www/html/index.html``` --> Codigo simple de html 
   
   - Recargamos la pagina web y...
    
   ![img](https://i.imgur.com/QWIKP7X.png)
