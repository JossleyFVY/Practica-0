# Manual de Markdown
## Sintaxis básica
Para crear un nuevo párrafo en Markdown basta con que dejes una línea en blanco entre una o más líneas de texto  
tal y como ves en este ejemplo:

Esto es un párrafo

y este es otro

No deberías de añadir sangrías 

### Encabezados
Para realizar encabezados es tan sencillo como añadir # al principio de la línea
el nivel dependerá del número de # que haya, de menor a mayor siendo el menor
el de mayor nivel : #(primer encabezado que podria ser el título) ##(Podría ser encabezados normales)
# Título 
este sería el equivalente en html a la etiqueta h1
## Título
este sería en h2
### Título
este sería en h3

Y así sucesivamente hasta 6.

### Saltos de Línea
Para agregar un salto de línea con markdown basta con que dejes dos o más espacios en blanco al final de la línea y luego pulses INTRO:
En HTML es la etiqueta <br>. A continuación puedes ver el código Markdown que crea una nueva línea

Como por ejemplo esta.

### Formato de texto

#### Negrita
Para agregar texto resaltado en negrita tendrás que usar dos asteriscos ** o dos guiones bajos __ al principio y al final de lo oración que quieres resaltar.
En caso de que quieras resaltar un texto que está en medio de una palabra, tedrás que agregar dos asteriscos ** o dos guiones bajos __, sin espacios, antes y después de las letras deseadas:

Ejemplos:

Texto en **negrita**  en html sería con la etiqueta <b>negrita</b>

texto en neg**gri**ta en html sería con ne<b>gri</b>ta

#### Cursiva
Para agregar texto en cursiva debes usar un solo asterisco * o un solo guión bajo _ tanto al inicio como al final de lo oración que quieres marcar como cursiva.
Si quieres poner en cursiva ciertas letras que estén en la mitad de una palabra, deberás agregar un asterisco * o un guión bajo _, sin espacios, al comienzo y al final de las letras deseadas:

Ejemplos:
Sería igual que en negrita...
texto en *cursiva*  en html sería con la etiqueta <em>
texto en *cur*siva igual

#### Listas
Para agregar listas ordenadas en Markdown debes agregar un número seguido de un punto, un espacio y el elemento de la lista. La lista no debe estar ordenada numéricamente, pero debe comenzar por el número 1:
Ejemplos:

1. Primer elemento
2. Segundo elemento
3. Tercer elemento
y así sucesivamente... en el caso de listas ordenadas.
En el caso de listas no ordenadas solo sería con *

Ejemplos:
* Primer elemento.
* Segundo elemento.
* Tercer elemento.

#### Texto Tachado
Para agregar un texto tachado en Markdown tendrás que usar dos guiones ondulados ~~ tanto antes como después del texto que quires tachar. Esto agregará una línea horizontal a través del texto tal y como ves en este ejemplo. El texto tachado suele usarse para indicar que ciertas palabras o elementos son un error:
Ejemplo:

~~ESPAÑA~~ 

En html sería con la etiqueta strike

#### Bloques de código
Los bloques de código que se inician y se cierran con tres comillas invertidas son aceptados por la mayor parte de los procesadores de texto y herramientas Markdown. Su funcionalidad se limita a crear un bloque de código sin formato ni resaltado de sintaxis.
Ejemplo

```
const value = 3;
let result = value * 4;
```
#### Resaltado de sintaxis
Muchos procesadores Markdown soportan los bloques de código con resaltado de sintaxis para una gran cantidad de lenguajes de programación. Esto coloreará y agregará formato al código según el lenguaje de programación con el que se corresponda.

Para ello tendremos que indicar el lenguaje de programación tras las tres comillas de apertura del bloque de código.

A continuación agregamos un bloque de código JavaScript:
```javascript
const value = 3;
let result = value * 4;
```
#### Listas de tareas
Las listas de tareas se componen de checkboxes que se mostrarán al lado del contenido.

Espacio en blanco: Agrega un espacio en blanco para indicar que la tarea no ha sido completada.
Equis x: Agrega una x para indicar que la tarea ha sido completada.
A continuación de los corchetes tendrás que dejar un espacio en blanco, agregando seguidamente la descripción de la tarea:

- [x] Primera tarea
- [ ] Segunda tarea
- [ ] Tercera tarea

### Enlaces
Para crear un enlace en Markdown debes situar entre corchetes el texto que quieres enlazar, también conocido como anchor. Seguidamente, debes usar paréntesis para definir la URL a la que debe enlazar en texto del enlace:

Es importante que no existan espacios entre el corchete de cierre ] del texto del enlace y el paréntesis de apertura del enlace.
Ejemplo:
[Enlace](https://www.google.com/webhp?authuser=1) con esto al darle enlace nos llevaría al buscador de google
<https://www.google.com/webhp?authuser=1> así nos saldría el enlace entero
#### Título de enlaces
También puedes agregar un título al enlace, que aparecerá cuando pases el cursor por encima del mismo. Para agregar un título a un enlace debes añadirlo entre comillas dobles, justo después del enlace:

Ejemplo:
Me gusta el editor [Editor Markdown](https://editormarkdown.com "Mejor editor Markdown")
#### Formato del enlace
También puedes agregar formato al texto del enlace, pudiendo ponerlo en negrita, cursiva o negrita y cursiva. Para ello basta con que uses asteriscos * o guiones bajos _, según corresponda, alrededor del enlace:

Ejemplo:
**[Negrita](https://neoguias.com)** etc
#### Imagenes
Para agregar imágenes con Markdown debes agregar un signo de exclamación ! seguido del texto alternativo o alt de la imagen entre corchetes y de la URL de la imagen entre paréntesis:

![Imagen de una Pizza](https://github.com/JossleyFVY/Practica-0/blob/main/Archivos/descarga.jpg)

Para añadir un título solo haría falta ponerlo entre comillas.

![Imagen de un gato](data:image/jpeg;base64,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 "titulo")

#### Citas
Para agregar citas en Markdown debes agregar el signo mayor > justo delante de una línea o de un párrafo:

Ejemplo:
>Te recordaremos Antonio

para que sea más largo o para que vaya una más a la derecha añadiremos >

Ejemplo:
>Te recordaremos Antonio
>
>>Nunca jugaste bien

#### Tablas
Para agregar tablas Markdown debes definir las cabeceras de columna mediante al menos tres guiones --- que se situarán por debajo del texto de la cabecera. Para separar las diferentes cabeceras tendrás que usar un símbolo de tubería |:
Ejemplos:
| Cabecera 1 | Cabecera 2 |
| ---------- | ---------- |
| Elem 1, 1  | Elem 1, 2  |
| Elem 1, 2  | Elem 2, 2  |
