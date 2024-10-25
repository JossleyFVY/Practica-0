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

![Imagen de un gato](https://www.google.com/imgres?q=imagen%20de%20gojo%20gato&imgurl=https%3A%2F%2Fih1.redbubble.net%2Fimage.2613406298.5590%2Fbg%2Cf8f8f8-flat%2C750x%2C075%2Cf-pad%2C750x1000%2Cf8f8f8.jpg&imgrefurl=https%3A%2F%2Fwww.redbubble.com%2Fes%2Fi%2Fpegatina%2Fetiqueta-engomada-del-gato-gojo-de-Oouyox%2F85245590.EJUG5&docid=J83tfhvnpg52WM&tbnid=H3f8KlkhXenmlM&vet=12ahUKEwjZ4oe-1amJAxVkSKQEHanTMpgQM3oECBgQAA..i&w=750&h=1000&hcb=2&ved=2ahUKEwjZ4oe-1amJAxVkSKQEHanTMpgQM3oECBgQAA "titulo")

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
