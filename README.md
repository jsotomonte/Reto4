# Reto4
## Determinar si un numero entero pertenece al codigo ASCII de una vocal minuscula
```
 x : int
if chr(x) == "a" or chr(x) == "e" or chr(x) == "i" or chr(x) == "o" or chr(x) == "u":
    print("el numero " + str(x) + " corresponde al codigo ASCII de una vocal minuscula")
 else:
    print("el numero " + str(x) + " no corresponde al codigo ASCII de una vocal minuscula"  
```
## determinar si la primera letra corresponde a un numero par en ASCII 
```
cadena : str # ingresar cadena de longitud 1
if ord(cadena[0]) % 2 == 0: 
print("el código ASCII de la primera letra corresponde a un número par") 
else: print("el código ASCII de la primera letra no corresponde a un número par") 
if ord(cadena[0]) % 2 == 0: 
 print("el código ASCII de la primera letra corresponde a un número par") 
else: 
print("el código ASCII de la primera letra no corresponde a un número par")
```

## Determinar si el carácfer es un dígito o no 
```
x : int or str
# ingresar un carácter 
x = input("ingrese un carácter: ") caracter_x = ord(x) 
if caracter_x >= 48 and caracter_x <= 57:
 print(str(x) + " sí es un dígito") 
else: print(str(x) + " no es un dígito")
```

## Indicar si el número es negativo, positivo o cero 
```
x : float
if x < 0: print("el número x es negativo")
elif x > 0:
 print("el número x es positivo") 
else: 
 print("el número x es el neutro para la suma")
```
## Determinar si un punto de R2 pertenece o no al círculo center_
```
x : float 
#ingrese punto x del centro center_
y : float 
#ingrese punto y del centro radio: float 
#ingrese el radio 
a : float 
#ingrese una cordenada a del punto R2
b : float 
#ingrese una cordenada b del punto R2 c = (center_x - a)**2 + (center_y - b)**2
r = radio**2
if c == r:
 print("el punto " + str(a) + ',' + str(b) + " pertenece al interior círculo")
 else:
 print("el punto " + str(a) + ',' + str(b) + " no pertenece al interior círculo")
```
## Determinar si con tres longitudes positivas se puede construir un triángulo 
```
a : float
#ingrese una longitud positiva 
b : float 
#ingrese una longitud positiva
c : float 
#ingrese una longitud positiva 
if (a + b) > c and (a + c) > b and (c + b) > a: 
print("sí se puede construir un triángulo") 
else: 
print("no se puede construir un triángulo")
```
