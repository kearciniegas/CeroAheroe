## Singleton

Este patron nos permite asegurarnos de que una clase tenga una única instancia, y tambien se debe proporcionar un punto de acceso global a dicha instancia. Este patron se puede utilizar cuando una clase deba tener solo una instancia disponible para todo los clientes.


- Ventajas.
	- Permite que una clase tenga una unica instancia.
	- Se obtiene un punto de acceso global a dicha instancia.
	- El objeto singleton cuando se requiere por primera vez.

- Desventajas:
	- Presenta vulnerabilidades al principio de responsabilidad única. es decir el patron resuelve dos problemas al mismo tiempo.
	- Puede enmascarar un mal diseño, por ejemplo, cuando los componentes del sistema saben demasiado los unos sobre los otros.
	- Requiere de tratamiento especial y con un entorno de multiples hilos de ejecución, para que estos hilos no creen multiples objetos singleton.
	- Es complicado realizar pruebas unitarias del codigo cliente del singleton debido a que los frameworks de pruebas dependen de la herencia.
