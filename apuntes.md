# Apuntes del Club de Programacion

Por: Krapp Ramiro

## El sistema de archivos de Linux

La carpeta home `~` es la carpeta del usuario, donde el usuario tiene todos sus
archivos personales

## Uso de Bash (La terminal)

La consola, la linea de comandos, la terminal, son todos nombres que se usan para referirse
a la <u>shell</u> por defecto de Linux, **Bash**.

Qué es la terminal? La terminal es lo que usamos los programadores para poder **comunicarnos
directamente con la computadora**, usando comandos específicos, que cumplen una
tarea en concreto.

### Comandos de bash

Hay muchos comandos? Si, hay un montonazo, pero uno **solamente usa los que necesita**,
y son más bien pocos, los más importantes son:

#### `ls`

Muestra en la terminal los contenidos del directorio actual.

Qué es un directorio? Un directorio es lo que se conoce normalmente como una carpeta.
O sea, `ls` muestras los contenidos de la carpeta actual en la que estas localizado.

Cómo se usa? Simplemente hay que escribir `ls`, y tocar enter para ejecutar el comando

Un resultado tipico de `ls` cuando uno esta en `~` (home) puede ser:

```
Descargas
Documentos
Imagenes
Musica
foto_gato.jpg
lista_compras.txt
ejercicios_matematicas.pdf
```

**Pro-tip:**
Si se desean ver los archivos ocultos, los cuales empiezan con un punto `.` , se debe
usar `ls -a`

---

#### `cd`

Cambia el directorio actual al que uno especifique.

Para dar un ejemplo, imaginemos que estoy en la carpeta `~` (home) ,
y ls me dió el siguiente resultado:

```
Descargas
Documentos
Imagenes
Musica
foto_gato.jpg
lista_compras.txt
ejercicios_matematicas.pdf
```

Si yo quisiera cambiar a la carpeta (o directorio) Documentos, lo unico que tendria que hacer es

```bash
cd Documentos
```

y ya estaría adentro de la carpeta (o directorio) Documentos.

Tambien, si adentro de la carpeta (o directorio) Documentos hubiera otra carpeta,
por ejemplo "Recibos_de_pago/", yo podría hacer

```bash
cd Documentos/Recibos_de_pago/
```

Y me mandaría directamente adentro de Recibos_de_pago

Otra cosa, si se usa simplemente `cd` **sin indicarle ninguna carpeta** (lo que tecnicamente
se llama "no pasarle argumentos"), `cd` te manda a la carpeta `~` (home)

---

#### `sudo`

Permite ejecutar un comando como un usuario administrador,
conocido en linux como usuario **root**.
Sirve cuando un comando tiene que modificar archivos del sistema y/o instalar aplicaciones.

Para usuarlo, lo único que hay que hacer es escribir

```bash
sudo comando_a_ejecutar_aqui
```

## Python

### print()
