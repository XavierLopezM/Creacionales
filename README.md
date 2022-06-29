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

Contras:


## Factory Method
Pro´s:
Nos permitiria hacer una superclase en la que se cree la computadora y luego una subclase de cada computadora que implemente los mismos metodos pero con diferentes, pues las computadoras son diferentes.

Contras:
Hay que introducir el codigo en las dos subclases




## Prototype:
Pro´s:

Contras:

## Singleton:
Pro´s:
Proporciona el acceso global de una instancia, con un metodo de creacion estatico, que actue como constructor de la clase global
Controla el acceso a algun recurso compartivo, para ello es hacer que esa clase globalizada tenga una sola instancia y su constructor este en privado, para evitar que otros objetos puedan acceder a esta informacion.

Contras:
Viola un principio de SOLID, el principio de SRP.

