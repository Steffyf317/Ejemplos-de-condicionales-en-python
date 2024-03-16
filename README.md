# Ejemplos de condicionales en python
## Determinar si un número entero corresponde al código ASCII de alguna vocal minúscula
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
  
