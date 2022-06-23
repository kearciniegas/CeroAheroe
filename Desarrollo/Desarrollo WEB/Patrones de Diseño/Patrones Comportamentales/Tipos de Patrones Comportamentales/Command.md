## Command

Este patron nos permite convertir una solicitud en un objeto independiente con toda la información necesaria de la solicitud. De este modo se pueden parametrizar los metodos con diferentes solicitudes, como tambien poner en cola la ejecución de una solicitud y a la vez soportar operaciones que no se puedan realizar.

- Ventajas:
	- Permite aplicar el principio de responsabilidad unica.
	- Principio de abierto/cerrado, es decir que se pueden introducir nuevos comandos en la aplicación sin alterar el codigo cliente existente.
	- Se puede usar el deshacer/rehacer.
	- se puede ensamblar un grupo de comandos simples y generar uno complejo.

- Desventajas:
	- El codigo puede generar complicaciones debido a la implementación de una nueva capa entre emisor y receptor.