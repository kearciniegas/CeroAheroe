## Adapter

Este patron nos permite la colaboración entre objetos con interfaces incompatibles. Se puede usar cuando se requiera usar una clase existente con una interfaz incompatible con el resto de codigo, es decir que permite crear una clase intermedia con la funcion de traducir el codigo con una clase heredada.

- Ventajas:
	- Principio de responsabilidad unica. Se puede separar la interfaz con el codigo de conversion de datos de la logica de negocio primaria del programa.
	- Principio de abierto/cerrado. Permite integrar nuevos tipos de adaptadores sin descomponer el codigo.

- Desventajas:
	- Se complica de manera general el codigo, ya que se debe introducir un grupo de nuevas interfaces y clases.
