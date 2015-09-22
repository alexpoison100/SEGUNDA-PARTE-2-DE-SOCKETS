# SEGUNDA-PARTE-DE-SOCKETS
INTEGRANTE: JOSE ALEXANDER MUÑOZ   
            JESUS CUESTA
            
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
