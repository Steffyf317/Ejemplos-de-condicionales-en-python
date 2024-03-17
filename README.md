# Reto 04: condicionales en python
[Notebook de python](/reto4.ipynb)
## Determinar si un número entero corresponde al código ASCII de alguna vocal minúscula
### En forma preestablecida: 
```python 
numero : int #Declaracion de variable
numero = 100  #Inicializar la variable
if numero == ord('a'):  #condicionales estableciendo si se cumple algun caso de vocal minuscula
  print('el número corresponde al código ASCII de la vocal a')
elif numero == ord('e'):
  print('el número corresponde al código ASCII de la vocal e')
elif numero == ord('i'):
  print('el número corresponde al código ASCII de la vocal i')
elif numero == ord('o'):
  print('el número corresponde al código ASCII de la vocal o')
elif numero == ord('u'):
  print('el número corresponde al código ASCII de la vocal u')
else:
  print('el número no corresponde al código ASCII de alguna vocal minúscula')
  ```
### En forma de programa:
```python
numero : int #Declaracion de variable
numero = int(input('Ingrese un numero entero ')) #Inicializar la variable
if numero == ord('a'):  #condicionales estableciendo si se cumple algun caso de vocal minuscula
  print('el número corresponde al código ASCII de la vocal a')
elif numero == ord('e'):
  print('el número corresponde al código ASCII de la vocal e')
elif numero == ord('i'):
  print('el número corresponde al código ASCII de la vocal i')
elif numero == ord('o'):
  print('el número corresponde al código ASCII de la vocal o')
elif numero == ord('u'):
  print('el número corresponde al código ASCII de la vocal u')
else:
  print('el número no corresponde al código ASCII de alguna vocal minúscula')
```

## Determinar si el código ASCII de una cadena de longitud 1 es par o no
### En forma de programa:
```python
cadena : str #Declaracion de variable
cadena = input('Ingrese una letra ') #pedir al usuario caracter por consola
if ord(cadena)%2 == 0 : #establecer los condicionales de si el ASCII es par o no
  print("El código ASCII de la letra es " +str(ord(cadena))+ " y es par")
else:
  print("El código ASCII de la letra es " +str(ord(cadena))+ " y es impar")
```
### Con la cadena preestablecida:
```python
cadena : str #Declaracion de variable
cadena = 'E' #Inicializar variable
if ord(cadena)%2 == 0 : #establecer los condicionales de si el ASCII es par o no
  print("El código ASCII de la letra es " +str(ord(cadena))+ " y es par")
else:
  print("El código ASCII de la letra es " +str(ord(cadena))+ " y es impar")
```

## Programa en Python para determinar si el carácter es un dígito o no
```python
caracter: str #Declarar variable
caracter  = input('Ingrese un carácter ') #Pedir a usuario que ingrese un caracter
if ord(caracter) == 48 or ord(caracter) == 49 or ord(caracter)== 50 or ord(caracter)== 51 or ord(caracter)==52 or ord(caracter)== 53 or ord(caracter)== 54 or ord(caracter)== 55 or ord(caracter)== 56 or ord(caracter)== 57 :
  print('El carácter es un dígito')  #Se establecen los condicionales a partir del codigo ASCII de los 9 dígitos
else:
  print('El carácter no es un dígito')
```

## Programa que permite determinar si un número real es positivo, negativo o cero
```python
num: float #declarar variable
num = float(input('Ingrese un número ')) #pedir al usuario un numero real
if num > 0: #Condicionales de acuerdo donde se encuentre el numero en la recta numerica
  print("El número " +str(num)+ " es positivo")
else:
  if num < 0:
    print("El número " +str(num)+ " es negativo")
  if num == 0:
    print("El número " +str(num)+ " es el neutro para la suma")
```
## Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo
### En forma preestablecida:
```python
centroX : float = 2.1 #Se declaran e inician variables
centroY : float = 1
radio: float = 5
x: float = -8 #coordenadas del punto en R2
y: float = 1

if (x-centroX)**2 + (y-centroY)**2  < (radio**2): #el condicional se hace con la formula de la circunferencia
  print('El punto pertenece al interior del círculo')
else:
  print('El punto no pertenece al interior del círculo')
```
### En forma de programa:
```python
centroX : float = float(input('Ingrese la coordenada en x del centro del círculo ')) #se declaran variables y se pide ingresar los datos del círculo
centroY : float = float(input('Ingrese la coordenada en y del centro del círculo '))
radio: float = float(input('Ingrese el radio del círculo '))
x: float = float(input('Ingrese la coordenada en x del punto '))
y: float = float(input('Ingrese la coordenada en y del punto '))

if (x-centroX)**2 + (y-centroY)**2  < (radio**2): #el condicional se hace con la formula de la circunferencia
  print('El punto pertenece al interior del círculo')
else:
  print('El punto no pertenece al interior del círculo')
```
## Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo
### En forma preestablecida:
```python
a: int = 2 #se declaran e inician variables
b: int = 2
c: int = 20
if a < (b+c) and b < (a+c) and c < (a+b): #desigualdad triangular
  print('Sí se puede construir un triángulo con las longitudes dadas')
else:
  print('No se puede construir un triángulo con las longitudes dadas')
```
### En forma de programa:
```python
a: int = int(input('Ingrese la primera longitud '))
b: int = int(input('Ingrese la segunda longitud '))
c: int = int(input('Ingrese la tercera longitud '))
if a < (b+c) and b < (a+c) and c < (a+b): #desigualdad triangular
  print('Sí se puede construir un triángulo con las longitudes dadas')
else:
  print('No se puede construir un triángulo con las longitudes dadas')
```
[Notebook](/reto4.ipynb) 
