# Desarrollo páginas web y lenguaje HTML

>[!IMPORTANT]
>[HTML W3 Schools](https://www.w3schools.com/html/)

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

## 2. Enlaces
## 3. Imágen, sonido y vídeo
## 4. Listas
## 5. Tablas
## 6. Marcos y estilos
## 7. Formularios
