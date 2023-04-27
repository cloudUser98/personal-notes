# replace() method for strings

### Parameters:

#### pattern
```
string or object, if the value does not have the replace method it will be coerced to a string.
```

#### replacement
```
It can be a function or a string, if it is a fu nction it will be invoked for each match.

The function can recive the next parameters:

match: The matched substring

p1, p2, ..., pN: The nth string found by a capture group

offset: Offset of the matched substring within the whole string being examined

string: The string being examined

groups: Object whose keys are the used group names, and whose values are the matched portions.
```

Tags:
  Javascript