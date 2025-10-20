trabajo practico Estructura de datos, Parte teorica. 

TEORIA ENTREGA 1.

1 Explicar el concepto de encapsulamiento y su importancia en la programación orientada a objetos.

El encapsulamiento es uno de los pilares en la Programación Orientada a Objetos (POO), consiste en ocultar los detalles internos de un objeto y exponer únicamente lo que se desea de este para que el usuario pueda interactuar, es decir, busca proteger los datos de accesos indebidos o modificaciones externas. En este caso, la forma correcta para acceder a aquellos atributos o métodos ocultos serian mediante la implementación de setters, los cuales permiten asignar/modificar o getters cuyo fin consta de devolver el valor de dicho atributo, de esta manera nos aseguramos que no se le asignen valores inválidos o inconsistentes.

2 Analizar ventajas y desventajas de distintas representaciones de listas y pilas para gestionar reservas y equipaje.

Una lista es una estructura que nos permite almacenar elementos en un orden determinado adjuntándole a los mismos un índice. Por otro lado, las Pilas también son un tipo de estructura cuya finalidad radica en el almacenamiento de datos con la particularidad es una estructura LIFO, es decir, el último elemento en entrar es el primero en salir ambas estructuras cuentan con ventajas y desventajas a la hora de querer plantear una gestión de reservas y pasajes. 

Por el lado de las Lista consta con las facilidades de permitir un acceso directo a cualquier elemento mediante un índice, lo que permitiría facilitar la búsqueda de una reserva o equipaje en concreto, otro punto a destacar es la facilidad de agregar o eliminar elementos de la misma como también la versatilidad que estas poseen ya que nos permiten almacenar distintos tipos de datos. Los puntos negativos de la misma podrían ser, por ejemplo, la eficiencia ya que mover elementos cuesta tiempo proporcional al tamaño de la lista, el consumo de memoria o la organización. 

Las Pilas con respecto a las listas poseen una serie de ventajas como, por ejemplo, la simplicidad de manejo ya que son ideales para controlar procesos en un orden definido, como registrar el orden del equipaje también nos permiten modelar situaciones donde se requiere deshacer acciones o revisar el último elemento agrado como una última reserva pendiente y a su vez, las pilas constan de una inserción y eliminación rápida de elementos. Su contraparte es que su acceso es limitado ya que esta estructura nos permite únicamente consultar o modificar el elemento superior, no es óptima para la búsqueda o listado ya que por el tipo de estructura que es nos obliga a desapilar los elementos uno por uno y consta de una menor flexibilidad

3 Justificar la elección de atributos y métodos para modelar pasajeros, vuelos y reservas.

