## Adstract Factory

Este patron nos permite crear familias de objetos relacionados sin especificar sus clases concretas, es decir que se puede utilizar cuando se requiere que el codigo funcione con varias familias de objetos relacionados y hay que tener en cuenta que no deben depender de clases concretas para permitir una futura extensibilidad.

- Ventajas:
	- Todos los objetos que se crean desde la fabrica manejan una compatibilidad entre si.
	- Se evita que los objetos de acoplen de manera permanente con el codigo cliente.
	- Principio de responsabilidad unico. se puede mover el codigo de creación de objetos a un solo lugar.
	- Principio de abierto/cerrado.

- Desventajas:
	- Se puede complicar el codigo más de lo necesario, por que introducen muchas interfaces y clases que se implementan con el patron.