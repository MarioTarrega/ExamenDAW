# Ejercicio 2

Lo primero que haremos para acceder a dicha maquina sera utilizar el comando _ssh (nombreUsuario)@ipMaquina_ unavex ejecutado el comando nos dira que hemos creado una __key fingerprint__ y escribiremos ***yes*** , una vez escrito eso ya estaremos dentro de la maquina servidor mediante ssh.

![Comprobación Acceso SSH](https://github.com/MarioTarrega/ExamenDWC/blob/main/Acceso_SSH.png)

A continuación para ir al "Escritorio" y crear un archivo (.txt) haremos los siguientes pasos:
1. Utilizaremos el comando _cd Escritorio/_ para acceder al directorio del Escritorio.
2. Ahora vamos a crear el archivo el cual nombremos con nuestro nombre (TuNombreyApellidos.txt) para ello utilizaremos el comando _touch TuNombreyApellidos.txt_.

![Crear Archivo](https://github.com/MarioTarrega/ExamenDWC/blob/main/Crear_Archivo.png)

Para escribir el resultado del whoami utilizaremos una redirección para que añada directamente el resultado del comando a nuestro archivo de texto en nuestro caso seria _whoami > TuNombreyApellidos.txt_

![Comprobación del Whoami](https://github.com/MarioTarrega/ExamenDWC/blob/main/Comando_Whoami_m%C3%A1s_Comprobacion.png).

Ahora queremos añadir al final de dicho archivo el resultado del comando para saber todas las maquinas que estan conectadas por SSh, el comando a utilizar es bastante parecido al anterior, lo unico que cambia que en lugar de utilizar un simbolo de "mayor que" utilizaremos dos,
el comando quedaria de la siguiente manera _who >> TuNombreyApellidos.txt_

![Comprobación Añadir Who Final del Archivo](https://github.com/MarioTarrega/ExamenDWC/blob/main/Comando_Who_mas_Comprobacion.png)
