# Entorno virtual en python (venv)
Nos sirve para instalar algunas herramientas incluyendo tambien la version de python que se va a trabajar en este proyecto en particular. Si tuvieramos otras versiones de python instaladas podriamos seleccionar cual es la version de python que deseamos trabajar en este proyecto en particular.

# Python
- Python es un lenguaje interpetado, osea de tal forma en que escribamos nuestro codigo se va interpetando.
- Con # se puede agregar comentarios en python
- Variables: Para la declaracion de asignacion de una variable se tiene 3 elementos principales: El identificador, el operador de asignacion y el dato o valor
- Un literal es el valor que se le puede asignar a las variables. Por ejemplo z = 10 (el valor 10 es el literal)
- Para conocer la direccion de memoria de los literales tenemos la funcion id:   id(x)   , para imprimir esto es necesario tambien usar la funcion print:   print(id(x))
- La memoria RAM que es donde se almacena las variables es una memoria volatil por lo que cada vez que volvamos a ejecutar la direccion de memoria de las variables cambia
- Recordar que python es sensible a mayusculas y minusculas

# SECCION 3: TIPOS DE DATOS EN PYTHON
## 12. TIPOS DE DATOS EN PYTHON
- Numeric
    - Integer
    - Complex Number
    - Float
- Dictionary
- Boolean
- Set
- Sequence Type
    - String
    - List
    - Tuple

Con la funcion **type** podemos conocer el tipo de dato de la variable. Para imprimirlo hacemos: print(type(x))

Tambien se le puede agregar una pista o indicacion (hint) a la variable que se va a usar indicando de que tipo se trata, pero esta no define como el tipo de variable final: Ejemplo:

x: str = "Hola Mundo"   (Esto le da una pista x sera de tipo str). Resultado: <class 'str'>

x: str = 10   (a pesar de que dijimos str el resultado sera lo siguiente). Resultado: <class 'int'> 


Recordar que las variables en python son dinamicas por lo que en cualquier momento pueden apuntar a cualquier tipo de dato que deseemos.

Para los tipos booleanos es necesario que estas se encuentren en mayusculas: False, True

Todos los tipos de datos en python son almacenados por clases

```python
//Tipos de datos
x = 10
print(type(x))
m = 12.6
print(type(m))
y = "Hola Mundo"
print(type(y))
z = False
print(type(z))

/*
Resultado:
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
*/
```


