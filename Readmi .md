# Los operadores lógicos
 nos permiten trabajar con valores de tipo booleano. Un valor booleano o bool es un tipo que solo puede tomar valores True o False . Por lo tanto, estos operadores nos permiten realizar diferentes operaciones con estos tipos, y su resultado será otro booleano.
 ## Operador and
El operador and evalúa si el valor a la izquierda y el de la derecha son True, y en el caso de ser cierto, devuelve True. Si uno de los dos valores es False, el resultado será False.
``` python
print(True and True)   # True
print(True and False)  # False
print(False and True)  # False
print(False and False) # False
```
## Operador or
El operador or devuelve True cuando al menos uno de los elementos es igual a True. Es decir, evalúa si el valor a la izquierda o el de la derecha son True.
``` python
print(True or True)   # True
print(True or False)  # True
print(False or True)  # True
print(False or False) # False
```