**REST** es un conjunto de límites relacionados con la arquitectura. 

Los desarrolladores de las [[API]] pueden implementarlo de distintas maneras.

La información se entrega por medio de [[HTTP]] en uno de estos formatos: **JSON** , **HTML**, **XLT**, **Python**, **PHP** o **texto sin formato**. 

**JSON** es el formato de archivo más conocido.

Asimismo, es necesario tener en cuenta otro aspecto: los  encabezados  y los parámetros también son importantes en los  métodos [[HTTP]]  de la  solicitud de la [[API]] de **RESTful**, ya que contienen información de  identificación  esencial sobre los metadatos, la autorización, el identificador uniforme de recursos (URI), el almacenamiento en caché, las cookies y otros elementos de la  solicitud.

Para que una [[API]] se considere de RESTful, debe tener:

- Una arquitectura cliente-servidor compuesta de clientes, servidores y recursos, con la gestión de solicitudes a través de [[HTTP]].
- Una comunicación entre el cliente y el servidor sin estado, lo cual implica que no se almacena la información del cliente entre las solicitudes [[GET]] y que cada una de ellas es independiente y está desconectada del resto.
- Datos que puedan almacenarse en caché y optimicen las interacciones entre el cliente y el servidor.
- Una interfaz uniforme entre elementos que permita que la información se transfiera de manera  estándar, para lo cual:
    - Los recursos solicitados deben ser identificables e independientes de las representaciones enviadas al cliente.
    - El cliente debe poder manipular los recursos a través de la representación que recibe, ya que esta contiene suficiente información para ello.
    - Los mensajes autodescriptivos que se envíen al cliente deben contener la información necesaria para describir la manera de procesarla.
    - Debe contener hipertexto o hipermedios, lo cual significa que cuando el cliente  acceda a algún recurso, tiene que poder utilizar hipervínculos para buscar las demás acciones que se encuentren disponibles en ese momento.
- Un sistema en capas que organiza en jerarquías invisibles  para  el cliente cada tipo de servidores (los encargados de la seguridad, del equilibrio de carga, etc.) que participan en la recuperación de la información solicitada.
- El código disponible según se solicite (opcional), es decir, la capacidad para enviar códigos ejecutables del servidor al cliente cuando se requiera, lo cual amplía las funciones del cliente.