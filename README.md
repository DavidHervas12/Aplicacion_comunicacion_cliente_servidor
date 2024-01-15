# Aplicacion_comunicacion_cliente_servidor

## Descripción
Esta es una aplicacion de mensajería cliente-servidor, su funcionamiento consiste en  
la apertura del servidor en un puerto específico, los clientes se podrán conectar mediante  
sockets en ese puerto, el servidor creará un hilo por cada cliente y estos se podrán  
comunicar entre ellos, enviando y recibiendo mensajes.

### Los tipos de mensaje son los siguientes:
- "?" muestra los usuarios conectados.
- "@nombreUsuario" envía un mensaje a un usuario en concreto.
- "" envía el mensaje a todos los usuarios conectados.
- "exit" cierra la sesión del cliente.

[Vídeo demo](https://youtu.be/8DrpdzO3shkhttps://youtu.be/8DrpdzO3shk)
