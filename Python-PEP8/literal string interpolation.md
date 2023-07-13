# Literal string interpolation(f-strings)

Fueron introducidas en PEP 498.
Es una manera diferente de dar formato a string literals en Python, siendo las otras
el formateo con % y el metodo str.format(). Este mecanismo permite embedir expresiones
dentro de los strings. Estas expresiones son evaluadas en runtime y no son un valor
constante.

Para usar este mecanismo se tiene que agregar el prefijo f al literal string al cual
se le dara formato. Esta tipo de formato es consdierado mas rapido que sus antecesores.

ejemplo:
```python
    value = "ejemplo"
    print( f"Este es un {value}"
```
