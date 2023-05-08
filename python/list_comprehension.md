# List comprehension in Python

## Creating Lists in Python

### With for loops

```
list = []
for i in range(10):
    list.append(i * i)
```

### With the map() object

```
list = [1.09, 23.56, 57.84, 4.56, 6.78]
for i in range(10):
    new_list = map(lambda x: x**2, list)
```

### With List comprehension

```
# The parts of the list comprehension are:
#   -expression: expression that returns a value or a function call
#   -member: value for the iteration
#   -expression: a list, set, sequence, generator or any ohter object

list = [i * i for i in range(10)]
```
