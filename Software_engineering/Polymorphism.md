# Polimorfismo

En la cienca de la computacion un objeto polimorfico es el cual es capaz de tomar
mas de una forma posible.

## Polimorfismo en la programacion

"En los lenguajes de programacion y teoria de tipado, polimorfismo es la exposicion
de una sola interfaz a diferentes tipos de entidades, o el uso de un solo simbolo
para representar multiples tipos diferentes"

El polimorfismo es una parte fundamental en el uso del paradigma de programacion orientada
a objetos.

## Tipos de polimorfismo

### Existen 4 tipos diferentes de polimorfismo:

- Subtype polymorphism(runtime)
- Parametric polymorphism(overloading)
- Ad hoc polymorphism(compile-time)
- Coercion polymorphism(casting)

### Polimorfismo de subtipado

Es el tipo mas comun de polimorfismo y suele ser el principal tipo cuando se habla
de este tema en general.

Como su nombre lo indica este tipo de polimorfismo se da cuando una sola clase o tipo
puede hacer referencia a multiples subtipos. Un ejemplo practivo podria ser tener
diferentes tipos de animales que provengan de la misma clase generica "Animal".

### Polimorfismo parametrico

Este tipo de polimorfismo se da cuando un solo metodo puede actuar/ser ejecutado
sobre diferentes tipos de datos sin importar.

Un ejemplo de esto puede ser el metodo pop() de listas en python el cual removera
un elemento de la lista sin importar su tipo.

### Polimorfismo Ad hoc

Este tipo de polimorfismo se da cuando una funcion del mismo nombre puede actuar
de diferentes maneras para diferentes tipos de datos.

Un ejemplo puede ser la funcion de suma de javascript la cual puede realizar la
suma de numeros o la concatenacion de cadenas de caracteres.

### Polimorfismo de coaccion

Se da cuando se altera directamente la clase de un elemento dentro de la logica
del codigo.

Un ejemplo podria ser la conversion de un dato tipo entero a tipo flotante en python
haciendo uso del metodo float().
