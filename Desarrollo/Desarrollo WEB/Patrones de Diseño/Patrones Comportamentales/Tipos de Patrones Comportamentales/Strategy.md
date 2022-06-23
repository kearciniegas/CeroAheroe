## Strategy

Este patron nos permite definir una familia de algoritmos, es decir colocar cada uno de ellos en clases separadas para que sus objetos se puedan trabajar de forma intercambiable. Este patron se puede usar cuando se trabaja con muchas clases similares, entendiendo que estas solo se diferencian en la forma de ejecucion de algunos comportamientos.

- Ventajas:
	- Permite intercambiar algoritmos que se hallan usado dentro de un objeto en su ejecución.
	- Permite aislar los detalles al implementar un algoritmo del codigo que utiliza.
	- Se puede cambiar la herencia por la composición.
	- Principio de abierto/cerrado. Se puden introducir nuevas estrategias sin modificar el contexto.

- Desventajas:
	- Si solo se estan manejando pocos algoritmos que rara vez cambian, es innecesario complicar el programa con nuevas clases e interfaces que se implementan con el patron.
	- Los clientes deben conocer las diferentes estrategias para poder elegir la más adecuada.
	- 