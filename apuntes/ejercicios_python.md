# Ejercicios de Python del Club de Programacion

Por: Krapp Ramiro

---

- [Ejercicios de Python del Club de Programacion](#ejercicios-de-python-del-club-de-programacion)
	- [Nota del autor](#nota-del-autor)
	- [Agradecimientos:](#agradecimientos)
	- [Uso de `print()`](#uso-de-print)
		- [Ejercicio 1](#ejercicio-1)
		- [Ejercicio 2](#ejercicio-2)
		- [Ejercicio 3](#ejercicio-3)
		- [Ejercicio 4](#ejercicio-4)
		- [Ejercicio 5](#ejercicio-5)
		- [Ejercicio 6](#ejercicio-6)
		- [Ejercicio 7](#ejercicio-7)
		- [Ejercicio 8](#ejercicio-8)
	- [Variables](#variables)
		- [Ejercicio 1](#ejercicio-1-1)
		- [Ejercicio 2](#ejercicio-2-1)
		- [Ejercicio 3](#ejercicio-3-1)
		- [Ejercicio 4](#ejercicio-4-1)
		- [Ejercicio 5](#ejercicio-5-1)
	- [`input()`](#input)
		- [Ejercicio 1](#ejercicio-1-2)
		- [Ejercicio 2](#ejercicio-2-2)
			- [Código](#código)
			- [Error de Compilación](#error-de-compilación)
	- [`if`](#if)
		- [Ejercicio 1](#ejercicio-1-3)
		- [Ejercicio 2](#ejercicio-2-3)
		- [Ejercicio 3 - Automatizador de patovica de boliche](#ejercicio-3---automatizador-de-patovica-de-boliche)
		- [Ejercicio 4 - Ladrillos LEGO](#ejercicio-4---ladrillos-lego)
	- [Listas](#listas)
		- [Ejercicio 1 - El creador de equipos de futbol](#ejercicio-1---el-creador-de-equipos-de-futbol)
	- [Diccionarios](#diccionarios)
		- [Ejercicio 1 -  Sistema de compra](#ejercicio-1----sistema-de-compra)
	- [While](#while)
		- [Ejercicio 1 - Adivinador de numero](#ejercicio-1---adivinador-de-numero)
	- [For](#for)
		- [Ejercicio 1 - Checkeador de Juan Carlos](#ejercicio-1---checkeador-de-juan-carlos)
		- [Ejercicio 2 - Checkeador de multiples Juan Carlos](#ejercicio-2---checkeador-de-multiples-juan-carlos)
		- [Ejercicio 3 - Buscador de nombres y repeticiones](#ejercicio-3---buscador-de-nombres-y-repeticiones)
		- [Ejercicio 4](#ejercicio-4-2)
- [Funciones](#funciones)
	- [Ejercicio 1 - Saludador](#ejercicio-1---saludador)
	- [Ejercicio 2 - Impresora de Hora (ja, rima)](#ejercicio-2---impresora-de-hora-ja-rima)
	- [Ejercicio 3 - La calculadora](#ejercicio-3---la-calculadora)

## Nota del autor

Personalmente, **recomiendo encarecidamente con toda mi alma** googlear todo lo posible.
Si no entendés algo del apunte, googlealo, puede ser que en internet
lo encuentres mejor explicado, o encuentres más información.

**No hay nada de malo en googlear, TODO LO CONTRARIO**, internet
es la **MEJOR HERRAMIENTA** que un programador puede tener.

¿Tenés un error en tu código? Googlealo
<br>
¿Necesitás más información sobre un tema en específico? Googlealo

_Ante cualquier problema, google es tu mejor amigo_

---

<!-- Template para las preguntas -->

<!--
¿Qué resultado va a tener el siguiente código?

```py

```

1.
2.
3.

<details>
  <summary>Toca para ver la respuesta</summary>

1
</details>
-->

## Agradecimientos:

Gracias a Valentin Albero y a Francisco Longobardi por ayudarme en la corrección de errores de este documento

## Uso de `print()`

### Ejercicio 1

¿Qué resultado va a tener el siguiente código?

```py
print("Hola mundo!")
```

1. No va a hacer nada
2. Va a imprimir `Hola mundo!` en la terminal
3. Va a tirar un error

<details> 
  <summary>Toca para ver la respuesta</summary>

2

</details>

---

### Ejercicio 2

¿Qué resultado va a tener el siguiente código?

```py
print("Hola mundo!)
```

1. No va a hacer nada
2. Va a imprimir `Hola mundo!` en la terminal
3. Va a tirar un error

<details>
  <summary>Toca para ver la respuesta</summary>

3, falta un `"` antes del `)` para cerrar el texto

</details>

---

### Ejercicio 3

¿Qué resultado va a tener el siguiente código?

```py
print(Hola mundo!)
```

1. No va a hacer nada
2. Va a imprimir `Hola mundo!` en la terminal
3. Va a tirar un error

<details>
  <summary>Toca para ver la respuesta</summary>

3, faltan las `" "` para que python entienda que queremos imprimir un texto,
porque en este caso python cree que queremos imprimir una variable llamada Hola

</details>

---

### Ejercicio 4

¿Qué resultado va a tener el siguiente código?

```py
nombre = "Pepe Argento"
print(nombre)
```

1. Va a imprimir nombre
2. Va a imprimir Pepe Argento
3. Va a tirar un error

<details>
  <summary>Toca para ver la respuesta</summary>

2

</details>

---

### Ejercicio 5

¿Qué resultado va a tener el siguiente código?

```py
nombre = "Pepe Argento"
print("nombre")
```

1. Va a imprimir nombre
2. Va a imprimir Pepe Argento
3. Va a tirar un error

<details>
  <summary>Toca para ver la respuesta</summary>

1

</details>

---

### Ejercicio 6

¿Qué resultado va a tener el siguiente código?

```py
nombre = "Pepe Argento"
print(f"Mi amigo se llama {nombre}")
```

1. Imprime Mi amigo se llama {nombre}
2. Tira un error
3. Imprime Mi amigo se llama Pepe Argento

<details>
  <summary>Toca para ver la respuesta</summary>

3

</details>

---

### Ejercicio 7

¿Qué resultado va a tener el siguiente código?

```py
nombre = "Pepe Argento"
print("Mi amigo se llama {nombre}")
```

1. Imprime Mi amigo se llama {nombre}
2. Tira un error
3. Imprime Mi amigo se llama Pepe Argento

<details>
  <summary>Toca para ver la respuesta</summary>

1, va a entender `{nombre}` como si fuera parte del string, falta la `f`

</details>

---

### Ejercicio 8

¿Qué resultado va a tener el siguiente código?

```py
edad = 18
print(f"Tengo {edad} años")
```

1. Imprime `Tengo {edad} años`
2. Imprime `Tengo 18 años`
3. Tira un error

<details>
  <summary>Toca para ver la respuesta</summary>

2

</details>

## Variables

---

### Ejercicio 1

¿Cuál es la **sintaxis** de la declaración de una variable?

1. Asi:

```py
valor_variable = nombre_variable
```

2. Asi:

```py
tipo_variable nombre_variable = valor_variable
```

3. Asi:

```py
nombre_variable = valor_variable
```

<details>
  <summary>Toca para ver la respuesta</summary>

3

</details>

---

### Ejercicio 2

¿Qué diferencias hay entre las variables de texto y las variables numéricas?

<details>
  <summary>Toca para ver la respuesta</summary>

Las variables de texto solamente pueden almacenar texto, mientras que
las variables numérticas solamente pueden almacenar números.

</details>

---

### Ejercicio 3

¿Qué valores pueden tener las variables lógicas (booleanas)?

<details>
<summary>Toca para ver la respuesta</summary>

Solamente pueden tener dos valores, `True` y `False`

</details>

---

### Ejercicio 4

¿Cómo averiguo el tipo de una variable?

<details>
<summary>Toca para ver la respuesta</summary>

usando `type(nombre_variable)`

</details>

---

### Ejercicio 5

¿Cómo le cambio el tipo a una variable?

<details>
<summary>Toca para ver la respuesta</summary>

usando `int()` o `str()`

</details>

---

## `input()`

### Ejercicio 1

¿Qué resultado va a tener el siguiente código?

```py
nombre_usuario = input("Hola, ingresa tu nombre: ")
```

1. Va a tirar un error de compilación
2. Va a pedirle al usuario que ingrese su nombre, y lo va a guardar como un int
3. Va a pedirle al usuario que ingrese su nombre, y lo va a guardar como un string

<details>
  <summary>Toca para ver la respuesta</summary>

3

</details>

---

### Ejercicio 2

El siguiente código tiene un error de compilación, cómo arreglaría ese problema?

#### Código

```py
numero_favorito = input("Ingrese su número favorito")
resultado = 7 + numero_favorito
print (f"Su numero favorito más 7 es: {resultado}")
```

#### Error de Compilación

```py
Traceback (most recent call last):
  File "/home/krapp/test.py", line 2, in <module>
    resultado = 7 + numero_favorito
TypeError: unsupported operand type(s) for +: 'int' and 'str'
```

<details>
  <summary>Toca para ver la respuesta</summary>

Habría que hacer `int(input())`

</details>

---

## `if`

### Ejercicio 1

1. ¿Qué pasa cuando `flechazo_cabeza` es `True`?

2. ¿Qué pasaría si `flechazo_cabeza` fuera `False`?

```py
flechazo_cabeza = True
vida_jugador = 100

if flechazo_cabeza == True:
  vida_jugador = 0
  print("Te pegaron un flechazo en la cabeza! Te moriste :( ")

else:
  print("La flecha no te pego, zafaste...")
```

<details>
  <summary>Toca para ver la respuesta</summary>

Cuando `flechazo_cabeza` es `True`, la vida del jugador se setea en 0,
y se imprime que perdiste.

Si `flechazo_cabeza` fuera `False`, se imprimiría en pantalla el "la flecha no te pego"

</details>

---

### Ejercicio 2

1. ¿Qué pasa cuando `zona_impacto` es `"cabeza"`?

2. ¿Qué pasa cuando `zona_impacto` es `"pecho"`?

3. ¿Qué pasa cuando `zona_impacto` es `"brazo"`?

4. ¿Hay alguna diferencia cuando es `"brazo"`, que cuando es `"pierna"`?

- A gusto, modifica el programa y agrega una zona del cuerpo

```py
print("Te pegó una flecha! Decime donde te pegó, y te voy a decir cuánta vida te queda")
zona_impacto = input("La zona de impacto fue: ")
vida_jugador = 100

if zona_impacto == "cabeza":
  # No usamos la ñ ni tildes (caracteres especiales en general) en la programacion,
  # porque causan errores
  dano = 100
  vida_jugador -= dano # Le resto 100 al valor actual de vida_jugador

elif zona_impacto == "pecho":
  vida_jugador -= 90

elif zona_impacto == "brazo" or zona_impacto == "pierna":
  vida_jugador -= 40

else:
  print(f"Zona de impacto: {zona_impacto}  no reconocida")

print(f"Tenes {vida_jugador} puntos de vida")
```

---

### Ejercicio 3 - Automatizador de patovica de boliche

Crea un programa que, preguntando la edad, checkee si una persona puede tomar
bebidas alcohólicas o no

<details>
  <summary>Toca para ver la respuesta</summary>

```py
edad=int(input("Ingresa tu edad: "))
if edad >=18:
   print("Podes tomar")
else:
   print("No podes tomar")
```

</details>

---

### Ejercicio 4 - Ladrillos LEGO

Los famosos ladrillos **LEGO** tienen un rango de edades permitidas, que van,
en la mayoría de los casos, desde los 7 años hasta los 99 años.

Hacer un programa que le pregunte la edad al usuario, y que le avise de las siguientes
dos cosas:

- Si el usuario esta en el rango de edad permitido para jugar con legos
- Si el usuario es muy joven para jugar con legos
- Si el usuario es muy viejo para jugar con legos
- Si la edad ingresada es invalida (por ejemplo, si el usuario puso que tenía -1 años)

_(Si, hice un ejercicio sobre los ladrillos lego, estaba muy aburrido)_

<details>
  <summary>Toca para ver la respuesta</summary>

```py
edad = int(input("Ingrese su edad: "))
edad_minima = 7
edad_maxima = 99
if edad >= edad_minima and edad <= edad_maxima:
    # Hay otra forma de hacer ese if, que es de esta forma:
    # if edad_minima < edad < edad_minima:
    print("Esta en el rango de edad permitido")
elif edad <= edad_minima:
    print("No tiene la edad suficiente")
elif edad >= edad_maxima:
    print("Es muy viejo para jugar con legos :( ")
else:
    print("Ingresó un número inválido")
```

</details>

---

## Listas

### Ejercicio 1 - El creador de equipos de futbol

Crear un codigo que, teniendo una lista de jugadores de futbol, mezcle las personas que estan adentro de la lista y haga dos equipos de futbol.
Además, que se fije si los equipos estan desbalanceados (o sea, si un equipo tiene más jugadores que otro)

Protip: usar el módulo `random`

<details>
  <summary>Toca para ver la respuesta</summary>

```py
import random
lista_personas = ["Juan", "Pepe", "Augusto", "Bruno",
                  "Geronimo", "Valentin", "Elias", "Pedro", "Alan"]

random.shuffle(lista_personas)  # Mezclo la lista de personas

# Consigo el tamaño de la lista (o sea, la cantidad de personas), luego
# lo divido por dos (para conseguir la mitad), y luego
# para evitar numeros con coma, lo paso a un int()
tamano_lista = int(len(lista_personas)/2)

# Hago slicing para conseguir la primera mitad de las personas, y va a ser el team 1
team_1 = lista_personas[:tamano_lista]
# Hago slicing para conseguir la segunda mitad de las personas, y va a ser el team 2
team_2 = lista_personas[tamano_lista:]

# len() me tira el tamaño de una lista
print(f"Equipo 1:\n{team_1} \nTamaño del equipo: {len(team_1)}\n")

print(f"Equipo 2:\n{team_2} \nTamaño del equipo: {len(team_2)}")

if len(team_1) > len(team_2):
    print("Los equipos estan desbalanceados, team 1 tiene más jugadores")
elif len(team_2) > len(team_1):
    print("Los equipos estan desbalanceados, team 2 tiene más jugadores")
else:
    print("Los equipos estan balanceados")
```

</details>

## Diccionarios

### Ejercicio 1 -  Sistema de compra

Crear un sistema compra en el que, usando un diccionario, se pueda seleccionar
un item a comprar.

El diccionario se debe ver de la siguiente forma:

```py
objetos = {
    "remera": 300,
    "pantalones": 500,
    "zapatillas": 3500
}
```

<details>
  <summary>Toca para ver la respuesta</summary>

```py
objetos = {
    "remera": 300,
    "pantalones": 500,
    "zapatillas": 3500
}
lista_objetos_disponibles = list(objetos.keys())

print(f"Nuestros objetos disponibles son: {lista_objetos_disponibles}")
pedido_compra = input("Ingrese el item a comprar: ")

if pedido_compra in objetos:
    print(f"serán ${objetos[pedido_compra]} pesos")
else:
    print("No existe ese objeto en nuestro sistema")

```

</details>

---

## While

### Ejercicio 1 - Adivinador de numero

La siguiente fracción de código hace que numero_random sea igual a un número al azar del 1 al 20.
Esto quiere decir que su valor cambia con cada ejecución del programa.

```py
import random # Se importa el modulo random -- Esto es algo que todavia no vimos, jejeje
numero_random = random.randrange(1, 21)
```

Usando `numero_random`, hacer un programa que le pida al usuario que adivine el valor
de `numero_random`.

El programa va a tener los siguientes requerimientos:

- Si el usuario ingresa un numero mayor a `numero_random`, que le avise.
- Si el usuario ingresa un numero menor a `numero_random`, que le avise.
- Si el usuario ingresa un numero igual a `numero_random`, que le avise que ganó.
- Al finalizar la ejecución del programa, el mismo deberá avisar cuántos intentos
  le tomo al usuario para adivinar el número

<details>
  <summary>Toca para ver la respuesta</summary>

```py
import random
numero_random = random.randrange(1, 21)
run = True
cantidad_intentos = 0

while run:
  user_input = int(input('Adivina el numero: '))
  if user_input < numero_random:
    print("Muy bajo!")
  elif user_input > numero_random:
    print("Muy alto!")
  elif user_input == numero_random:
    print('Adivinaste!')
    run = False
  cantidad_intentos += 1

print(f"Te tomo {cantidad_intentos} intentos!")
```

</details>

---

## For

### Ejercicio 1 - Checkeador de Juan Carlos

Hacer un código que, usando un for, checkee si en una lista de nombres de animales
hay un perro llamado Juan Carlos

<details>
  <summary>Toca para ver la respuesta</summary>

```py
lista_perros = ["Rufus", "Rocco", "Juan Carlos", "Manchitas", "Juan Carlos"]

for perro in lista_perros:
    if perro == "Juan Carlos":
        print("Hay un perro llamado Juan Carlos!")
```

</details>

---

### Ejercicio 2 - Checkeador de multiples Juan Carlos

Modificar el código anterior, para que checkee si en una lista de nombres de animales
hay **tres o más** perros llamados Juan Carlos

<details>
  <summary>Toca para ver la respuesta</summary>

```py
lista_perros = ["Rufus", "Rocco", "Juan Carlos", "Manchitas", "Juan Carlos"]
cantidad_repeticiones = 0

for perro in lista_perros:
    if perro == "Juan Carlos":
        cantidad_repeticiones += 1

if cantidad_repeticiones == 0:
    print("No se encontraron perros llamados Juan Carlos")
else:
    print(f"Se encontraron {cantidad_repeticiones} perros llamados Juan Carlos")
```

</details>

---

### Ejercicio 3 - Buscador de nombres y repeticiones

Modificar el código anterior, para que permita buscar cualquier nombre y cualquier
cantidad de repeticiones del mismo

<details>
  <summary>Toca para ver la respuesta</summary>

```py
lista_perros = ["Rufus", "Rocco", "Juan Carlos", "Manchitas", "Juan Carlos"]
cantidad_repeticiones = 0
nombre_buscado = input("Ingrese el nombre del perro a buscar")

for perro in lista_perros:
    if perro == nombre_buscado:
        cantidad_repeticiones += 1

if cantidad_repeticiones == 0:
    print(f"No se encontraron perros llamados {nombre_buscado}")
else:
    print(f"Se encontraron {cantidad_repeticiones} perros llamados {nombre_buscado}")
```

</details>

---

### Ejercicio 4

Escribir un programa para mostrar los numeros de una lista que satisfagan los siguientes requisitos:

- El numero debe ser divisible por cinco
- Si el número es mayor a 150, skipear a la siguiente iteración
- Si el número es mayor a 500, salir completamente del for

Dado:

`numeros = [12, 75, 150, 180, 145, 525, 50]`

Printeo en pantalla esperado:

```
75
150
145
```

<details>
  <summary>Toca para ver la respuesta</summary>

```py
numeros = [12, 75, 150, 180, 145, 525, 50]
# Itero por cada elemento en la lista
for item in numeros:
    if item > 500:
        break # Con break salgo del for
    elif item > 150:
        continue # Continue skipeea la iteracion actual y pasa al siguiente item
    # Checkeo si el numero es divisible por 5
    elif item % 5 == 0:
        print(item)
```

</details>

# Funciones

## Ejercicio 1 - Saludador

Escribir una funcion que imprima un nombre pasado por parametro

<details>
  <summary>Toca para ver la respuesta</summary>

```py
def saludar(nombre):
	print(f"Hola {nombre}, todo bien?")

saludar("Muller")
```

</details>

---

## Ejercicio 2 - Impresora de Hora (ja, rima)

Escribir una funcion que imprima la hora en un formato en especifico. (Para esta, vas a tener que googlear. Suerte.)

<details>
  <summary>Toca para ver la respuesta</summary>

```py
from datetime import datetime

def imprimir_hora_actual(formato):
	tiempo = datetime.now() # Consigue la hora actual

	tiempo_legible = tiempo.strftime(formato) # Pasa la hora a un formato un poco más legible
	print("fHora actual: {tiempo_legible}")
```

</details>

---

## Ejercicio 3 - La calculadora

Escribir varias funciones que te permitan hacer una calculadora. Estas funciones deberían ser

- suma
- resta
- multiplicacion
- division
- porcentaje
- raiz cuadrada
- potencia

Protip: Te conviene usar el modulo `math` para las raices cuadradas y las potencias

<details>
  <summary>Toca para ver la respuesta</summary>

```py
import math  # Usamos las funciones del modulo math, que nos van a simplificar la vida


def sumar(num1, num2):
    return num1 + num2


def restar(num1, num2):
    return num1 - num2


def multiplicar(num1, num2):
    return num1 * num2


def dividir(dividendo, divisor):
    if divisor == 0:
        print("NO! No se puede dividir por 0!")
        return
    # Aca no puse un else, porque ya el return te sacaria de la funcion si divisor fuera 0, entonces bueno, no hace falta
    return dividendo / divisor


def calcular_porcentaje(num1, num2):
    return (num1 / num2) * 100


def calcular_raiz_cuadrada(numero):
    if numero < 0:
        # Te vas a preguntar por que este print usa '''texto''' y no "texto"
        # Bueno, esto es porque existen strings que pueden ocupar varias lineas,
        # se llaman multiline strings, aca un link que lo explica:
        # https://www.w3schools.com/python/gloss_python_multi_line_strings.asp
        print(''' No existen las raices cuadradas de los numeros menores a 0!
        (mentira, pero son numeros imaginarios, pero ese es
        otro tema de matematicas que se re va de enfoque.''')
    # Este link explica bien que hace math.sqrt https://www.geeksforgeeks.org/python-math-function-sqrt/
    return math.sqrt(numero)


def calcular_potencia(base, exponente):
    # Este link explica ben que hace math.pow https://www.geeksforgeeks.org/pow-in-python/
    return math.pow(base, exponente)
```

</details>
