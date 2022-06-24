## Arquitectura Hexagonal

Es un estilo de arquitectura de software que permite al programador distinguir desde un plano mas conceptual el interior y exterior del software. es decir la parte interior son los casos prácticos y el modelo domain esta construido sobre ello. La parte exterior es el UI, Base de Datos, Mensajeria, etc. hay que tener presente que la conexción entre la parte interna y externa es por medio de puertos, y sus implementaciones equivalen a los adaptadores. Por Ultimo se puede decir que la AH promueve la separación de asuntos por medio de la encapsulación de la lógica en diferentes capas de la aplicación, lo cual facilita aislar las partes de manera correcta, asi como mejor testabilidad y mejor manejo del codigo de negocio especifico.

- Para que se usa la arquitectura hexagonal:
	Esta arquitectura se utiliza para aislar e independizar al modelo de dominio de los elementos externos, de manera que si los elementos externos cambien estos no afecten al modelo y a la vez se puedan hacer cambios en el dominio para que los elementos externos requieran la menor cantidad de cambios.
	

- Ventajas:
	- Es una guia para crear software de calidad con sus directrices y reglas.
	- Se puede utilizar de manera mas facil patrones de diseño como el solid.
	- Se puede desacoplar la logica de negocio del metodo de entrega, gracias a los adaptadores.
	- Al ser una arquitectura basada en inyección de dependencias, se pueden realizar de mejor manera los test unitarios a los diferentes componentes.

- Desventajas:
	- Complejiad adicional, debido a la creación de más capas.
	- De dificil creación y mantenimiento.
	- No hay ninguna orientación sobre la organización del codigo, entre sus directorios y capas.

- Los 3 componentes de la arquitectura hexagonal son:
	- [[Modelo Domain]].
	- [[Puertos]].
	- [[Adaptadores]].
