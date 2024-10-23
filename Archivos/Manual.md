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
texto en neg**gri**ta en html sería con ne<b>gri</b>
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
Para agregar imágenes con Markdown debes agregar un signo de exclamación ! seguido del texto alternativo o alt de la imagen entre corchetes y de la URL de la imagen entre paréntesis:
![Imagen de una nube](C:\Users\jfvy1\Desktop\CMD)
Para añadir un título solo haría falta ponerlo entre comillas.
![Imagen de una nube](C:\Users\jfvy1\Desktop\CMD "titulo")

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