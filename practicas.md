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
   
   
5- Virtual Hosting
  
  - Tendremos dos sitios virtuales con la misma ip y el mismo puerto, por lo tanto, lo primero que tenemos que hacer es crear dos carpetas a la misma altura de `/var/www/html`, por lo tanto haremos lo siguiente:

    ```mkdir /var/www/html/web1 /var/www/html/web2```
 
    - En ellas vamos a introducir un index.html basico:
    
    ```echo "<h2>Esta es mi web1</h2>" > /var/www/web1/index.html```
    
    ```echo "<h2>Esta es mi web2</h2>" > /var/www/web2/index.html```
    
    
