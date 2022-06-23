## Mediator

Este patron nos permite reducir las dependencias caóticas entre objetos. Es decir restringe las comunicaciones directas entre objetos, forzandolos a colaborar únicamente a través de un objeto mediador.

- Ventajas:
	- Principio de responsabilidad única. con esto se pueden extraer las comunicaciones entre varios componentes dentro de un único sitio, de este modo es fácil de comprender y mantener.
	- Principio de abierto/cerrado. se pueden agregar nuevos mediadores sin cambiar los componentes existentes.
	- Permite reducir el aclopamiento de muchos de los componentes de un programa.
	- Se pueden reutilizar componentes individuales con mayor facilidad.

- Desventajas:
	- A largo plazo un objeto mediador puedo llegar a convertirse en un objeto todo poderoso.
