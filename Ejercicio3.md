### Ejercicio3

En este ejercicio tenemos que realizar un VirtualHost con Apache2.

1. Tener instalado Apache2, si no lo teneis aqui os dejo una memoria donde esta paso a paso como instalarlo (https://docs.google.com/document/d/1iB_oAdPqTWdDSrQ-AZLgzhEzTw2qoBiYVydTFzRZsf0/edit#heading=h.wd0a2densgq)

2. Una vez instalado Apache crearemos una carpeta en __/var/www__ con nuestras iniciales y ahi es donde guardaremos nuestro index.html para poder acceder a el más tarde.
![Imagen comandos Carpeta](https://github.com/MarioTarrega/ExamenDAW/blob/main/Carpeta_VAR_WWW_MTB.png)

3. Luego editaremso el archivo de configuración donde le indicaremos la ruta anterior para decirle que es de ahi de donde tiene que coger el HTML y modificaremos las lineas de __DocumentRoot__ y __ServerName__
![Imagen Archivo Modificado](https://github.com/MarioTarrega/ExamenDAW/blob/main/Archivo_Conf_VH.png)

4.Tambien tendremos que modificar el archivo Hosts para indicarle a nuestra ip de localhost que cuando busquemos _daw.ejercicio3.com_ nos muestre el index.html que tenemos en nuestra ruta, para modificarlo lo encontreremos en la carpeta _etc_, y para editarlo ejecutaremos el comando __sudo nano hosts__ y ahi añadiremos la ip 127.0.0.1  y el nombre del dominioLocal _daw.ejercicios3.com_ una vez eso modificado ya deberia de funcionar nuestro hostVirtual.

![Imagen Archivo Hosts](https://github.com/MarioTarrega/ExamenDAW/blob/main/Archivo_Hosts.png)
![Imagen Comprobación](https://github.com/MarioTarrega/ExamenDAW/blob/main/Comrobacion_Ejercicio3.png)


En este ejercicios si estabas avispado solo tenias que modificar un archivo ya que en clase ya instalamos Apache y hicimos ya la modificacion de dicho archivo, asi que este ejercicio esta medio regalado por no decir que esta regalado.
