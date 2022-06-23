## Factory Method

Es patron nos permite crear objetos atravez de una interfaz de una superclase, tambien permite que las subclases alteren los tipos de objetos que se crearan. Este patron se puede utilizar cuando no se conocen las dependencias y los tipos de datos con lo que debe fucnionar el codigo.

- Ventajas:
	- Se evita un acoplamiento fuerte entre el creador y los objetos concretos.
	- Principio de responsabilidad unica. Permite mover el codigo de creación de objetos a un lugar del programa el cual nos permite que el codigo sea mas facil de mantener.
	- Principio de abierto/cerrado, Se pueden añadir nuevos tipos de productos en el programa sin modificar el codigo cliente existente.

- Desventajas:
	- El codigo puede complicar debido a que se deben incorporar multidud de subclases para poder implementar el patron.