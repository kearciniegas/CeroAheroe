## Proxy

Este patron permite proporcionar un sustituto o marcador de posición para otro objeto, es decir que controla el acceso al objeto original, de este modo permite hacer algo antes o despues de que la solicitud llegue al objeto original. Este patron se puede utilizar para mutiples acciones una de ellas es: para el control de acceso, es cuando quiere que unicamente los clientes especificos sean capaces de utilizar el objeto de servicio.

- Ventajas:
	- Puedes controlar el objeto de servicio sin que los clientes lo sepan.
	- Se puede gestionar el ciclo de vida del objero de sevicio.
	- El proxy funciona aunque el objeto de sevicio no este listo o disponible.
	- Principio de abierto/cerrado. Se pueden introducir nuevos proxies sin cambiar el servicio o los clientes.

- Desventajas:
	- El codigo se complica debido a que se introducen gran cantidad de nuevas clases.
	- La respuesta del servicio puede restrasarse.