# Clean Code

El codigo limpio es un conjunto de practicas y reglas las cuales su objetivo es tener codigo facil de leer, entender que tenga bajo acoplamiento, alta cohesión y que sea de  facil mantenimiento o adaptación.

## Para que sirve el clean code
La idea de los principios de clean code es convertir el desarrollo web y el mantenimiento de codigo en algo cada  vez mas simple.
Un código con muchos ajustes durante mucho tiempo, se vuelve imposible de mantener, por lo que en muchas ocaciones prefieren crear un nuevo codigo que resuelva el problema que tratar de hacer mas grande el codigo creando mas codigo dificil de probar y mantener.

## Cuales son las reglas del clean code

- **Claridad en los nombramientos**
	- Variables
	- Metodos
	- Clases
	- Parametros
	- Commits
Cuando definimos un nombre siempre debemos tener encuenta dos aspectos principales:
	- Debe ser preciso y claro, facil de entender. 
	- No te debe importar nombre largos, es mejor se claro que usar abreviasiones que pueden confundir a alguna persona.
	
- **Regla del boy scout**
Esta regla hace referencia a que si trabajamos en un clase, metodo o función debemos dejarla lo mejor posible *"lo mas limpio"*, mejor de como la encontramos.

- **Debes ser el verdadero autor del codigo**
Como desarrollador es debemos interpretar el *rol*  de autor de nuestra historia una historia escrita en codigo pero al final una historia, para escribir una buena historia hay que tener una buena narrativa "literal" y como lo hacemos, exiten dos reglas que nos ayudan a mejorar la narrativa del codigo son:
	- Las funciones deben ser pequeñas.
	- Deben ser aún mas pequeñas.

- **Don't Repeat Yourself (DRY)**
Este es uno de los principios del codigo limpio *"No te repitas a ti mismo"* **DRY** define que se debe evitar repetir codigo, esto haciendo dificil el mantenimiento del codigo por que si un codigo hace lo mismo en muchos lugares y luego toca modificar ese proceso toca modificarlo en todos.
![[Dry Don't Repeat Yourself.png]]

- **Comentar solamente lo necesario**
Este principio afirma que los comentarios pueden hacerse, sin embargo debe realizarse solamente cuando es absolutamente necesario. Segun el Uncle Bob en el libro Clean Code, los comentarios mienten en ocaciones los mentarios no estan actualizados con lo que realmente hace el codigo por algun cambio o modificación.

- **Tratamiento de errores**
Existe una frase muy conocida en le mundo del desarrollo del autor Michael Feathers * *"las cosas siempre pueden salir mal, pero los programadores son los responsables que el codigo siga funciando"*.
Es decir, tratar las excepciones de forma correcta es un gran paso para el programador de desarrollo.

- **Test limpio**
Realizar test en el área de programación es la parte mas importante del desarrollo es donde garantizamos la calidad del codigo realizado, un codigo solo se puede considerar como "limpio" cuando es pasado a travez de pruebas, para realizar pruebas estas son algunas de la reglas a seguir:
	- Fast: El test deber ser rapido, permitiendo que sea pueda ejecutar muchas vez en cualquier momento.
	- Indepediente: Debe ser independiente, con el fin de evitar que sea afectado por otras clases o metodos y no sean probados.
	- Repetible: Debe permitir la repitición de los test, muchisimas veces sin importar el ambiente que las realicemos.
	- Self-Validation: Los test bien escritos retornan con las datos precisos asi para que la respuesta de la prueba no sea subjetiva.
	- Timely: Los test deben seguir estrictamente el criterio de puntualidad. El test deberia ser escrito antes que el mismo codigo.
	
- **SOLID**
Este es uno de los principios del codigo limpio SOLID son una siglas cada una de ella tiene un objetivo permitir implementar codigo con las mejores practicas posibles un codigo limpio.

## S
**Responsabilidad Única**
Este principio habla que cada clase o metodo debe tener una unica resposabilidad asignada.
## O
**Open/Closed Abierto Cerrado**
Este principio habla que las clases modulos o metodos, deben estar abiertas para crear nuevas funcionalidades pero cerrado para modificaciones.

## L
**Sustitución de liskov**
Este principio habla que si tenemos un clase hija y esta es sustituida no deberia afectar a la clase padre.

## I
**Segreción de Interfaces**
Este principio dice que ninguna clase deberia estar obligada a depender de los métodos que no utiliza.

## D
**Inversion de Dependencias**
No deben existir dependencias entre los módulos, en especial entre los módulos de bajo y de alto nivel. 