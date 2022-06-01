# Ejercicios de Python del Club de Programacion

Por: Krapp Ramiro

---

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

## Ejercicios

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

### Uso de `print()`

#### Ejercicio 1

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

#### Ejercicio 2

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

#### Ejercicio 3

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

#### Ejercicio 4

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

#### Ejercicio 5

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

#### Ejercicio 6

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

#### Ejercicio 7

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

#### Ejercicio 8

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

### Variables

---

#### Ejercicio 1

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

#### Ejercicio 2

¿Qué diferencias hay entre las variables de texto y las variables numéricas?

<details>
	<summary>Toca para ver la respuesta</summary>

Las variables de texto solamente pueden almacenar texto, mientras que
las variables numérticas solamente pueden almacenar números.

</details>

---

#### Ejercicio 3

¿Qué valores pueden tener las variables lógicas (booleanas)?

<details>
<summary>Toca para ver la respuesta</summary>

Solamente pueden tener dos valores, `True` y `False`

</details>

---

#### Ejercicio 4

¿Cómo averiguo el tipo de una variable?

<details>
<summary>Toca para ver la respuesta</summary>

usando `type(nombre_variable)`

</details>

---

#### Ejercicio 5

¿Cómo le cambio el tipo a una variable?

<details>
<summary>Toca para ver la respuesta</summary>

usando `int()` o `str()`

</details>

---

### `input()`

#### Ejercicio 1

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

#### Ejercicio 2

El siguiente código tiene un error de compilación, cómo arreglaría ese problema?

##### Código

```py
numero_favorito = input("Ingrese su número favorito")
resultado = 7 + numero_favorito
print (f"Su numero favorito más 7 es: {resultado}")
```

##### Error de Compilación

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

### `if`

#### Ejercicio 1

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

#### Ejercicio 4

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

elif zona_impacto == "pecho:
	vida_jugador -= 90

elif zona_impacto == "brazo" or "pierna:
	vida_jugador -= 40

else:
	print(f"Zona de impacto: {zona_impacto}  no reconocida")

print(f"Tenes {vida_jugador} puntos de vida")
```

---

#### Ejercicio 3

Crea un programa que, preguntando la hora, checkee si una persona puede tomar
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

para

#### Ejercicio 4

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

<!--
### While

#### Ejercicio 1

La siguiente fracción de código hace que numero_random sea
igual a un número al azar del 1 al 20. Esto quiere decir que su valor cambia con cada
ejecución del programa.

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
-->