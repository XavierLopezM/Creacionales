# Creacionales
## Taller Creacional DS
### Análisis de los patrones de diseño vistos en clase e indique los pro y contra de usar dichos patrones en el desarrollo de este sistema.

## Abstract Factory
*Pro´s:*
Podriamos declarar de forma explícita interfaces para cada producto diferente de la familia computador (gamers, oficina, pc, laptos). Después podemos hacer que todas las variantes de los productos sigan esas interfaces. Por ejemplo, todas las variantes de gamers pueden implementar la interfaz Silla, así como todas las variantes de Oficina pueden implementar la interfaz Oficina, y así sucesivamente.

*Contras:*
Puede ser que el código se complique más de lo que debería, ya que se introducen muchas nuevas interfaces y clases junto al patrón

## Builder Patterns
Pro´s:
Nos permitira crear una interface (Un builder) con los pasos para crear las computadoras, luego podremos crear las computadoras con sus diferentes caracteristicas

Contras:
Hay que crear las clases de las computadoras con los pasos que se encuentran en la interface.


## Factory Method
Pro´s:
Nos permitiria hacer una superclase en la que se cree la computadora y luego una subclase de cada computadora que implemente los mismos metodos pero con diferentes, pues las computadoras son diferentes.

Contras:
Hay que introducir el codigo en las dos subclases

## Prototype:
Pro´s:
*Se utiliza para restringir las operaciones de memoria & base de datos manteniendo la modificación al mínimo utilizando copias de objetos.
*Crea un a copia de clase utilizando una interfaz, que admite el netodo clonar, y cada clase que implemente dicha interfaz, se podra copiar hasta sus campos privados, en los que no se pueden acceder.

Contras:
*Dado que debe conocer la clase del objeto para crear un duplicado, su código se vuelve dependiente de esa clase.


## Singleton:
Pro´s:
Proporciona el acceso global de una instancia, con un metodo de creacion estatico, que actue como constructor de la clase global
Controla el acceso a algun recurso compartivo, para ello es hacer que esa clase globalizada tenga una sola instancia y su constructor este en privado, para evitar que otros objetos puedan acceder a esta informacion.

Contras:
Viola un principio de SOLID, el principio de SRP.

