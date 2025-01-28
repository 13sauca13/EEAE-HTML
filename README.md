# Desarrollo páginas web y lenguaje HTML

>[!IMPORTANT]
>[HTML W3 Schools](https://www.w3schools.com/html/)
>
>[HTML Cheatsheet](https://htmlcheatsheet.com/)

## 1. Introducción HTML
Los lenguajes de marcas existen prácticamente desde el comienzo de la informática. Cubren la necesidad de disponer de lenguajes sencillos para el intercambio de información entre distintos sistemas. Con la llegada de internet, algunos de los lenguajes de marcas se convirtieron en piedras angulares sobre las que construir la *World Wide Web*.

Un lenguaje de marcas o lenguaje de marcado es aquel que permite representar información que contiene, además de los datos propiamente dichos, marcas o etiquetas que indican cómo se estructuran estos datos, su significado o cómo debe representarse desde un punto de vista gráfico o visual. Los lenguajes de marcas no son lenguajes de programación. No contienen instrucciones ni implican acciones directas. Son reglas que organizan la información con el objetivo de darle una estructura uniforme y facilitar su procesamiento automático. Una clasificación simplificada de los lenguajes de marcas podría ser la siguiente:
- Lenguajes orientados a la presentación de información.
- Lenguajes orientados al almacenamiento y procesado de información.

El ejemplo más representativo de un lenguaje de marcas orientado a la presentación de información es el lenguaje de marcas de hipertexto (HyperTextMarkup Language), conocido como HTML


```HTML
<html>
	<head> 
		<title>Mi web</title>
	</head>
	
	<body>
		<h1>Esta es mi primera web</h1>
		<h2>Trabajando en ello</h2>

		<p>
		Aqui irá el contenido de mi página web con todo su texto.
		<br>
		Esto va en otra línea
		</p>

		<p>
		Y más cositas.
		</p>
	</body>
</html>
```

En el ejemplo anterior nos falta introducir `<!DOCTYPE html>`, esto es una instrucción para el navegador, no una etiqueta de HTML, y aunque no es imprescindible para que la web funcione, es importante para asegurarse del correcto comportamiento puesto que de no ponerlo, el navegador, abrirá la página en *Quirks mode* (compatibilidad de navegadores antiguos) y con esta instrucción usará el *no-quirks mode* y el comportamiento será el que dictemos en el HTML y CSS de la web (veremos CSS más adelante).

Como lenguaje de etiquetado, HTML utiliza **etiquetas** para su contenido con la siguiente forma:
```HTML
<etiqueta> contenido </etiqueta>
```
Estas etiquetas no son *case sensitive*, es decir, no diferencian mayúsculas de minúsculas (es lo mismo `<body>` que `<BODY>`) pero **W3C recomienda el uso de minúsculas**, también ciertas etiquetas de HTML permiten cambiar la apariencia de los elementos pero de nuevo lo recomendado es utilizar las *hojas de estilo en cascada* **CSS**

Con todo esto, la estructura básica de una página sería:
```HTML
<!DOCTYPE html>
<html>
	<head>
	</head>
	<body>
	</body>
</html>
```
- `<html>`: Esta pareja de etiquetas indica al navegador que todo lo que encierra es lenguaje HTML y nada se escribe fuera con la excepcióon de la declaración del tipo de documento.
- `<head>`: Información de la página que no se mostrará pero que ayuda a su procesamiento.
- `<body>`: Contiene todos los elementos que el navegador procesará y mostrará.

>[!NOTE]
>Para introducir comentarios en el código HTML lo haremos de la siguiente manera:
>```HTML
><!- COMENTARIO ->
>```
### Títulos, párrafos y saltos de línea
Los encabezados llevarán etiquetas desde `<h1>`hasta `<h6>`(cuanto mayor sea el número más pequeño será el título), para los párrafos de texto usaremos la etiqueta `<p>` (esta etiqueta puede funcionar sin cierre, pero podríamos tener problemas con ciertas webs y salvo que especifiquemos lo contrario como sucede con algunas excepciones, **todas las etiquetas deben cerrarse**).

Las etiquetas también pueden tener atributos como se mencionó anteriormente, y aunque en un futuro usaremos CSS para esto, vamos a usar algunas:
- `align="alineacion"`: Modifica la alineación de un texto
- `bgcolor="color"`: Modifica el color de fondo (nombre del color o hexadecimal). Se usa en `<body>`, en `<table>` o en sus celdas, filas o columnas.
- `color="color"`: Modifica el color del texto (nombre del color o hexadecimal). Se usa en `<font>` y en `<hr>`.
- `id="identificador"`: Asigna un identificador único a un elemento, lo que permite referenciarlo fácilmente desde CSS o JavaScript.
- `class="nombreClase"`: Asigna una o más clases a un elemento, lo que permite aplicar estilos CSS específicos a grupos de elementos.
- `style="propiedadesCSS"`: Permite aplicar estilos CSS directamente a un elemento, aunque es preferible usar hojas de estilo externas para mantener el código limpio y separado (veremos CSS más adelante).

Las líneas en blanco serán ignoradas por el navegador por no contener código de manera que para dar formato al texto tenemos saltos de línea `<br>` y lineas horizontales `<hr>`, **estas etiquetas no se cierran**. Para introducir un texto preformateado usaremos `<pre> TEXTO </pre>`, de esta manera el contenido será interpretado como texto con formato, no como HTML.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de atributos en HTML</title>
	</head>
	<body>
		<h1 id="tituloPrincipal" class="titulo">Bienvenidos a mi página web</h1>
		<p class="parrafo" color="blue" align="center">
			Este es un párrafo con texto centrado y color azul.
		</p>
		<p class="parrafo" bgcolor="#f0f0f0">
			Este es otro párrafo con un fondo gris claro.
		</p>
		<pre>
			Aquí irá texto con formato
			Y se respetarán entre otras cosas los saltos de línea
		</pre>
	</body>
</html>
```

Por último existen ciertas etiquetas que indican como debe aperecer el texto que encierran:
- `<b>`: *Bold*, texto en negrita.
- `<i>`: *Italic*, texto en cursiva.
- `<u>`: *Underline*, texto subrayado.

### `<div>`
La etiqueta `<div>` es una de las etiquetas más utilizadas en HTML para agrupar y organizar contenido. Su nombre proviene de "division" (división), y se utiliza para crear contenedores que pueden contener otros elementos HTML. La etiqueta `<div>` no tiene un significado semántico específico, lo que significa que no describe el contenido que contiene. En su lugar, se utiliza principalmente para aplicar estilos y scripts a un grupo de elementos.

Más adelante al ver CSS veremos como aplicar estilos a los `<div>` según su *class* o su *id*.

En resumen se usa para agrupar elementos relacionados y aplicarles estilos o scripts comunes.
```html
<div>
    <h2>Encabezado dentro de un div</h2>
    <p>Este es un párrafo dentro de un div.</p>
</div>
```
## 2. Enlaces
Los enlaces son una parte fundamental de HTML, ya que permiten la navegación entre diferentes páginas web. La etiqueta <a> se utiliza para crear enlaces, y su atributo más importante es href, que especifica la URL del destino del enlace.
```HTML
<a href="https://www.ejemplo.com">Visita mi página de ejemplo</a>
```
Se puede añadir el atributo `title` en donde irá el texto del menú contextual que se ve al pasar con el ratón por encima del enlace aunque se recomienda por convención no añadir aquí información que no esté ya en el texto de la web o el nombre del enlace.

En el href hay más cosas que URLs que se pueden poner:
- `href="mailto:xxxxx"`: Lanza el programa de correo electrónico y empieza un nuevo mail a la dirección introducida.
- `href="tel:xxxxxxxxx"`: Marca el múmero de teléfono introducido.
- `href="fp:xxxxx"`: Conecta por FTP con el servidor introducido.
- 
### Enlaces en la misma página
Es posible hacer un enlace a otro punto de la propia página utilizando en href el valor del id de ese elemento precedido por #.
```html
<!DOCTYPE html>
<html>
<head>
    <title>Enlaces Internos</title>
</head>
<body>
    <h1>Índice</h1>
    <ul>
        <li><a href="#seccion1">Ir a la Sección 1</a></li>
        <li><a href="#seccion2">Ir a la Sección 2</a></li>
    </ul>

    <h2 id="seccion1">Sección 1</h2>
    <p>Contenido de la Sección 1.</p>

    <h2 id="seccion2">Sección 2</h2>
    <p>Contenido de la Sección 2.</p>
</body>
</html>
```
## 3. Imágen, sonido y vídeo
HTML también permite la inclusión de contenido multimedia como imágenes, sonido y vídeo. Las etiquetas `<img>`, `<audio>` y `<video>` se utilizan para estos propósitos.
### `<img>`
Para incluir una imágen tendremos que especificar el nombre y la localización de la misma, en principio usaremos jpg (o jpeg), png y gif, pero también se pueden usar más formatos (ico, svg, apng...)
```HTML
<img src="imagen.jpg" alt="Descripción de la imagen" width="500" height="300">
```
Los atributos de la etiqueta son:
- `src`: La ruta de la imagen que queremos poner en la página.
- `alt`: Texto alternativo para cuando no se puede mostrar la imágen o para personas con discapacidad visual.
- `width`: Ancho de la imágen en pixeles.
- `height`: Altura de la imágen en pixeles.

La altura y anchura de la imágen tambien puede ser definida usando CSS (preferible).

### `<audio>`
Podemos introducir audio de la siguiente manera:
```html
<audio src="audio.mp3" controls autoplay muted loop="infinite" volume="10"></audio>
```
- `controls`: Muestra los controles de reproducción.
- `autoplay`: Hace que se reproduzca automáticamente.
- `muted`: Audio muteado (si no se pone, hace caso de el atributo `volume`).
- `loop`: El audio se repite automáticamente (infinitas veces o X número de veces).
- `volume`: Establece el valor de volúmen inicial.

### `<video>`
Para introducir vídeo se utiliza esta etiqueta con los mismos atributos que la de `<audio>` pero además:
- `width`: Ancho en pixeles.
- `height`: Alto en pixeles.

## 4. Listas
En HTML, las listas son una forma de organizar y presentar información en un formato estructurado. Existen tres tipos principales de listas:

1. **Listas no ordenadas** (`<ul>`): Utilizan viñetas para enumerar los elementos.
2. **Listas ordenadas** (`<ol>`): Utilizan números o letras para enumerar los elementos.
3. **Listas de definición** (`<dl>`): Utilizan términos y descripciones, comúnmente usadas para glosarios o definiciones.

### Listas no ordenadas
Las listas no ordenadas se crean utilizando la etiqueta `<ul>`, y cada elemento de la lista se define con la etiqueta `<li>`.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de lista no ordenada</title>
	</head>
	<body>
		<h2>Lista de frutas</h2>
		<ul>
			<li>Manzana</li>
			<li>Banana</li>
			<li>Cereza</li>
		</ul>
	</body>
</html>
```
### Listas ordenadas
Las listas ordenadas se crean utilizando la etiqueta `<ol>`, y cada elemento de la lista se define también con la etiqueta `<li>`.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de lista ordenada</title>
	</head>
	<body>
		<h2>Pasos para hacer una receta</h2>
		<ol>
			<li>Precalentar el horno a 180°C.</li>
			<li>Mezclar los ingredientes secos.</li>
			<li>Añadir los ingredientes húmedos.</li>
			<li>Hornear durante 30 minutos.</li>
		</ol>
	</body>
</html>
```
### Listas de definición
Las listas de definición se crean utilizando la etiqueta `<dl>`, y cada término se define con la etiqueta `<dt>`, mientras que cada descripción se define con la etiqueta `<dd>`.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de lista de definición</title>
	</head>
	<body>
		<h2>Glosario de términos</h2>
		<dl>
			<dt>HTML</dt>
			<dd>Lenguaje de marcado para crear páginas web.</dd>
			<dt>CSS</dt>
			<dd>Lenguaje de estilos para diseñar páginas web.</dd>
			<dt>JavaScript</dt>
			<dd>Lenguaje de programación para añadir interactividad a las páginas web.</dd>
		</dl>
	</body>
</html>
```
## 5. Tablas
Las tablas en HTML se utilizan para organizar datos en filas y columnas, proporcionando una estructura clara y fácil de leer. La etiqueta principal para crear una tabla es `<table>`, y dentro de ella se utilizan varias etiquetas para definir las diferentes partes de la tabla.

### Estructura básica de una tabla
- `<table>`: Define el inicio y el final de la tabla.
- `<tr>` (table row): Define una fila de la tabla.
- `<th>` (table header): Define una celda de encabezado, que generalmente se muestra en negrita.
- `<td>` (table data): Define una celda de datos.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de tabla</title>
	</head>
	<body>
		<h2>Tabla de ejemplo</h2>
		<table border="1">
			<tr>
				<th>Nombre</th>
				<th>Edad</th>
				<th>Ciudad</th>
			</tr>
			<tr>
				<td>Ana</td>
				<td>28</td>
				<td>Madrid</td>
			</tr>
			<tr>
				<td>Juan</td>
				<td>35</td>
				<td>Barcelona</td>
			</tr>
			<tr>
				<td>María</td>
				<td>22</td>
				<td>Valencia</td>
			</tr>
		</table>
	</body>
</html>
```

En este ejemplo, hemos creado una tabla con tres columnas: "Nombre", "Edad" y "Ciudad". La primera fila contiene los encabezados de la tabla, definidos con la etiqueta `<th>`, y las filas siguientes contienen los datos, definidos con la etiqueta `<td>`. El atributo `border="1"` se utiliza para agregar un borde a la tabla.

### Atributos adicionales para tablas
- `colspan="n"`: Permite que una celda se extienda a través de varias columnas.
- `rowspan="n"`: Permite que una celda se extienda a través de varias filas.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de colspan y rowspan</title>
	</head>
	<body>
		<h2>Tabla con colspan y rowspan</h2>
		<table border="1">
			<tr>
				<th>Nombre</th>
				<th colspan="2">Información</th>
			</tr>
			<tr>
				<td>Pedro</td>
				<td>30</td>
				<td>Sevilla</td>
			</tr>
			<tr>
				<td rowspan="2">Lucía</td>
				<td>25</td>
				<td>Bilbao</td>
			</tr>
			<tr>
				<td>Ingeniera</td>
				<td>Madrid</td>
			</tr>
		</table>
	</body>
</html>
```

En este ejemplo, la celda de encabezado "Información" se extiende a través de dos columnas utilizando `colspan="2"`, y la celda que contiene "Lucía" se extiende a través de dos filas utilizando `rowspan="2"`.
## 6. Marcos y estilos
### Marcos
Los marcos (`frames`) en HTML se utilizaban para dividir la ventana del navegador en varias secciones, cada una de las cuales podía mostrar un documento HTML diferente. Sin embargo, el uso de marcos ha caído en desuso debido a problemas de accesibilidad, usabilidad y SEO. En su lugar, se recomienda utilizar técnicas modernas como el diseño de páginas con CSS y JavaScript.

### Estilos CSS
CSS (Cascading Style Sheets) es un lenguaje utilizado para describir la presentación de un documento HTML. CSS permite separar el contenido de la presentación, lo que facilita el mantenimiento y la actualización del diseño de una página web.

En HTML, hay tres formas principales de introducir CSS para aplicar estilos a una página web: **CSS en línea**, **CSS interno** y **CSS externo**.

La manera de utilizar CSS es indicando el elemento que vamos a "decorar", lo que llamamos ***selector*** (si no estamos ya en la propia etiqueta usando el atributo `style`para CSS *inline*) y luego todas las propiedades y sus valores separados por ;

Los comentarios en CSS se hacen entre `/* */`
```CSS
h1 {color:blue; font-size:12px; text-align:center;}
/* Y aqui un comentario*/
```
Según el selector que usemos lo haremos de una forma u otra:
- Etiquetas HTML: La etiqueta sin más, por ejemplo `p {text-align:justify;}`
- Id: El Id irá precedido por #, por ejemplo `#seccion3 {background-color:grey;}`
- Class: El nombre de la clase irá precedido por . , por ejemplo `.parrafos {font-family:verdana;}`

Se pueden usar varios selectores a la vez separándolos por comas:
```CSS
h1, p, .titulos {
	font-size:10px;
	color:red;
}
```

Las principales propiedades de CSS son:
| Propiedad | Descripción | Valores |
| - | - | - |
| `color` | Define el color del texto. | `nombre del color`, `#hex`, `rgb()`, `rgba()`, `hsl()`, `hsla()` |
| `background-color` | Establece el color de fondo de un elemento. | `nombre del color`, `#hex`, `rgb()`, `rgba()`, `hsl()`, `hsla()` |
| `font-size` | Define el tamaño de la fuente. | `px`, `em`, `rem`, `%`, `vw`, `vh` |
| `margin` | Establece el espacio exterior alrededor de un elemento. | `px`, `em`, `rem`, `%`, `auto` |
| `padding` | Define el espacio interior de un elemento. | `px`, `em`, `rem`, `%` |
| `border` | Establece el borde de un elemento. | `width style color` (ej. `1px solid black`) |
| `display` | Define cómo se muestra un elemento. | `block`, `inline`, `inline-block`, `flex`, `grid`, `none` |
| `position` | Establece el método de posicionamiento de un elemento. | `static`, `relative`, `absolute`, `fixed`, `sticky` |
| `width` | Define el ancho de un elemento. | `px`, `em`, `rem`, `%`, `vw` |
| `height` | Define la altura de un elemento. | `px`, `em`, `rem`, `%`, `vh` |
| `text-align` | Define la alineación del texto dentro de un elemento. | `left`, `right`, `center`, `justify` |
| `line-height` | Establece la altura de las líneas de texto. | `normal`, `número`, `px`, `em`, `%` |
| `font-weight` | Define el grosor de la fuente. | `normal`, `bold`, `bolder`, `lighter`, `100` a `900` |
| `font-family` | Especifica la familia de fuentes para el texto. | `nombre de la fuente`, `serif`, `sans-serif`, `monospace`, etc. |
| `text-decoration` | Añade decoraciones al texto. | `none`, `underline`, `overline`, `line-through` |
| `opacity` | Define la opacidad de un elemento. | `0` a `1` |

#### Media queries
CSS también puede ajustar su comportamiento a las pantallas que utilicemos, las **media queries** son una característica de CSS3 que permiten aplicar estilos CSS específicos en función de las características del dispositivo en el que se visualiza la página web, como el ancho de la pantalla, la resolución, la orientación, entre otros. Esto es fundamental para crear diseños web responsivos que se adapten a diferentes tamaños de pantalla y dispositivos.

Las media queries utilizan la regla `@media` seguida de una condición que especifica cuándo deben aplicarse los estilos.
```css
/* Estilos generales */
body {
    font-size: 16px;
}

/* Media query para pantallas con un ancho máximo de 600px */
@media (max-width: 600px) {
    body {
        font-size: 14px;
    }
}
```

En este ejemplo, el tamaño de la fuente del `body` será de 16px en pantallas más grandes, pero se reducirá a 14px en pantallas con un ancho máximo de 600px.

Existen varios tipos de media queries:
- **Ancho y alto de la pantalla**:
   - `max-width` y `min-width`: Se utilizan para aplicar estilos en función del ancho de la pantalla.
   - `max-height` y `min-height`: Se utilizan para aplicar estilos en función de la altura de la pantalla.

   ```css
   @media (max-width: 768px) {
       /* Estilos para pantallas con un ancho máximo de 768px */
   }
   ```
- **Resolución**:
   - `resolution`: Se utiliza para aplicar estilos en función de la resolución del dispositivo.

   ```css
   @media (min-resolution: 300dpi) {
       /* Estilos para dispositivos con una resolución mínima de 300dpi */
   }
   ```

- **Orientación**:
   - `orientation`: Se utiliza para aplicar estilos en función de la orientación del dispositivo (horizontal o vertical).

   ```css
   @media (orientation: landscape) {
       /* Estilos para dispositivos en orientación horizontal */
   }
   ```

- **Aspect ratio**:
   - `aspect-ratio`: Se utiliza para aplicar estilos en función de la relación de aspecto de la pantalla.

   ```css
   @media (min-aspect-ratio: 16/9) {
       /* Estilos para pantallas con una relación de aspecto mínima de 16:9 */
   }
   ```

#### Incluir CSS
##### 1. CSS en línea
El CSS en línea se aplica directamente a los elementos HTML utilizando el atributo `style`. Este método es útil para aplicar estilos rápidos y específicos a un solo elemento, pero no es recomendable para proyectos grandes debido a la dificultad de mantenimiento y la falta de separación entre contenido y presentación.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de CSS en línea</title>
	</head>
	<body>
		<h1 style="color: blue; text-align: center;">Título con CSS en línea</h1>
		<p style="color: red;">Párrafo con CSS en línea</p>
	</body>
</html>
```

En este ejemplo, los estilos se aplican directamente a los elementos `<h1>` y `<p>` utilizando el atributo `style`.

##### 2. CSS interno
El CSS interno se define dentro de la etiqueta `<style>` en la sección `<head>` del documento HTML. Este método es útil para aplicar estilos a una sola página y mantener los estilos separados del contenido HTML.

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de CSS interno</title>
		<style>
			body {
				background-color: #f0f0f0;
				font-family: Arial, sans-serif;
			}
			h1 {
				color: blue;
				text-align: center;
			}
			p {
				color: red;
			}
		</style>
	</head>
	<body>
		<h1>Título con CSS interno</h1>
		<p>Párrafo con CSS interno</p>
	</body>
</html>
```

En este ejemplo, los estilos se definen dentro de la etiqueta `<style>` y se aplican a los elementos de la página.

##### 3. CSS externo
El CSS externo se define en un archivo separado con extensión `.css` y se enlaza al documento HTML utilizando la etiqueta `<link>`. Este método es el más recomendado para proyectos grandes, ya que permite mantener los estilos separados del contenido y facilita la reutilización y el mantenimiento de los estilos.

Para utilizar CSS externo:

1. Crear un archivo CSS llamado `estilos.css`:
```CSS
body {
	background-color: #f0f0f0;
	font-family: Arial, sans-serif;
}
h1 {
	color: blue;
	text-align: center;
}
p {
	color: red;
}
```

2. Enlazar el archivo CSS en el documento HTML:
```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de CSS externo</title>
		<link rel="stylesheet" type="text/css" href="estilos.css">
	</head>
	<body>
		<h1>Título con CSS externo</h1>
		<p>Párrafo con CSS externo</p>
	</body>
</html>
```

En este ejemplo, los estilos definidos en `estilos.css` se aplican al documento HTML, manteniendo el contenido y la presentación separados.
## 7. Maquetando todo
Existen ciertas etiquetas semánticas para estructurar una página web de manera clara y organizada, estas etiquetas ayudan a describir el propósito de su contenido, lo que mejora la accesibilidad y el SEO de la página.

![Etiquetas semánticas](https://github.com/user-attachments/assets/15f4bb25-a27d-4d29-b119-d6c58c866999)


#### `<header>`

La etiqueta `<header>` se utiliza para definir el encabezado de una página o sección. Generalmente, contiene elementos como el logotipo, el título del sitio, y el menú de navegación principal.

```html
<header>
    <h1>Mi Sitio Web</h1>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#sobre">Sobre mí</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
</header>
```

#### `<nav>`

La etiqueta `<nav>` se utiliza para definir una sección de navegación que contiene enlaces a otras partes del sitio web o a otras páginas.

```html
<nav>
    <ul>
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#sobre">Sobre mí</a></li>
        <li><a href="#contacto">Contacto</a></li>
    </ul>
</nav>
```

#### `<section>`

La etiqueta `<section>` se utiliza para definir una sección genérica de contenido. Cada `<section>` debe tener un tema específico y puede contener encabezados, párrafos, imágenes, y otros elementos.

```html
<section id="inicio">
    <h2>Bienvenido a mi sitio web</h2>
    <p>Este es el contenido de la sección de inicio.</p>
</section>
```

#### `<article>`

La etiqueta `<article>` se utiliza para definir un contenido independiente que puede ser distribuido o reutilizado, como un artículo de blog, una noticia, o una entrada de foro.

```html
<article>
    <h2>Título del artículo</h2>
    <p>Este es el contenido del artículo.</p>
</article>
```

#### `<aside>`

La etiqueta `<aside>` se utiliza para definir contenido adicional que está relacionado con el contenido principal, pero que no es parte de él. Generalmente, se utiliza para barras laterales, citas, o enlaces relacionados.

```html
<aside>
    <h3>Enlaces relacionados</h3>
    <ul>
        <li><a href="#enlace1">Enlace 1</a></li>
        <li><a href="#enlace2">Enlace 2</a></li>
    </ul>
</aside>
```

#### `<footer>`

La etiqueta `<footer>` se utiliza para definir el pie de página de una página o sección. Generalmente, contiene información de contacto, derechos de autor, y enlaces a políticas de privacidad o términos de uso.

```html
<footer>
    <p>&copy; 2025 Mi Sitio Web. Todos los derechos reservados.</p>
</footer>
```
