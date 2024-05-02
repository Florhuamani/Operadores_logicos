# OPERADORES LOGIGOS
Los operadores lógicos o logical operators nos permiten trabajar con valores de tipo ***booleano***. Un valor ***booleano o bool*** es un tipo que solo puede tomar valores ```True o False```. Por lo tanto, estos operadores nos permiten realizar diferentes operaciones con estos tipos, y su resultado será otro booleano. 



## Operador "and": Devuelve ```True``` si ambas condiciones son verdaderas.
python
> Ejemplo del operador "and":
```python
edad = 25
genero = "Femenino"

if edad > 18 and genero == "Femenino":
    print("Eres una mujer mayor de edad")
```

En este caso, la condición se cumple si la edad es mayor a 18 y el género es femenino.

## Operador "or": Devuelve ```True``` si al menos una de las condiciones es verdadera.
python
> Ejemplo del operador "or":
```python
edad = 16
genero = "Masculino"

if edad <= 18 or genero != "Masculino":
    print("Eres menor de edad o no eres un hombre")
```

En este ejemplo, la condición se cumple si la edad es menor o igual a 18 o si el género no es masculino.

## Operador "not": Devuelve ```True``` si la condición es falsa.
python
> Ejemplo del operador "not"
```python
condicion = False

if not condicion:
    print("La condición es falsa")
```

En este caso, la condición se cumple si la variable "condicion" es falsa.
