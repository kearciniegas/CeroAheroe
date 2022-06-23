## Bridge

Este patron permite dividir una clase grande, o un grupo de clases estrechamente relacionadas, en dos jerarquias separadas (adstracción e impementación) y nos permite desarrollarlas de manera independiente la una de la otra. Lo podemos usar para dividir y organizar una unica clase que contenga muchas variantes de una solo funcionalidad.

- Ventajas:
	- Puedes crear clases y aplicaciones independientes de plataforma.
	- El codigo cliente trabaja con abstracciones de alto nivel, es decir no esta expuesta a los detalles de la platforma.
	- Principio de abierto/cerrado. Se pueden introducir nuevas adstracciones e implementaciones independientes entre si.
	- Principio de responsabilidad unico. Se puede centrar en la logica en la adstracción y los detalles de la plataforma en la implementación.

- Desventajas:
	- Se puede complicar al aplicar este patron a una clase muy cohesionada.