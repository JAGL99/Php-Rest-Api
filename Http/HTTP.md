**_Hypertext Transfer Protocol (HTTP)_** (o **_Protocolo de Transferencia de Hipertexto en español)_** es un protocolo de la [capa de aplicación](http://es.wikipedia.org/wiki/Capa_de_aplicaci%C3%B3n) para la transmisión de documentos hipermedia, como HTML. 

Fue diseñado para la comunicación entre los navegadores y servidores web, aunque se puede utilizar para otros propósitos también. Sigue el clásico [modelo cliente-servidor](http://es.wikipedia.org/wiki/Cliente-servidor), en el que un cliente establece una conexión con el servidor, realiza una petición y espera hasta que recibe una respuesta del mismo. 

Se trata de un [protocolo sin estado](http://es.wikipedia.org/wiki/Protocolo_sin_estado), lo cual significa que el servidor no guarda ningún dato (estado) entre dos peticiones. Aunque en la mayoría de casos se basa en una conexión del tipo TCP/IP, se puede usar sobre cualquier [capa de transporte](http://es.wikipedia.org/wiki/Capa_de_transporte) segura o de confianza, es decir, sobre cualquier protocolo que no pierda mensajes silenciosamente, tal como UDP.

**HTTP** define un conjunto de **métodos de petición** para indicar la acción que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados _HTTP verbs_.

Algunos de estos son:
- [[HTTP/GET]]
- [[HTTP/POST]]
- [[HTTP/PUT]]
- [[HTTP/DELETE]]
- [[HTTP/PATCH]]

## Códigos de estado de respuesta HTTP
Los códigos de estado de respuesta **HTTP** indican si se ha 
completado satisfactoriamente una solicitud **HTTP** específica. 

Las respuestas se agrupan en cinco clases:
1. [Respuestas informativas](https://developer.mozilla.org/es/docs/Web/HTTP/Reference/Status#respuestas_informativas) (`100`–`199`),
2. [Respuestas satisfactorias](https://developer.mozilla.org/es/docs/Web/HTTP/Reference/Status#respuestas_satisfactorias) (`200`–`299`),
3. [Redirecciones](https://developer.mozilla.org/es/docs/Web/HTTP/Reference/Status#redirecciones) (`300`–`399`),
4. [Errores de los clientes](https://developer.mozilla.org/es/docs/Web/HTTP/Reference/Status#errores_de_cliente) (`400`–`499`),
5. [Errores de los servidores](https://developer.mozilla.org/es/docs/Web/HTTP/Reference/Status#errores_de_servidor) (`500`–`599`).