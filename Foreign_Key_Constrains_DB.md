# Foreign Key Constrains - DB

Es una construcción de la base de datos y fuerza la integridad de la relación por llave entre una tabla padre e hijo, permitiendole a la tabla hijo solo poder referenciar una fila de la tabla padre si esta existe.

Servicios como PlanetScale no permiten el uso de estos contraints por las siguientes razones:
- La manera en la que MySQL implementa estos contrains interfiere con operaciones DDL.

Tags:
  Software_related_concepts