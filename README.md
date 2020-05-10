Es hora de aplicar estilos a tu proyecto del blog de conciertos, en esta ocasión debes realizarlo de tres formas:

Archivo externo.
En el documento HTML
En la línea (en la misma etiqueta).
A continuación te presentamos una idea de cómo debe lucir tu documento tu proyecto.

<img src="/images/C02U1L1_contenido1.png">

Contenido
En el siguiente enlace puedes obtener los recursos para tu prototipo.

<a href="/descargas/contenido_base.zip" download="contenido_base.zip">
Descargar contenido base 
</a>

Instrucciones
Crea un archivo estilos.css dentro de la carpeta css y enlázalo con la etiqueta link dentro del head del HTML. En ese archivo externo colocar los estilos generales:
Fondo color negro.
Color blanco para letras en primer plano foreground.
Fuente verdana.
Agrega estilos dentro del documento con la etieueta style dentro del head.
Agregar h1 para el título con fuente Arial.
Agrega estilo en línea en la etiqueta img del logo colocando el fondo blanco.
Agrega estilo en línea en la etiqueta img de la imagen grande del blog y cambia el atributo width por css.
Aplica style="width: 80%".
Buenas Prácticas
Los estilos deben ser css, es decir se deben sustituir atributos de estilos como width y colocarlos en css.
Se recomienda tener siempre los estilos en archivo externo ya que se pueden compartir y el código HTML es más limpio.
Excepcionalmente se utilizan estilos en el documento HTML con la etiqueta style.