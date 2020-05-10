# Practica-CSS
Pequeños proyectos que realise para aprender a manejar los conseptos de html.
Propiedades para Fuentes
Propiedades de Color y Fondo:
Font-Family: Times, Serif, “New Century
Schoolbook”, Arial.
Especifica el tpo de fuente.
Define cómo mostrar el texto, normal o
inclinado.
Font-Style: normal o italic o oblique
Define si el texto se muestra en
mayúsculas, pero con el texto un poco
más grande que en minúsculas.
Font-variant: normal o SMALL-CAPS
Especifica el tamaño del texto a
Font-size: 10px
Font: italic bold 12px helvetca
Propiedades para Texto
word-spacing: 0.4em;
Define la cantdad de espacio existente
entre palabras
Define la cantdad de espacio existente
entre letras.
leter-spacing: 0.1 em;
Define la presentación de un texto con
subrayado, línea superior, tachado o
text-decoraton: none o underline o overline
o line-through o blink
Define la alineación de un texto con
respecto a la línea horizontal donde se
encuentre ubicado.
vertcal-align: baseline o sub o super o
top o text-top o middle o botom o
text-botom
background-image: url(image/imagen.jpg)
Color: blue, otra manera de definirlo es con
valores hexadecimales color: #000080
Define el color de un elemento, se puede
expresar con el nombre del color o su
representación en hexadecimal.
Define un color de fondo a un elemento.
Define una imagen para el fondo del
elemento.
background-color: red, otra manera de
definirlo es con valores hexadecimales,
background-color: #000080
background-repeat: repeat o repeat-x o
repeat-y o no-repeat.
repeat-y: permite que se repita la
imagen vertcalmente.
repeat: permite que se repita la imagen
tanto vertcal como horizontalmente.
no-repeat: evita que la imagen se
repita.
Repeat-x: permite que se repita la
imagen horizontalmente.
Background-atachment: scroll o fixed
Determina si la imagen de fondo se
desplaza con el contenido o si queda
fija con respecto al lienzo. Debe estar
acompañada de Background-image de
la siguiente manera:
 body
{
 background-image: url(image/imagen.jpg);
 background-atachment: fixed;
}
CURSO: WEB
margin-top: 5em
Especifica el margen que existe entre un
elemento superior y la tabla, por defecto su valor es 0.
Define el margen derecho de un elemento.
margin-right: 3em
Especifica el margen inferior de un
elemento.
margin-botom:12em
Define un margen superior de 1em,
right de 2 em, botom de 3em y lef de
margin: 1em 2em 3em 4em
Especifica el espacio que debe existr
entre el borde superior y el siguiente
padding-top: 0
Describe el espacio que debe existr
entre el borde derecho y el contenido.
padding-right: 0
Propiedades para Tablas
Define la alineación de un texto con
respecto a la línea horizontal donde se
encuentre ubicado.
baseline: alineación en toda la base del
elemento (alineación por defecto).
middle: alineación del texto en la línea
media horizontal.
sub: alineación como subíndice.
super: alineación como exponente o
superíndice.
text-top: alineación en la línea superior
horizontal.
text-botom: alineación en la parte inferior de la línea vertcal.
Capitalize: en mayúscula el primer caracter de cada palabra.
UPPERCASE: en mayúsculas todas las
letras de cada palabra.
Lowercase: en minúsculas todas las
letras de cada palabra.
text-transform: none o Capitalize o UPPERCASE o lowercase.
Define la alineación del texto: alineación
a la derecha, izquierda, centro o justficado.
text-align: lef o right o center o justfy.
padding-lef: 0
Define el espacio que debe existr entre
el borde izquierdo y el contenido.
Especifica el espacio que debe existr
entre el borde inferior y el contenido.
padding-botom: 0
Define, de manera agrupada, 1em para
top, 2 em para right, 3em para botom y
4 em para lef.
padding: 1em 2em 3em 4em
Se usa para especificar el ancho de un
elemento en el borde superior.
border-top-width: 0
Se usa para definir el ancho de un elemento en el borde derecho.
border-right-width: 0
Especifica el ancho del borde inferior
de un elemento.
border-botom-width:
Describe el valor del ancho del borde
izquierdo de un elemento.
border-lef-width: 0
Se usa para definir el color de los
bordes de un elemento, su valor puede
ser el nombre del color o su valor en
hexadecimal.
border-color: blue o border-color:
#000800
Define la apariencia del borde de un
elemento, según la propiedad asignaBorder-style: none doted dashed solid
double groove ridge inset outset
border-top: valorparaelancho valorparaelestlo valorparaelcolor
Propiedades de Clasificación:
block: crea un salto de línea después
del elemento.
inline: quita los saltos de línea que
estén a contnuación del elemento.
Listtem: agrega un marcador de ítems
de lista
none: sin ningún tpo de visualización
definida.
Display: block inline listtem none
CURSO: WEB
Define el valor horizontal de un elemento.
width: 30px
Define el tamaño vertcal de un elemento.
height: 30px
Permite ajustar texto alrededor de un
elemento.
Float: lef o right o none
border-right: valorparaelancho valorparaelestlo valorparaelcolor
border-botom: valorparaelancho valorparaelestlo valorparaelcolor
border-lef:valorparaelancho valorparaelestlo valorparaelcolor
whitespace: normal pre nowrap
normal: cuando se crean varios espacios
en blanco en un solo lugar, los
convierte a un solo espacio en blanco.
pre: no combina espacios en blanco.
nowrap: no permite saltos de línea si no
está la etqueta <br>.
Liststyletype: disc circle square decimal
lowerroman upperroman loweralpha
Se usa para especificar la presentación
de las listas a través de círculos,
decimales, letras en mayúsculas, entre
otros.