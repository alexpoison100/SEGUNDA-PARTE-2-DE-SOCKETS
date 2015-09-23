# SEGUNDA-PARTE-DE-SOCKETS
0-INTEGRANTES: 

            JOSE ALEXANDER MUÑOZ   
            JESUS CUESTA
            
1-DESCRIPCIÓN DE LOS PROGRAMAS  

Socket utils

basics-01.py: Este programa muestra el uso básico de la clase toma en particular, cómo obtener el nombre de host de un servidor en el que se ejecuta el código.

basics-02.py: Este programa muestra cómo obtener la IP de un servidor dado su nombre.

basics-03.py: Este programa muestra cómo obtener el nombre de un servicio de red por su nombre de protocolo y número de puerto.

NTP Client

basics-04.py: Este programa se ejecuta como un cliente NTP utilizando la biblioteca ntplib. Este programa le pide a un servidor NTP para la hora actual y lo imprime.

basics-05.py: Este código crea un protocolo de tiempo de red simple.

HTTP Client

socket-01.py: Este programa muestra como crear un socket que es del tipo IPv4 (socket.AF_INET) y es orientado a conexion (socket.SOCKET_STREAM a.k.a. TCP)

socket-02.py: Este programa muestra la dirección IP asignandole un host.

socket-03.py: Este programa esta vez utiliza el Socket.connect para conectar con el servidor de www.google.com.

socket-04.py: Este programa muestra cómo se puede enviar una petición HTTP al servidor HTTP.

socket-05.py: Muestra cómo recibir la respuesta desde un servidor HTTP.


Socket server

server-01.py: En este programa se utiliza la función socket.bind () que es un método para enlazar un socket con un host y el puerto dado.

server-02.py: En este programa el socket.listen () y socket.accept () están expuestos y al ejecutar el programa espera por una conexion llamada bloqueante es decir que no se ejecutara la siguiente linea de codigo hasta tanto alguien no se conecte a este IP y ese puerto.

server-03.py: Este programa muestra cómo un servidor recibe una conexión a continuación, cómo responde al cliente.

server-04.py: En este programa se crea un bucle infinito con el fin de ejecutar el servidor siempre.

server-05.py: Este programa crea un servidor multiproceso que acepta conexiones desde varios clientes y que es capaz de asistir a ellas simultáneamente.El programa servidor principal acepta una conexión y crea un nuevo hilo para manejar la comunicación para la conexión, y luego el servidor se remonta a aceptar más conexiones.


Echo Service

Echo-server.py - Echo-client.py: La función de estos dos programas es que un host en este caso (echo-cliente.py) puede conectarse a un servidor que soporta el Protocolo Echo usando el Protocolo de Control de Transmisión (TCP ) en el número de puerto conocido, en este caso (port 8888). El servidor envía una copia idéntica de los datos que recibe del cliente.

El Protocolo Echo es un servicio en el protocolo de Internet suite definido en RFC 862. Se propuso originalmente para las pruebas y la medición de los tiempos de ida y vuelta [ cita requerida ] en las redes IP .

2-COMO EJECUTAR CODIGO FUENTE

Los script en Python normalmente se guardan con la extensión .py no es estrictamente necesario hacerlo de esa manera, puede no llevar extensión incluso, pero colocaremos la extensión .py por cuestiones de orden, digo, me imagino que quieres diferenciarlo del resto de ficheros que tengas.

Para comenzar, abrimos un editor de texto, ya sea Mousepad, Gedit, Kate, Vi, Nano, Emacs o el que gusten, luego vamos donde esta el código fuente de cada programa en este gihub guardado, le damos copiar,abrimos el editor de texto le damos pegar y por el ultimo guardar con la extensión .py.

Luego lo guardamos con el nombre ejemploPython.py, abrimos una terminal (ctrl t) buscamos el directorio donde se haya guardado el archivo .py y luego solo tenemos que poner:

$ python ejemploPython.py

Y ya debe de funcionar.

Para ejecutar los programas Echo service que son echo-server y echo-cliente tocaria asi:

En una terminal:

$ python echo-server.py --port 8888

En otra terminal:

$ python echo-client.py --port 8888

