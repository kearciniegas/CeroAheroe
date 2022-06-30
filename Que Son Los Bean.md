## Que son los Bean Desde Spring

Cuando se habla de Inversion de control y al crear una dependencia con multiples funcionalidades estas se pueden agregar al contenedor de espring boot, Un bean es una dependencia que es inicializada e instanciada por spring, es decir que solo se debe preocupar de como y donde utilizarla.

- Ejemplo de Creacion de funcionalidades de la dependencia:

#
	Public interface Dependencia {
		void implementation();
	}
	
	public class Objeto implements Dependencia {
		@Override
			public void implementation() {
				//
			}
	}
	public class Objeto2 implements Dependencia {
		@Override
			public void implementation() {
				//
			}
	}

- Ejemplo de creacion de la dependecia/Bean:

#
		@Bean
		public MyBean anyNameMethod() {
			return new MyBeanImpl();
		}
	}

Como se pudo observar en el ejemplo anterior al crear la dependencia y retornar MyBeanImpl: esta es una interfaz y la cual inyectaremos en otras partes del codigo.