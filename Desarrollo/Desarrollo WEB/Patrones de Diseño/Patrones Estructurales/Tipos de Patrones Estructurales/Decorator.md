## Decorator

Este patron permite añadir funcionalidades a objetos colocandolos dentro de objetos encapsuladores especiales que contienen estas funcionalidades, Se puede usar cuando se necesite asignar funcionalidades adicionales a objetos durante el tiempo de ejecución.

- Ventajas:
	- Se puede extender el comportamiento de un objeto sin crear una nueva subclase.
	- Se puede añadir o eliminar reponsabilidades de un objeto durante su ejecución.
	- Principio de responsabilidad unico. Se puede dividir una clase monolitica con muchas variantes de comportamientos, en varias clases mas pequeñas.

- Desventajas:
	- Resulta dificil eliminar un wrapper especifico de la pila de wrappers.
	- Se complica al intentar implementar un decorador de forma que su comportamiento no dependa del orden en la pila de decoradores.
	- El codigo de configuración inicial de las capas puede tener un aspecto desagradable.