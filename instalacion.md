### INSTALACIÓN Y PRIMEROS PASOS

Empecemos. 

Aconsejable realizar los siguientes pasos antes de la instalación

```sudo apt update```

Vamos a lo interesante

```apt install nginx``` --> Instalamos el servicio web nginx

```systemctl enable nginx``` --> Activamos el demonio para que se inicie nginx cuando arraquemos el servidor

```systemctl restart nginx``` --> Reiniciamos el servicio

Buscamos en el navegador la ip de nuestro servidor, o bien, si estamos trabajando dentro del servidor, buscamos localhost

![img](https://i.imgur.com/gdMqcz1.png)
