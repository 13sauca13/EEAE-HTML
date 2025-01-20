# Desarrollo páginas web y lenguaje HTML

>[!IMPORTANT]
>[HTML W3 Schools](https://www.w3schools.com/html/)

## 1. Introducción HTML
## 2. Weblogic
## 3. Enlaces
## 4. Imágen, sonido y vídeo
## 5. Listas
## 6. Tablas
## 7. Marcos y estilos
## 8. Formularios


## El lenguaje HTML es para las personas

El HTML no es únicamente para las personas que trabajan en el campo tecnológico. Es para cualquiera, de la misma manera que los documentos son también para cualquiera. HTML es simplemente otro tipo de documentos. Uno muy especial con el que se construye la web.

La [página original en inglés](https://htmlforpeople.com/) ha sido escrita por [Blake Watson](https://blakewatson.com/). Que ha estado creando sitios web desde los inicios del 2000. Aunque trabaja de manera profesional en este campo, cree que _cualquiera_ debería ser capaz de crear un sitio web con HTML si quisiera.

Este libro le enseñará cómo realizar justamente eso. No requiere que tenga experiencia previa sobre cómo hacer sitios web o en crear código. En este libro se tratará todo lo que necesita saber para empezar de una manera accesible y fácil.

Esta traducción en español que está leyendo, está realizada por mí ([Victorhck](https://victorhckinthefreeworld.com)) porque me pareció un gran recurso para aprender desde cero a crear páginas web y así difundir el conocimiento de las herramientas y los materiales que crean esta gran red llamada Internet.

Podrá crear su propia página web, escribir de lo que quiera y ser protagonista y no un mero espectador. Este traducción espera que sea instructiva y emancipadora. Utilícela en un taller que realice, en su organización, en una charla o a nivel personal y sea parte de un cambio hacia un Internet más _artesanal_ y menos industrial.

¿Quiere empezar? ¡Vamos a hacerlo!

<center>-#-</center>

## Introducción

No creo que los sitios web estén destinados a ser creados únicamente por "profesionales de la web". Los sitios web son en el fondo otro tipo de documentos. Casi todo el mundo sabe cómo crear un documento en esta era digital, ya sea Word, Google Docs, Markdown o cualquier otro formato. HTML no debería ser una excepción. Seguro que es un poco más técnico que otro tipo de documentos, pero también es muy especial.

Es el formato de documento de la web. El humilde documento HTML es omnipresente. Está en todas partes. Si visitó un sitio web hoy, es casi seguro que vio HTML.

HTML es robusto. Podría mirar un sitio web creado hoy o uno creado hace veinte años. Ambos usan HTML y ambos funcionan. Se trata de un logro que no muchos formatos de documentos pueden presumir. Tampoco necesita ningún programa especial para crear un documento HTML. Existen muchos y podrías utilizar cualquiera de ellos. También puede simplemente abrir el bloc de notas o el editor de texto más básico y escribir HTML a mano (spoiler: vamos a hacer precisamente eso).

Creé este libro web porque quería algo para las personas que no se consideran desarrolladores web profesionales. Imagínese si los documentos de Word fueran creados únicamente por "profesionales de Word". No. Saber cómo escribir HTML y publicarlo en la web es una habilidad valiosa que resulta útil para todo tipo de actividades profesionales y personales. No pertenece sólo a aquellos de nosotros que hacemos sitios web de manera profesional. HTML es para todos. HTML es para personas.

### ¿Para quién es este libro?]

Este libro está dirigido a personas que no tienen experiencia previa en crear código de ningún tipo. Asumiré que no sabe nada sobre HTML. Empezaremos poco a poco. Pero al final del libro habremos creado un sitio web personal completo con varias páginas, imágenes, un blog y más.

_Asumiré_ que tiene algo de experiencia usando una computadora y realizando tareas básicas como crear archivos y carpetas. Este es un requisito previo necesario porque (nuevamente, alerta de spoiler) los sitios web son esencialmente solo archivos y carpetas.

### ¿Qué necesito?

Necesita una computadora con acceso a internet. Escribí este libro de forma genérica para que fuera aplicable a personas que utilizan macOS, Windows o Linux. Si le indico el software que debe instalar, será gratuito (o tendrá un nivel gratuito utilizable) y será multiplataforma (u ofreceré alternativas para otras plataformas).

<a id="Indice">
### Índice de contenidos

1.  [De cero a internet: tu primer sitio web](#Cap1)
2.  [Añadir contenido a tu sitio web](#Cap2)
3.  [Intermedio: actualizar tu editor de texto](#Cap3)
4.  [Un sitio web con estilo](#Cap4)
5.  [Añadir una página "Acerca de"](#Cap5)
6.  [Añadir un blog](#Cap6)
7.  [Añadir un currículum](#Cap7)
8.  [Intermedio: instalación de un servidor web local](#Cap8)
9.  [Añadir una página divertida](#Cap9)
10.  [Logro desbloqueado: Hypertexter](#Cap10)

<a id="Extras">
### Capítulos extras

Esta es la materia que quería tratar pero sentí que estaba un poco fuera de alcance. CSS y PHP tienen una curva de aprendizaje un poco más pronunciada en comparación con HTML. Sin embargo, no creo que estén fuera del alcance de cualquiera que quiera explorarlos. Y un poco de ambos puede ser de gran ayuda. Así que esta es mi manera de ofrecer una pequeña muestra de cada uno.

1.  [Personalizar Simple.css](#Cap11)
2.  [Lo básico de CSS](#Cap12)
3.  [HTML reutilizable con PHP](#Cap13)

<center>-#-</center>

<a id="Cap1">
## De cero a internet: tu primer sitio web

Usted, está a punto de pasar de cero a internet creando su primera página personal en la web.

Le contaré un pequeño secreto: los sitios web son sólo archivos con texto. No requieren software sofisticado y costoso para crearlos. Puede crear un sitio web con las herramientas de edición de texto gratuitas que vienen con su computadora. De hecho, eso es lo que haremos ahora.

---

**Nota**

Si bien es posible crear un sitio web en un teléfono móvil o en una tableta, es mucho más común hacerlo desde una computadora. Entonces, eso es lo que haremos en este libro. Dicho esto, lo que aprenderá se aplicará a otros contextos. Una cosa hermosa de la web es que hay muchas maneras de crear en ella.

---

### Paso 1. Cree una carpeta en su equipo

Elija una ubicación en su computadora y cree una carpeta. Llámelo `mi-sitio` o algo similar. Es mejor nombrar las carpetas y archivos de su sitio web con letras minúsculas, números, guiones o guiones bajos. Evite espacios en los nombres de archivos. Esto garantiza que sus archivos serán compatibles con muchas computadoras y servidores diferentes.

---

**Nota**

¿Necesita ayuda para crear una carpeta? A continuación se explica cómo hacerlo en algunos de los sistemas operativos comunes.

-   [Crear una carpeta en Windows](https://perma.cc/H5YD-7W8S)
-   [Crear una carpeta en macOS](https://perma.cc/X9RD-T6RH)
-   [Crear una carpeta en Ubuntu Linux](https://perma.cc/B7LV-XXD5)

---

Probablemente terminará creando varios sitios web a medida que pasa el tiempo, por lo que puede seguir adelante y crear una carpeta llamada `webs` y poner `mi-sitio` dentro de ella si lo desea.

![Captura de pantalla de una ventana de un explorador de archivos mostrando una carpeta llamada "Websites" seleccionado en el panel izquierdo y una carpeta llamada "mi-sitio" mostrando dentro la carpeta "Websites" en el panel derecho. Traducido por Victorhck](imagenes/zero-to-internet-01_es.webp)

### Paso 2. Crear un archivo llamado index.html

Por convención, la página de inicio de un sitio web es `index.html`. Puede que tenga otras páginas (como `acercade.html` o cualquier otra que desee), pero llegaremos a eso más adelante.

Para crear el archivo `index.html`, abra TextEdit en Mac o Notepad en Windows o un editor de texto sencillo.

---

**Usuarios de Mac**

Los sitios web deberían ser _texto plano_, así que tendremos que decirle a TextEdit que utilice texto plano. Para eso, hacer clic en _Formato_ en la barra de menú escoger _Hacer texto plano_. Después abrir los austes de TextEdit, y hacer clic en la pestaña de abrir y guardar, y marcar la opción _Mostrar los archivos HTML como código HTML en vez de texto formateado_. Si ya estás en esta sección, si quiere que TextEdit siempre utilice texto plano de manera predeterminada, escoja _Texto plano_ bajo la pestaña de Nuevo Documento, en la sección Formato.

---

Escriba una frase o dos sobre usted. Esta es la mía, por ejemplo:

```html
Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo.
```

Ahora guarde este archivo con el nombre de `index.html` y colóquelo en la carpeta `mi-sitio` que creó en el paso 1.

![Captura que muestra la ventana de un editor de texto que muestra el contenido de un archivo llamado "index.html." El texto dice: "Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo.](imagenes/zero-to-internet-02_es.webp)

---

**Nota**

Cuando realice sitios web, es esencial fijarse en la extensión del archivo, la parte del nombre que va después del punto. Si no la ve, así es como puede mostrarla [Windows](https://perma.cc/3LAG-L6YW) o [Mac](https://perma.cc/KYR3-6H3L).

---

### Paso 3. Previsualizar su sitio web

Puede abrir su sitio web haciendo doble clic en el archivo `index.html`. Debería abrir su navegador predeterminado. También puede abrir primero su navegador y después hacer clic sobre la opción _Archivo_ > _Abrir archivo…_, y después seleccionar el archivo `index.html` dentro de la carpeta.

¡Debería ver su (ciertamente simple) sitio web en su navegador! Siéntase libre de ajustar el texto y corregir errores tipográficos, porque estamos a punto de publicar esta página con el _mundo_.

No se preocupe ahora por su aspecto. Más adelante vamos a solucionar eso.

![Se muestra una ventana de un navegador que muestra una página web simple con un texto en negro sobre un fondo blanco. Se puede leer en el texto: "Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo." La URL de la página web muestra una dirección en la barraa que es la ruta de un archivo local.](imagenes/zero-to-internet-03_es.webp)

### Paso 4. Publicar su sitio web

Hay muchas opciones para publicar su sitio web. Para nuestros propósitos, necesitamos algo gratuito, fácil y dirigido a individuos en lugar de empresas. Afortunadamente, conseguimos precisamente eso con [Neocities](https://neocities.org).

---

**Servicios webs alternativos**

A lo largo de este libro, usaré Neocities como ejemplo. Pero me gustaría mencionar otras alternativas en caso de que alguna le guste.

-   **[Yay.boo](https://yay.boo/):** Nombre tonto, publicación de sitios web sin esfuerzo. Simplemente arrastre y suelte una carpeta, elija un nombre y su sitio web estará en línea.
-   **[Glitch](https://glitch.com/):** Esta es una buena opción si desea crear el código todo directamente en el navegador. Constrúyalo y luego publíquelo.
-   **[Netlify](https://www.netlify.com/):** Más sofisticado, pero tiene una funcionalidad [arrastrar y soltar carpeta para publicar](https://perma.cc/W3PH-5KRS) y le ofrece funciones más centradas en el desarrollador.

---

Diríjase a Neocities y cree una cuenta. Es gratis. También deberá elegir un nombre de usuario/nombre de sitio. Su sitio web finalmente estará en un _subdominio_ en `SUNOMBRE.neocities.org`. Sugiero usar su nombre real o su nombre de usuario en línea o nick si tiene uno. O, si sabe de qué quiere que se trate su página, puede elegir algo que se ajuste al tema. (por ejemplo, `fandegatos`).

Una vez que haya creado su cuenta, vaya al [panel de control del sitio o dashboard](https://neocities.org/dashboard). Verá que ya existen algunos archivos iniciales ya creados. Puede ignorarlos por ahora. Para publicar la página que acaba de crear en su computadora, arrastre el archivo `index.html` de su equipo hasta el panel de control de Neocities. Eso reemplazará el archivo `index.html` que ya existía.

![Captura de pantalla del panel de control de Neocities mostrando una web llamada "My Cool Website" que pertenece al usuario blakewatson. La interfaz muestra opciones para crear un nuevo archivo, una carpeta o subir archivos y también infromación sobre el almacenamiento utilizado y la actividad del sitio.](imagenes/zero-to-internet-04.webp)

Una vez que haya hecho eso, haga clic en el enlace a su sitio en la parte superior del panel.

**¡Felicidades, acaba de hacer una página web!** 🎉

<center>-#-</center>

<a id="Cap2">
## Añadir contenido a tu sitio web

Primero, dese una palmadita en la espalda porque ahora tiene un sitio web personal. Ahora es el momento de hacerlo más interesante.

---

**Usuario de Windows**

Si no lo ve en la carpeta de su sitio web cuando usa _Archivo > Abrir_, busque el menú desplegable Documentos de texto en la esquina inferior derecha de la ventana Abrir y cámbielo a _Todos los archivos_.

---

## Añadir un encabezado

¡Démosle un nombre! Depende del tipo de sitio que esté creando, pero el mío será una página de inicio personal. Todo el mundo, incluso su cuñado, tiene un perfil en las redes sociales, pero son aburridos y todos iguales. Merecemos _más_. Y nuestra vieja amiga, la página de inicio personal, es un lugar perfecto para comenzar.

```html
Página web de Victorhck.

Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo.
```

¡Genial! Vamos a verlo en el navegador.

![Se muestra una ventana de un navegador que muestra una página web simple con un texto en negro sobre un fondo blanco. Se puede leer en el texto: "Página web de Victorhck. Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo."](imagenes/add-content-1_es.webp)

Bueno, eso no es lo que queremos. El navegador juntó nuestro texto en una sola línea. ¡¿Qué pasa?!

Nos falta el _marcado_ en el lenguaje de _marcado_ de Hipertexto. Le debemos decir a nuestro navegador que queremos el nombre de nuestro sitio en un encabezado. En HTML, puede tener hasta seis niveles de encabezados. Vamos a ajustar el nombre de nuestro sitio con el encabezado más importante, es decir, _un encabezado de nivel 1_, o `<h1>`.

¿Qué es este extraño código de letras y símbolos que acabo de escribir? Se llama etiqueta HTML. Envolvemos partes de nuestra página en etiquetas para indicarle al navegador web cuáles son. Hagámoslo ahora.

```html
<h1>Página web de Victorhck.</h1>

<p>
  Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo.
</p>
```

Aquí, hemos separado los dos elementos de nuestra página y encerrado cada una dentro de etiquetas. Estamos diciendo que el nombre de nuestro sitio debería ser un encabezado de nivel 1 y nuestro primer párrafo debería ser, bueno un _párrafo_, eso es lo que significa el código `p`.

Tenga en cuenta que cada par de etiquetas tiene una etiqueta de _apertura_ y una etiqueta de _cierre_ (salvo algunas excepciones que veremos más adelante). La etiqueta de cierre es idéntica a la de apertura, excepto que empieza con una barra inclinada, `/`.

Ahora, guardemos el archivo y recarguemos el navegador. Este suele ser el flujo de creación de un sitio web: cambiar algún código, guardarlo y luego pulsar recargar en el navegador. Y ahora, ¡sienta el poder corriendo por tus venas mientras crea un sitio web a partir de la nada!

![Un navegador web muestra una página web sencilla con un título grande y en negrita. "Página de Victorhck." el contenido dice: "Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo.](imagenes/add-content-2_es.webp)

¡Epa, eso está mucho mejor! Vamos a ir añadiendo más contenido.

### Enlazando a otros sitios web

¿Alguna vez se ha preguntado por qué se llama _la web_? ¿Qué significa eso? La salsa especial que la hace una web (o red en español) es el _hiperenlace_, o lo que normalmente se llama, un _enlace o link_. Ya sabe, a menudo es un texto en azul, subrayado sobre el que se puede hacer clic y saltar a otra página web, sitio, imagen, vídeo de gatos o cualquier cosa.

Es posible gracias al elemento _anchor_, o “Una etiqueta,” como se conoce comunmente. Tiene este aspecto:

```html
<a>Esto ahora mismo no irá a alguna parte</a>
```

En lo que haya dentro de las etiquetas `<a>` se puede hacer clic encima de ello. Pero ¿dónde nos llevará ese enlace? Tal como lo hemos escrito, a ningún sitio. Necesitamos darle un destino. Podemos hacer eso dándole a la etiqueta `<a>` un _atributo_ llamado `href`. Es la _referencia de hipertexto_, el lugar al que quiere que se dirija al hacer clic en el enlace.

```html
<a href="https://www.wikipedia.org/">Ir a Wikipedia</a>
```

Vamos a añadir un enlace en nuestro sitio web, vamos a elegir uno de sus sitios web favoritos o algo que le parezca divertido e interesante.

```html
<h1>Página web de Victorhck</h1>

<p>
  Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo.
</p>

<p>
  Echa un vistazo a estos fantásticos juegos web en <a href="https://neal.fun/">Neal.fun</a>!
</p>
```

¡Guardar y recargar!

![Captura de un navegador mostrando"Página web de Victorhck." El texto dice: "Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo. Echa un vistazo a estos fantásticos juegos web en Neal.fun!" La página tiene un diseño minimalista con texto negro en un fondo blanco e incluye un enlace.](imagenes/add-content-3_es.webp)

Con la ayuda de las humildes etiquetas `<a>`, su sitio web es parte de la vibrante red. Hay más de cien etiquetas HTML, pero no es necesario memorizarlas todas para crear un sitio web. Puede hacer mucho con poco. Veamos algunas etiquetas más que pueden ayudarle a comenzar.

### Listas de cosas

Para las personas aficionadas a las listas, este conjunto de etiquetas es para vosotros. Usaremos los elementos de _lista sin orden_, `<ul>` (iniciales de _**u**nordered **l**ist_), para añadir una lista. El código `<ul>` define la lista, mientras que, cada uno de _los elementos de la lista_ está definido con la etiqueta, `<li>`, (iniciales de _**l**ist **i**tem_). Como esta:

```html
<ul>
  <li>El primer elemento</li>
  <li>Otro elemento</li>
  <li>Y finalmente, otro elemento</li>
</ul>
```

El código anterior crea una lista similar a esta:

-   El primer elemento
-   Otro elemento
-   Y finalmente, otro elemento

Si desea una lista numerada, cambie `<ul>` por `<ol>` (iniciales de _**o**rdered **l**ist_). ¡Eso es todo! Así creará la lista numerada que desea.

1.  El primer elemento
2.  Otro elemento
3.  Y finalmente, otro elemento

Vamos a añadir una lista a nuestro sitio web. Aquí está el sitio web completo:

```html
<h1>Página web de Victorhck</h1>

<p>
  Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñanado a otras personas a hacer lo mismo.
</p>

<p>
  Echa un vistazo a estos fantásticos juegos web en <a href="https://neal.fun/">Neal.fun</a>
</p>

<h2>Juegos de mesa favoritos</h2>

<ul>
  <li>Dungeons & Dragons</li>
  <li>Risk</li>
  <li>Pandemic</li>
</ul>

<h2>Cómo hacer un sitio web</h2>

<ol>
  <li>Crear un archivo HTML</li>
  <li>Escribir algo de HTML en él</li>
  <li>Abrirlo en el navegador web</li>
</ol>
```

¡Oye, esto poco a poco está empezando a parecerse a un sitio web!

![Una página web titulada "La página web de Victorhck" es lo que se muestra. Incluye secciones de los juegos de mesa favoritos (Dungeons & Dragons, Risk, Pandemic) e instrucciones de cómo realizar un sitio web: 1. Crear un archivo HTML, 2. Escribir algo de HTML en él, 3. Abrirlo en el navegador web.](imagenes/add-content-4_es.webp)

Notará que puse una nueva etiqueta en el código que he mostrado, sin mencionarla. Es un _encabezado de nivel 2_, o etiqueta `<h2>`. Los encabezados agregan estructura a una página, lo que facilita que los visitantes encuentren lo que buscan.

Hay otra diferencia sutil entre las etiquetas que hemos estado usando. Algunas de ellas, como la etiqueta `<a>`, son _elementos en línea_, lo que significa que no comienzan nuevas líneas y solo ocupan el ancho necesario. Otras etiquetas como `<h1>`, `<ul>`, o `<p>`, son conocidas como _elementos de bloque_. Un elemento de bloque comienza en una nueva línea y ocupa el ancho completo de su contenedor.

Hasta ahora tenemos muchas palabras, pero ¿sabe cuánto valen mil palabras?

### Añadir imágenes a su sitio web

Vamos a añadir una imagen interesante a nuestro sitio web. Si bien puede resultar tentador ir a Google Imágenes y tomar lo primero que encuentre, ese no es el camino a seguir. Debe asegurarse de tener los derechos adecuados sobre la imagen. Hay muchos lugares en la web para encontrar imágenes que podremos usar. (Buscar imágenes con licencia _Creative Commons_). Para simplificar, usemos el popular sitio de imágenes libres, [Unsplash](https://unsplash.com).

Encontré una imagen genial del espacio. Descargué la versión de tamaño pequeño y le cambié el nombre a `espacio.jpg` para que sea más fácil llamarla. Encuentre una imagen que le guste y suéltela en la carpeta al lado de su archivo `index.html`.

Puede agregarla a su página usando la _etiqueta de imagen_ o `<img>`. A diferencia de las etiquetas que hemos visto hasta ahora, la etiqueta `<img>` no _necesita etiqueta de cierre_. Es algo similar a esto:

```html
<img src="espacio.jpg" alt="Fotografía del espacio con estrellas y polvo de estrellas.">
```

Al igual que la etiqueta `<a>`, la etiqueta `<img>` también utiliza atributos para ofrecer más información sobre cómo quiere que se utilice esa etiqueta.

Utilice el atributo `src` para decirle a su etiqueta de imagen la _fuente_ de su imagen, esto es, dónde está ubicada. En este ejemplo, decimos que la imagen está en la misma carpeta que nuestro archivo `index.html` (en lugar de una subcarpeta) y especificando que el nombre de archivo de la imagen es `espacio.jpg`.

También necesitamos describir la imagen en caso de que algunas personas que visiten nuestro sitio web no puedan verla. Esto podría suceder por varias razones: tal vez nuestro visitante sea una persona ciega y utilice un lector de pantalla para acceder a sitios web. O tal vez un problema técnico hace que la imagen no se cargue por algún motivo. Si eso sucede, nuestro texto _alternativo_, o texto `alt`, será lo que se muestre.

Después de estos cambios, guardemos y actualicemos el navegador.

![Captura de pantalla de "La web de Victorhck" mostrando una imagen del espacio. El texto que se muestra dice que Victorhck disfruta haciendo sitios web y enseñando a otras personas a hacer lo mismo. Más abajo hay una sección de juegos de mesa favoritos con tres opciones y una guía de tres pasos para hacer un sitio web.](imagenes/add-content-5_es.webp)

Cambié el tamaño de la ventana para que toda la página cupiera en la captura de pantalla, pero si ve una barra de desplazamiento, ¡eso también está bien!

Dependiendo de su imagen, es posible que desee hacerla más pequeña o más grande. Puede utilizar los atributos `width (ancho)` y/o `height (alto)` para realizar esto. Si no especifica _ninguna_ anchura o altura, el navegador mantendrá el _aspecto_ de la imagen, no la deformará estirándola o aplastándola. Para establecer un ancho o alto para la imagen, debe proporcionar un número que representa una cantidad de píxeles.

```html
<img src="espacio.jpg" alt="Fotografía del espacio con estrellas y polvo de estrellas." width="300">
```

Si establecemos el `ancho` a `300`, tendrá este aspecto:

![Captura de pantalla de "La web de Victorhck" mostrando una imagen del espacio. La imagen es mucho más pequeña que la captura anterior. El texto que se muestra dice que Victorhck disfruta haciendo sitios web y enseñando a otras personas a hacer lo mismo. Más abajo hay una sección de juegos de mesa favoritos con tres opciones y una guía de tres pasos para hacer un sitio web.](imagenes/add-content-8_es.webp)

### Añadir notas a su código

A veces, querrá poner notas en su código: texto que no se muestra en la página pero que permanece visible en el código. Puede hacer esto para ayudar a organizar un documento, dejar notas (como todos) para usted en el futuro o incluso ocultar algún código de trabajo en progreso que no desea que se muestre todavía.

Por ejemplo, podría dejar una nota para revisar y actualizar mis juegos de mesa favoritos.

```html
<h2>Juegos de mesa favoritos</h2>

<!-- Nota: después de jugar algunos juegos nuevos, ver si alguno merece estar en esta lista. -->

<ul>
  <li>Dungeons & Dragons</li>
  <li>Risk</li>
  <li>Pandemic</li>
</ul>
```

El navegador ignorará cualquier cosa que esté entre `<!--` y `-->` y no se mostrará en la página. Este tipo de texto es llamado un _comentario_. Los comentarios le brindan una buena manera de añadir notas en el código, ya que solo son visibles en el código, no en la página web representada.

Aquí hay otro ejemplo de cómo incluí varias etiquetas HTML dentro de un comentario. Nada del comentario aparecerá en la página, solo en el código fuente.

```html
<!--
Trabajo en progreso. Cuando finalice esta lista, eliminaré las marcas de los comentarios

<h2>Juegos de mesa favoritos</h2>

<ul>
    <li>Dungeons & Dragons</li>
    <li>Risk</li>
    <li>Pandemic</li>
</ul>
-->
```

**Su código HTML es público, incluso los comentarios.** Cualquiera puede ver el código fuente de su sitio web, así que no ponga nada secreto o privado en los comentarios. Para ver el código fuente de una página, puede pulsar el atajo de teclado o encontrar la opción indicada en el menú de su navegador web. Varía dependiendo del navegador. Eche un vistazo a esta [referencia en Lifewire](https://perma.cc/3WP3-R9XL).

### Dele cabeza y cuerpo a su sitio web

No he sido totalmente honesto con usted hasta ahora. Hemos estado tomando un atajo. Hemos estado escribiendo _únicamente_ las cosas que el navegador mostrará en nuestro archivo `index.html`. Pero cada sitio web tiene una sección invisible. Y ahora su sitio web la necesita.

¿Recuerda cómo envolvimos la mayoría de los elementos en etiquetas? De hecho, necesitamos envolver toda la página en la etiqueta `<html>`. Una página HTML se divide además en una sección invisible llamada cabeza o `<head>` que contiene la información sobre su sitio web, y el cuerpo o `<body>`, que es donde va todo el contenido.

```html
<html>
  <head>
    <!-- la info sobre su sitio web va aquí-->
  </head>

  <body>
    <!-- el material que desea mostrar en su página web va aquí -->
  </body>
</html>
```

Para que nuestro documento HTML sea oficial, agreguemos una línea `doctype` al comienzo del todo. Se necesita principalmente por razones históricas, pero le dice a su navegador web, “Hey, soy un documento HTML, así que por favor procede a mostrarme de manera correcta”. Está bien copiar y pegar esa línea y seguir adelante; no sienta que necesita memorizar cada pequeño detalle.

```html
<!doctype html>
<html>
  <head>
    ...
  </head>

  <body>
    ...
  </body>
</html>
```

Por ahora, vamos a incluir dos elementos en la sección `<head>`: una etiqueta de título y una meta etiqueta.

```html
<head>
  <meta charset="utf-8">
  <title>La web de Victorhck</title>
</head>
```

La etiqueta `<title>` controla el texto que aparece en la pestaña del navegador en su sitio web y el nombre de su sitio cuando aparezca en los resultados de búsqueda. ¡Genial!

Podemos utilizar la etiqueta `<meta>` en múltiples ocasiones para darle al navegador información extra sobre nuestra página web. En este caso, le estamos diciendo qué _conjunto de caracteres_ utilizar. Todo lo que necesita saber aquí es que el texto UTF-8 significa que los símbolos especiales, como los emojis, aparecerán como se esperaba. Lo incluiremos primero, antes de cualquier otro elemento de texto, para asegurarnos de que todo nuestro texto se muestre correctamente.

---

**Nota**

Si le confunden todas las etiquetas adicionales que estamos viendo aquí, debe saber que puede copiar y pegar esta estructura de código inicial para no tener que recordarlo todo ahora mismo.

---

Aquí está el archivo `index.html` completo como referencia:

```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Página web de Victorhck</title>
  </head>

  <body>
    <h1>Página web de Victorhck.</h1>

    <img src="espacio.jpg" alt="Fotografía del espacio con estrellas y polvo de estrellas.">

    <p>
      Mi nombre es Victorhck. Disfruto haciendo sitios web y enseñando a otras personas a hacer lo mismo.
    </p>

    <p>
      Echa un vistazo a estos fantásticos juegos web en
      <a href="https://neal.fun/">Neal.fun</a>!
    </p>

    <h2>Juegos de mesa favoritos</h2>

    <ul>
      <li>Dungeons & Dragons</li>
      <li>Risk</li>
      <li>Pandemic</li>
    </ul>

    <h2>Cómo hacer un sitio web</h2>

    <ol>
      <li>Crear un archivo HTML</li>
      <li>Escribir algo de HTML en él</li>
      <li>Abrirlo en el navegador web</li>
    </ol>
  </body>
</html>
```

### Actualizar su página en la web

Estos cambios se ven bastante bien. Publiquemos esta página al mundo. Visite [su panel de Neocities](https://neocities.org/dashboard). Verá los archivos iniciales mas el archivo `index.html` que subió en el capítulo 1 de este libro. Para hacer las cosas algo más límpias borraré las imágenes PNG y el archivo CSS que ya estaban allí inicialmente.

![Captura de pantalla del panel de Neocities. En la cabecera se lee "My Cool Website" con la URL "blakewatson.neocities.org" debajo. Muestra los archivos utilizado y una lista de dos archivos, "index.html" y "not_found.html," con opciones para editarlos o eliminarlos.](imagenes/add-content-6_es.webp)

Ahora haga clic en el botón de _Subir_ o simplemente arrastre sus archivos actualizados (el index y la imagen) a la lista de archivos.

Una vez hecho eso, haga clic en el enlace de su sitio web en la parte superior del panel. Ese es su sitio web EN VIVO recientemente actualizado, que creó desde cero. ¡Qué genial!

![Captura de pantalla de un navegador web visitando "La página web de Victorhck" (la misma web que anteriorment). La URL original victorhck.neocities.org. La página tiene una sección con los juegos de mesa preferidos, incluyendo Dungeons & Dragons, Risk, y Pandemic, e instrucciones de cómo realizar una página web.](imagenes/add-content-7_es.webp)

<center>-#-</center>

<a id="Cap3">
## Intermedio: actualizar tu editor de texto

Ha recorrido un largo camino. Tomémonos un segundo para apreciar que abrió un editor de texto simple y creó un sitio web increíble escribiendo código HTML. ¡Así se hace!

Hablando de editores de texto simples, mantener todo el texto con una buena sangría en HTML puede resultar molesto. También puede resultar complicado distinguir el código HTML de nuestro contenido escrito.

![Una ventana de un editor de texto mostrando código HTML con "La web de Victorhck". La página contiene un encabezado, la etiqueta de una imagen con la fuente "espacio.jpg" y un texto alternativo (como este) "Fotografía del espacio con estrellas y polvo de estrellas," y secciones sobre aficiones y temas de enseñanza que utiliza varios elementos del código HTML.](imagenes/code-editor-1_es.webp)

No es terrible, pero podemos hacerlo mejor. Descarguemos un editor diseñado para escribir código.

---

**Nota del traductor**

En este ejemplo estoy usando Linux y recomiendo utilizar siempre software libre. El editor [Kate](https://kate-editor.org/es/get-it/) de KDE serviría para esta tarea. Pero los pasos que vamos a ver a continuación pueden servir para todos los sistemas operativos Mac, Windows o Linux.

---

### Descargar Visual Studio Code

Visite el siguiente enlace [https://code.visualstudio.com/](https://code.visualstudio.com/). Este editor de código es de Microsoft pero funciona no solo en Windows, también en Mac y Linux. Puede realizar muchas tareas, pero lo usaremos de manera sencilla para este libro.

No deje que la captura de pantalla de la página de inicio le asuste. No necesitamos todas esas funciones avanzadas para lo que estamos haciendo.

Una vez que descargue e instale VS Code, inícielo. Es posible que vea algunas pantallas instructivas, pero luego se le presentará una pantalla como esta:

![Captura de pantalla de la pantalla de bienvenida de Visual Studio Code. La barra lateral incluye opciones como "Explorar," "Buscar," "Control de fuente," "Ejecutar," y "Extensiones." La pantalla principal muestra opciones para "Abrir carpeta..." con tutoriales para comenzar con VS Code y aprender los fundamentos](imagenes/code-editor-2.webp)

### Abrir su proyecto

En la pantalla de bienvenida de VS Code, haga clic en _Abrir carpeta_, y seleccione la carpeta que contiene su proyecto web. Verá los archivos de su sitio web en la barra lateral. Cuando abra el archivo `index.html`, verá el código en una vista agradable con los números de líneas y lo que se llama _resaltado de sintaxis_, las partes del código coloreadas para que sea más sencillo distinguir una partes de otras.

![Captura de pantalla de Visual Studio Code con código HTML para "La web de Victorhck." La barra lateral izquierda muestra los archivos del proyecto. El editor principal muestra el mismo código que antes, pero coloreado para hacer más sencillo distinguir las diferentes partes del código.](imagenes/code-editor-3.webp)

VS Code también ayuda a hacer más fácil la tarea de escribir código. Entiende el código HTML y muchos otros lenguajes de programación. Cuando comienza a escribir, le ofrecerá sugerencias para completar el texto, que puede aceptar haciendo clic o pulsando enter. También colocará el código tabulado de manera automática para hacer una sangría correcta del texto, así no tiene que introducir las tabulaciones o los espacios a mano cada vez que sea necesario.

VS Code abre sus archivos en pestañas. Esto es muy conveniente para cuando más adelante su sitio web tenga múltiples páginas.

---

**Nota**

VS Code permite que las líneas de texto se desplacen fuera del ancho de la página de forma predeterminada. Si prefiere que el texto se ajuste a la siguiente línea, haga clic en _Ver_ Menú y pulse en _Ajuste de palabras_.

---

### Explore cuando esté preparado

Hay muchas cosas interesantes que VS Code puede hacer, pero lo que hemos cubierto aquí es suficiente para empezar. Piense en ello como un Bloc de notas más elegante. Al fin y al cabo, sigue siendo sólo texto en un archivo. Comenzamos nuestro viaje con Notepad o TextEdit para demostrar que se puede crear un sitio web con herramientas simples que ya tiene instaladas en su computadora, sin necesidad de magia ni software costoso.

Dicho esto, el uso de un editor de código hace que el proceso de escritura HTML sea más agradable y manejable. Y cuando esté listo, podrá explorar todas las funciones que ofrece VS Code. También puede probar otros editores de código para ver si le gustan.

Por ahora, ¡volvamos a la tarea de crear nuestro sitio web!

<center>-#-</center>

<a id="Cap4">
## Un sitio web con estilo

Creo que nuestro sitio web es agradable. Su tranquila sencillez resulta acogedora en un mundo lleno de distracciones. Sin embargo, parece muy simple y _sin estilo propio_.

Estamos viendo los estilos predeterminados del navegador: cómo muestra texto e imágenes sin más instrucciones sobre cómo deben verse. Pero la mayoría de los sitios web que visita no tienen este aspecto. Han sido diseñados para tener diferentes estilos. Sus diseñadores han dado instrucciones sobre qué fuentes de texto utilizar, qué colores y qué diseño debe tener la página.

En la tierra del HTML, sólo nos preocupamos con _qué cosas existen_, esto es un encabezado, esta otra cosa es un párrafo, aquí una imagen y así. Para definir _qué aspecto tienen las cosas_ el navegador utiliza un lenguaje pariente del HTML que se llama: _Cascading Style Sheets_, o más conocido por sus siglas en inglés CSS.

Una forma de incluir CSS es utilizando la etiqueta de `<style>` y poner directamente el código CSS en él. Por ejemplo, considera en añadir lo siguiente:

```html
<style>
  body {
    font-family: 'Gill Sans', sans-serif;
  }
</style>
```

Si incluyera este código en algna parte de su sitio web añadiéndolo en el archivo index, eso cambiaría la fuente tipográfica de todo lo que está dentro de la etiqueta `<body>`, es decir, de todo el texto visible de la página. Este conjunto de _reglas_ de CSS dice, “establecer la fuente tipográfica del cuerpo de la web a Gill Sans o, si esa fuente no está disponible, establecerla a cualquier fuente de tipo sans-serif.”

---

**Nota sobre fuentes tipográficas**

Las fuentes de tipo Serif tienen pequeños trazos, llamados _serifs_, que sobresalen un poco de los más grandes. Normalmente la encontrará en libros y periódicos.

Las fuente Sans-serif fonts son aquellas _sin_ serifs y normalmente tienen una forma más simplificada que sus homólogos serif. Son populares en la web y para interfaces de usuario.

`Las fuentes monoespaciadas, de cuyo ejemplo es este párrafo, se parecen al texto de una máquina de escribir. Cada letra ocupa la misma cantidad de ancho, lo cual es útil si deseas alinear las cosas. Son una opción popular para mostrar código informático.`

---

Esa es una forma totalmente válida de utilizar CSS. Pero a menudo encontrará personas que ponen sus reglas de estilo en un archivo separado. Algo similar a `styles.css`. La razón principal para hacerlo es que hace que sea más fácil compartir estilos en varias páginas: le evita copiar y pegar su etiqueta `<style>` por todas y cada una de las páginas que cree.

CSS es un lenguaje muy potente. Todos los sitios web que ve lo utilizan. Todos esos diseños complejos, gran parte de la animación y la ubicación de las imágenes y la tipografía: eso es CSS.

Sin embargo, también existe una curva de aprendizaje para CSS. Y aunque le animo totalmente a que explore CSS, este libro es sobre _HTML_ para personas. Por lo que quiero mantener el foco en el propio HTML. ¡Pero está bien! Podemos usar CSS para hacer que nuestro sitio web se vea bien sin tener que escribir todo nosotros mismos.

---

**Nota**

Si está interesado en aprender más sobre CSS, ¡genial! Tengo un [capítulo extra](#Cap9) al final de este libro que presenta más CSS y enlaces a otros recursos.

---

### Marcos o frameworks CSS

Incluso los desarrolladores web profesionales que conocen CSS utilizarán CSS preescrito como punto de partida. Haremos algo similar. Nos referiremos a estos marcos por su palabra en inglés como , más comunmente utilizada. Algunos frameworks CSS están diseñados para desarrolladores web: incluyen muchos detalles y requieren que escriba su código HTML de una manera particular. Sin embargo, otros frameworks están diseñados para sitios web más simples. Hacen que su HTML se vea bien sin que tenga que hacer mucho trabajo extra. Son los llamados _CSS frameworks sin clase_.

Para nuestros propósitos, eso es perfecto. Usaremos uno llamado [Simple.css](https://simplecss.org/). Pero aquí hay algunos otros que quizá quiera ver. Son similares en espíritu pero con diferentes estilos.

-   [Water.css](https://perma.cc/5936-VK4J)
-   [Sakura](https://perma.cc/F6E4-EU58)
-   [Pico](https://picocss.com/)

Estos harán que su HTML se vea bien y le brindarán un excelente punto de partida para un sitio web básico. ¡Siéntase cómodo usando cosas que otras personas han hecho, porque hay muchas cosas geniales por ahí!

### Simple.css

Le recomiendo que eche un vistazo al sitio web [Simple.css](https://simplecss.org/), en particular a su [página de demostración](https://simplecss.org/demo), ya que le muestra cómo usar diferentes elementos HTML y cómo se ven con Simple. Descarguemos Simple.css.

El [documento Simple.css](https://perma.cc/XA5E-E59Q) nos da algunas formas de empezar, pero para simplificar, le daré directamente la URL del archivo CSS:

-   [https://cdn.simplecss.org/simple.css](https://cdn.simplecss.org/simple.css)

¡No se deje intimidar por todo el código que contiene! No es necesario que lo entienda ahora (ni nunca, en realidad). Solo pulse _Archivo > Guardar página como_ en su navegador (_Command-S_ en macOS o _Control-S_ en Windows) y guarde el archivo en la carpeta de su proyecto de sitio web donde reside el archivo `index.html` junto con la imagen.

Muy bien, lo ha guardado y lo agregaremos a la página pronto. Pero primero, hagamos un poco de limpieza.

### Organizando nuestros archivos

Hasta ahora, sólo tenemos tres archivos: nuestra página web, un archivo de imagen y el archivo `simple.css` que acabamos de descargar. Pero pronto agregaremos más archivos. Vamos a crear un par de carpetas y organicemos las cosas. Queremos que nuestra nueva estructura de archivos se vea así:

-   carpeta `css`
    -   `simple.css`
-   carpeta `imagenes`
    -   `espacio.jpg`
-   `index.html`

Bonito y limpio. Con Visual Studio Code, puede crear archivos y carpetas directamente en la barra lateral. Pase el mouse sobre sus archivos y verá estos botones.

![Captura de pantalla de VS Code con una carpeta llamada 'MY-SITE' resaltada. Dentro de la carpeta, hay dos archivos: 'index.html' y 'espacio.jpg.' Una larga flecha roja apunta al botón de 'Nueva carpeta' en laesquina superior derecha del editor.](imagenes/vscode-new-folder.webp)

Una vez que realice los cambios, si recarga la página en el navegador, notará que nuestra imagen ya no funciona. Observe cómo el navegador vuelve a mostrar el texto `alt` que escribimos en lugar de la imagen.

![Captura de pantalla de "La web de Victorhck." Incluye secciones, una breve declaración sobre el autor, sus juegos de mesa favoritos y una guía sobre cómo crear un sitio web. La página tiene texto negro sobre fondo blanco. Hay una imagen presente pero no funciona correctamente; en su lugar se muestra el texto alternativo de la imagen, "Fotografía del espacio con estrellas y polvo de estrellas."](imagenes/a-website-with-style-1_es.webp)

Esto es debido a que hemos movido el archivo de la imagen `espacio.jpg` a otra ubicación. Ahora está ubicada en una carpeta llamada `imagenes`. Podemos solucionar esto actualizando el valor `src` de la imagen. Vamos a añadir el nombre de la carpeta y una barra inclinada delante del nombre del archivo. Esa es la ruta donde irá a buscar la imagen.

```html
<img src="imagenes/espacio.jpg" alt="Fotografía del espacio con estrellas y polvo de estrellas.">
```

Cuando necesitamos proporcionar la ubicación de archivos en nuestro sitio web, ya sea un enlace a otra página o la ubicación de una imagen, podemos proporcionar lo que se llama una _URL relativa_.

Cuando está en la página `index.html`, puede pensar como en la ubicación actual o punto de partida. Si quiere referenciar una imagen, necesita decirle al navegador dónde encontrarla. Una URL relativa es una forma de hacer eso. Describe cómo ir "desde aquí hasta allí” por decirlo así.

De manera similar a cómo funciona una URL en su navegador, se utilizan barras diagonales para separar niveles en la URL. La URL `imagenes/espacio.jpg`, significa “busca una carpeta llamada `imagenes` en el nivel actual, y dentro de ella, busca un archivo llamado `espacio.jpg`.”

### Añadir Simple.css a nuestra página web

Podemos añadir una _hoja de estilo_ de manera similar a como hemos añadido la imagen. Utilizaremos una etiqueta `<link>` para vincular el archivo CSS. La pondremos dentro de la etiqueta `<head>`.

```html
<head>
  <title>La web de Victorhck</title>
  <meta charset="utf-8">

  <link rel="stylesheet" href="css/simple.css">
</head>
```

La etiqueta `<link>` es _de auto cierre_, de manera similar a la etiqueta `<a>` que vimos anteriormente, no necesita una etiqueta de cierre. Necesitamos darle dos _atributos_. `rel` Especifica la relación que tiene el archivo que estamos vinculando con nuestra página web. Los archivos CSS se llaman hojas de estilo o _stylesheets_ entonces proporcionamos eso como la relación. El atributo `href` es donde especificamos el archivo, incluyendo la ruta de la carpeta.

---

**Nota**

Lo que la gente normalmente llama "enlaces" en una página web (texto o imágenes en los que se puede hacer clic) se crean con la etiqueta `<a>`, como hemos visto anteriormente. Por lo general, se refieren a un destino al que navegar cuando se hace clic en él.

La etiqueta `<link>` especifica un archivo que queremos vincular a nuestra página y cuál es la relación de ese archivo. Lo estamos usando para conectar una hoja de estilo. Otra relación típica es definir un icono para el sitio, por ejemplo.

---

Así, nuestro sitio web se transforma. Ahora vemos una página centrada, texto más grande y una fuente sans-serif.

![Captura de pantalla de "La web de Victorhck" con un estilo actualizado utilizando Simple.css. La tipografía ha cambiado: El título ahora está en negrita y más grande, creando un encabezado más destacado. La imagen, ya se muestra correctamente, mostrando una fotografía de un espacio estrellado. El texto está más estructurado visualmente con un mejor espaciado, y secciones claramente definidas con encabezados en negritas para "los juegos de mesa favoritos" y "Cómo hacer un sitio web." El diseño general parece más limpio y organizado con una legibilidad mejorada.](imagenes/a-website-with-style-2_es.webp)

### Añadir un encabezado, un pie y contenido principal

Podemos ver que el archivo Simple.css tuvo efecto inmediato. Pero las cosas se verán aún mejor una vez que agreguemos algunas secciones a nuestro sitio web que Simple.css espera: un encabezado o `<header>` para el título del sitio web y `<main>` para el contenido principal. No los usamos antes (no son obligatorios), pero usarlos es una buena práctica.

Y esto es totalmente opcional, pero podríamos agregar también un pie de página o `<footer>` ya que estamos metidos en la tarea. A veces, la gente pone en él información de derechos de autor o información relacionada con el autor o la licencia de la página. A veces, las personas tienen pies de página grandes con muchos enlaces a cosas. A veces, es sólo su nombre. Lo mantendré simple, pero puede agregar aquí lo que quiera.

Entonces pondremos el nombre de nuestro sitio web en una etiqueta `<header>` y nuestro contenido principal en una etiqueta `<main>`. Después añadiremos una etiqueta `<footer>` con un poco de información.

```html
<body>
  <header>
    <h1>La web de Victorhk.</h1>
  </header>

  <main>EL CONTENIDO DE LA PÁGINA IRÁ AQUÍ</main>

  <footer>
    <p>Hecho con ❤️ y ☕️ por Victorhck.</p>
  </footer>
</body>
```

Después de estos ajustes, el título de nuestro sitio web tiene un estilo especial y los párrafos y listas están espaciados de manera más apropiada.

![Captura de pantalla de "La web de Victorhck." con mejoras adicionales en el estilo. La página ahora incluye un encabezado claro en la parte superior con un color de fondo claro, lo que hace que el título destaque más. Se ha mejorado el espacio entre las secciones para una mejor legibilidad y se ha agregado un nuevo pie de página en la parte inferior que contiene el texto. Este pie de página proporciona un toque personalizado. El diseño general se siente más estructurado y visualmente equilibrado.](imagenes/a-website-with-style-3_es.webp)

---

**Nota**

Si lo sigue y nota que su sitio web tiene un fondo oscuro con texto claro, ¡está bien! Simple.css reconoce si usted (el visitante del sitio) tiene su sistema en modo oscuro y, de ser así, utiliza un tema oscuro para el sitio web. Para anular este comportamiento, consulte el capítulo extra [Personalizando Simple.css](#Cap11).

---

### Vamos a actualizar el sitio web

¡Pongamos nuestras novedades en línea! En Neocities, no puede cargar carpetas usando el botón de carga. Debe crear la carpeta en el panel haciendo clic en "Nueva carpeta o New Folder, " o puede arrastrar la carpeta desde su computadora a la zona donde están los archivos en el panel.

![Captura de pantalla del panel de  Neocities para "La web de Victorhck." La página muestra opciones de administración de archivos, incluida la carga de archivos, la creación de archivos nuevos y carpetas nuevas. La URL de la página web de victorhck y las opciones de edición están visibles, resaltadas por una flecha roja que apunta al botón "Nueva carpeta".](imagenes/a-website-with-style-4_es.webp)

Probablemente sea más fácil arrastrar las carpetas, pero si las crea manualmente, deberá abrir cada carpeta y cargar su contenido. Una vez creada una carpeta, puede pasar el ratón sobre ella para ver las opciones. Querrá hacer clic en "Administrar" para abrir la carpeta. Desde allí, puede hacer clic en "Cargar" para cargar los archivos apropiados en esa carpeta.

Mueva archivos existentes cambiándoles el nombre. Por ejemplo, si quiero mover `espacio.jpg` En la carpeta de imágenes, puedo hacer clic en "Cambiar nombre" e incluir la carpeta en la ruta: `imagenes/espacio.jpg`.

![Una ventana emergente con las opciones "Rename / Move" muestra la ruta de un archivo "imagenes/espacio.jpg" siendo editado.](imagenes/a-website-with-style-5.webp)

Es engorroso pero no tan malo. Cualquiera que sea la forma en que lo haga, asegúrese de que los archivos en Neocities coincidan con los que tienes en tu computadora.

<center>-#-</center>

<a id="Cap5">
## Añadir una página Acerca de

Para el resto de este libro, vamos a expandir nuestra página personal de la que ya hemos sentado las bases, en un sitio web completo con múltiples páginas e incluso un blog. El ejemplo continuará siendo **La web de Victorhck**, y el contenido será relacionado conmigo para el ejemplo. Usted puede personalizar el contenido a su gusto para que se adapte a lo que quiere mostrar en su propio sitio web.

Si no quiere crear una página web personal y prefiere hacerlo sobre otra temática, ¡eso también es genial! Los conceptos que tratamos se aplican a todo tipo de sitios web, así que puede seguirlos y adaptarlos según lo vea necesario.

Si quiere echar un vistazo de cómo es el resultado de lo que estamos construyendo, puede hacerlo en la web de ejemplo en [esta web de Victorhck](https://victorhck.neocities.org/).

Tiene las siguientes páginas y características:

-   Un encabezado con botones de navegación
-   Un blog con tres artículos
-   Una página de Acerca de con una fotografía
-   Un currículum digital
-   Una página divertida con vídeos de YouTube incrustados

Incluiré muchos ejemplos del código en los próximos capítulos, pero también puede ir [al repositorio](https://gitlab.com/victorhck/htmldemo) que contiene el código de la página de ejemplo y ver el código fuente de cualquier página como referencia en cualquier punto.

### Las páginas son solo archivos a los que usted enlaza

Crearemos una nueva página en nuestro sitio creando un nuevo archivo. Crearemos el archivo `about.html` junto con `index.html`. Para ahorrar algo de escritura, copie todo el contenido de `index.html` y péguelo en `about.html`.

Y ahora, limpiémoslo un poco. Eliminaré el encabezado "Cómo crear un sitio web" y el párrafo con el enlace a neal.fun. Esta página debería ser sobre mí. Hablando de eso, también cambiaré la imagen a una foto mía (si no se siente cómodo usando una foto suya, puede utilizar cualquier otra imagen que quiera).

Ampliaré el contenido añadiendo un par de párrafos. Este también es un excelente lugar para proporcionar cualquier información de contacto que desee. Agregaré un enlace a mi cuenta de Mastodon (con un emoji de elefante).

```html
<p>🐘 <a href="https://mastodon.social/@victorhck">Puedes contactarme en Mastodon</a></p>
```

Recuerde, un enlace es una etiqueta `<a>`. Se puede hacer clic en cualquier texto que envuelva la etiqueta. Luego proporciona el _atributo_ `href`, que es el destino del enlace, normalmente una URL.

---

**Selector de Emojis**

Para abrir el selector de emojis:

-   En Windows y en el entorno Plasma de KDE, pulse la tecla Windows + el punto (`.`)
-   En macOS, pulse `fn` + `e`.

---

Este es mi código dentro de la etiqueta `<body>`.

```html
<header>
  <h1>Acerca de Victorhck</h1>
</header>

<main>
  <img src="imagenes/victorhck.jpg" alt="Fotografía de mí, agachado detrás de un viejo ordenador Amstrand 128K. No se me ve la cara.">

  <p>
    Mi nick es Victorhck. Soy un aficionado al software libre y me gusta difundir lo bueno de esta filosofía. Y usuario de GNU/Linux desde 2011.
  </p>

  <p>
    Participo en varios proyectos en la web donde traduzco y ayudo a otras personas. Tengo un blog personal donde escribo tutoriales y difundo noticias relacionadas con GNU/Linux y el software libre. Me gusta el chocolate negro.
  </p>

  <p>🐘 <a href="https://mastodon.social/@victorhck">Puedes contactarme en Mastodon</a></p>

  <h2>Juegos de mesa favoritos</h2>

  <ul>
    <li>Dungeons & Dragons</li>
    <li>Risk</li>
    <li>Pandemic</li>
  </ul>
</main>

<footer>
  <p>Hecho con ❤️ y ☕️ por Victorhck.</p>
</footer>
```

Y así es como quedaría.

![Captura de una página Acerca de "Victorhck". La cabecera muestra "Acerca de Victorhck." Más abajo una foto mía detrás de un viejo Amstrand 128K que me tapa la cara. El texto menciona mis aficiones y un enlace a mi cuenta de Mastodon. Una sección titulada "Mis juegos de mesa favoritos" lista estos tres "Dungeons & Dragons," "Risk," y "Pandemic." TEl pie de página dice "Hecho con ❤️ y ☕ por Victorhck."](imagenes/adding-an-about-page-1_es.webp)

¡Sorpresa, ese soy yo! Esto parece una página Acerca de adecuada. Bueno, no hay mucha información personal, pero sirva como ejemplo. Por favor, siéntase libre de escribir todo lo que quiera en esta página sobre usted o el proyecto sobre el que trate su página web.

### Navegando entre páginas

Ahora tenemos una página Acerca de, pero necesitamos una forma de navegar entre nuestras dos páginas. Necesitamos un menú de navegación o nav. Un menú de navegación es solo una lista de enlaces. A Simple.css parece gustarle que el menú de navegación esté encima del encabezado, así que lo haré, aunque podría colocarlo debajo.

HTML tiene una etiqueta `<nav>` justamente para este propósito. Vamos a poner dos enlaces en nuestro menú de navegación. Uno para la página principal y otro para la página Acerca de.

```html
<header>
  <nav>
    <a href="index.html">Inicio</a>
    <a href="about.html" aria-current="page">Acerca de</a>
  </nav>

  <h1>Acerca de Victorhck</h1>
</header>
```

Dado que esta es actualmente la página Acerca de, agregué un atributo especial al enlace. ARIA significa Aplicaciones de Internet enriquecidas accesibles. Podemos hacer que nuestro sitio sea más accesible agregando el atributo `aria-current="page"`. Hace un par de cosas por nosotros.

-   Hará que nuestra página sea más accesible para tecnologías de asistencia como lectores de pantalla.
-   Simple.css diseñará el enlace de manera diferente para que sea fácil saber en qué página estamos.

![Captura de pantalla mostrando la sección superior de la página "Acerca de Victorhck" con los botones de navegación. La navegación incluye "Inicio" y "Acerca de," Con el botón "Acerca de" resaltado indicando que es la página actual. El encabezado "Acerca de Victorhck" es mostrado en negrita debajo de la barra de navegación.](imagenes/adding-an-about-page-2_es.webp)

Agreguemos el mismo menú de navegación a la página de inicio. Abra el archivo `index.html` y añada el menú como lo hicimos en la página Acerca de. Dado que esta es la página de inicio, debemos poner el atributo `aria-current` en el enlace de Inicio.

```html
<header>
  <nav>
    <a href="index.html" aria-current="page">Inicio</a>
    <a href="about.html">Acerca de</a>
  </nav>

  <h1>La web de Victorhck</h1>
</header>
```

¡Cárgalo en el navegador y maravíllese con su sitio web de varias páginas! Clic, clic, clic…

### Limpieza de la página de inicio

Dado que ahora tenemos una página Acerca de, parte del contenido de nuestra página de inicio es redundante. Algo de esto está en la página Acerca de. Eliminaré el texto de la biografía, el enlace de Neal.fun y la lista de juegos de mesa. Mantendré la imagen del espacio y agregaré un pequeño párrafo de bienvenida. También podría conservar la lista de "cómo crear un sitio web".

Aunque, hablando de la imagen del espacio, hagámosla más interesante. Quiero ponerle un título a esta imagen y un enlace a donde la obtuve. Podemos marcar aún más una imagen envolviéndola en una etiqueta `<figure>` e incluyendo un `<figcaption>`.

```html
<figure>
  <img src="imagenes/espacio.jpg" alt="Fotografía del espacio con estrellas y polvo de estrellas.">

  <figcaption>
    El espacio es genial. <a href="https://unsplash.com/photos/blue-and-purple-galaxy-digital-wallpaper-E0AHdsENmDg">Fuente de la imagen </a>
  </figcaption>
</figure>
```

El contenido `<principal>` de mi página web ahora tiene este aspecto.

```html
<main>
  <figure>
    <img src="imagenes/espacio.jpg" alt="Fotografía del espacio con estrellas y polvo de estrellas.">

    <figcaption>
      El espacio es genial. <a href="https://unsplash.com/photos/blue-and-purple-galaxy-digital-wallpaper-E0AHdsENmDg">Fuente de la imagen</a>
    </figcaption>
  </figure>

  <p>
    ¡Bienvenidos y bienvenidas a mi sitio web! Aquí puede encontrar más información sobre mí, leer mis publicaciones del blog muy interesantes y nada artificiales, y ver algunos de los pasatiempos divertidos que tengo. No pasará mucho tiempo hasta que se pregunte qué hechicería he usado para crear esta alucinante experiencia basada en la web. La respuesta es HTML.
  </p>

  <h2>Cómo hacer un sitio web</h2>

  <ol>
    <li>Crear un archivo HTML</li>
    <li>Escribir algo de HTML en él</li>
    <li>Abrirlo en el navegador web</li>
  </ol>

  <p class="notice">
    <strong>¿Quiere aprender cómo hacer un sitio web como este?</strong><br> Eche un vistazo a esta web <a href="https://victorhck.gitlab.io/htmlparapersonas/">HTML para personas</a>. Está hecho para todo el mundo y le enseña cómo crear una página web de una manera amigable y accesible.
  </p>
</main>
```

¿Qué es ese `class="notice"`? Puede obtener más información sobre las clases en los capítulos adicionales de CSS al final de este libro. Pero, en resumen, esto activará algunos estilos proporcionados por Simple.css para crear un pequeño cuadro con algo de texto.

![Captura de pantalla de "la web de Victorhck." La cabecera de la web incluye botones de navegación para "Inicio" (resaltado) y "Acerca de." Más abajo aparece una imagen del espacio con estrellas. El texto de introducción da la bienvenida a la persona que visita la web, mencionando los artículos del blog en un tono desenfadado sobre el uso de HTML. Una sección titulada "Cómo hacer un sitio web" muestra tres pasos: "Crear un archivo HTML," "Escribir algo de código en él," y "Abrirlo en el navegador web." Una caja resaltada anima al visitante a echar un vistazo a la serie de tutoriales "HTML para personas".](imagenes/adding-an-about-page-3_es.webp)

### Actualizar el sitio web

Puede actualizar su sitio web con estos últimos cambios realizados si lo desea. También está bien seguir trabajando en ello en su computadora. Muchos sitios web se construyen de esa manera: la persona trabaja en su sitio web en su propia computadora hasta que termina y luego lo publica. Pero muchas personas también crean su sitio web en público y lo actualizan a medida que avanzan.

Si desea actualizarlo, regrese a su panel de Neocities y cargue ambos archivos `index.html` y `about.html` ya que esos archivos han cambiado. Si agregó alguna imagen, debe hacer clic en la carpeta de imágenes en Neocities y subirla allí (o puede arrastrar la carpeta de `imagenes` a la zona de archivos de Neocities, lo que reemplazará todo el contenido de la carpeta).


<center>-#-</center>

<a id="Cap6">
## Añadir un blog

Los blogs son una parte importante de la web. Probablemente haya oído hablar de varias plataformas de blogs populares como WordPress, Tumblr o Blogger. Y hay un montón más de plataformas de [blogueo más pequeñas e independientes](https://perma.cc/K3PV-JL9S).

Pero no _necesita_ ninguna de estas plataformas para tener un blog. Un blog no es más que una serie de artículos en orden cronológico (normalmente en orden _inverso_, es decir las más recientes primero). ¡Podemos hacer todo eso simplemente con HTML!

Añadiré tres artículo al blog que vamos a crear. No pondré todo el código en este capítulo ya que sería excesivo. Puede echar un vistazo [al sitio de prueba](https://victorhck.neocities.org/blog/) y ver los artículos completos o al [código de esa web](https://gitlab.com/victorhck/htmldemo). Pero le mostraré cómo estructurar los archivos y revisaré algunas de las diferentes etiquetas HTML que utilizaré.

### Crear el blog de inicio

Siga los pasos de `sitename.neocities.org/blog` para tener disponible también usted su propio blog dentro de su sitio web.

1.  Cree una carpeta llamada `blog`, dentro de ella cree un archivo llamado `index.html`.
2.  Copie el contenido de una de sus páginas y péguelo dentro de este nuevo y vacío archivo llamado `index.html`.
3.  Cambie el texto dentro de la etiqueta `<h1>` a “Blog,” “Mi Blog,” o con cualquier nombre que quiera llamarlo.
4.  Cambie el `<título>` para cambiar el texto que aparecerá en la pestaña del navegador web al visitarlo. Por ejemplo, “Blog - de la web de Victorhck.”
5.  Limpie el contenido principal, así tendrá una etiqueta `<main>` vacía. Añadiremos contenido más adelante.

Vamos a abrirlo en el navegador para ver el aspecto que tiene.

![Captura de pantalla del "Blog" de la página de Victorhck. La página tiene un aspecto minimalista debido a que se han roto la referencias al archivo de estilo. Aparece un texto simple, sin estilo en negro sobre un fondo blanco. El encabezado enlaces al "Inicio" y "Acerca de" en texto azul y subrayado, indicando el estilo predeterminado del navegado. El título principal "Blog" está en negrita y en grande, pero la apariencia general es la falta de diseño de anteriores páginas.](imagenes/adding-a-blog-1_es.webp)

¿¡Qué ha pasado, todo se ha roto!? Tiene que ver con la estructura de archivos. Mire nuestra etiqueta de `<link>`, donde añadimos la hoja de estilos Simple.css.

```html
<link rel="stylesheet" href="css/simple.css">
```

Está buscando el archivo `css/simple.css` pero no puede encontrarlo ¿Por qué? La ruta que le dimos es _relativa_ al archivo actual. El archivo actual está en la carpeta `blog`, así que busca en `blog/css/simple.css`, que no existe.

Así que, ¿Cómo hacemos referencia a archivos que no están en la carpeta actual? Podemos utilizar la siguiente sintaxis `..`.

```html
<link rel="stylesheet" href="../css/simple.css">
```

Con los dos puntos `..` le estamos diciento "sube un nivel en la estructura de carpetas" y ahí busca css/simple.css.”

![Captura de pantalla de la página del "Blog" de la web de Victorhck con el estilo corregido. La página ahora muestra una cabecera ligeramente coloreada con botones redondeados para "Inicio" y "Acerca de," mejorando la navegación. El título principal "Blog" está centrado y en negrita y se nota una estructura visual del contenido. El pie de página está centrado, tiene una fina línea por encima para separarlo del contenido principal.](imagenes/adding-a-blog-2_es.webp)

¡Esto ya está mejor! Ahora vamos a actualizar la barra superior de navegación. Ya que la página de inicio y en la de Acerca de no se encuentran en la carpeta actual, necesitaremos utilizar la misma sintaxis que en el caso anterior, añadiendo los dos puntos `..` para enlazarlos.

```html
<nav>
  <a href="../index.html">Inicio</a>
  <a href="index.html" aria-current="page">Blog</a>
  <a href="../about.html">Acerca de</a>
</nav>
```

También deberá actualizar la navegación en las otras páginas para incluir un enlace al blog. Por ejemplo, la navegación de la página de inicio debería verse así.

```html
<nav>
  <a href="index.html" aria-current="page">Inicio</a>
  <a href="blog/index.html">Blog</a>
  <a href="about.html">Acerca de</a>
</nav>
```

---

**Nota**

Dado que abrimos los archivos de nuestro sitio web directamente en el navegador, usamos _URL relativas_ para formar enlaces a otras páginas y archivos. En un próximo capítulo, aprenderemos cómo [poner en marcha un servidor web local](#Cap8) y cómo hacerlo nos permitirá utilizar _URL absolutas_, que son más sencillas y directas.

---

### Crear el primer artículo

Voy a escribir una publicación tonta sobre cómo enseñar HTML a un gato. Crearé un archivo llamado `2024-04-12-whiskers.html` dentro de la carpeta del `blog`. Puede nombrar el archivo de publicación de tu blog como quiera. Lo bueno de incluir la fecha es que, a medida que cree más publicaciones, aparecerán ordenadas en el sistema de archivos de su computadora.

Como punto de partida, copiaremos el contenido de `blog/index.html` en nuestro nuevo archivo. Cambiaré `<h1>` (y el `<título>`) para que sea el nombre de mi artículo, "Cómo le enseñé a mi gato a crear un sitio web con HTML". También modificaré la navegación. No estamos en la página de listado del Blog, por lo que es inexacto decir `aria-current="page"` en el enlace de navegación del blog. Pero _está_ dentro de la sección del Blog de nuestro sitio web. Así que cambiaré el atributo a algo más general `aria-current="true"`. Esto es **únicamente para páginas de artículos individuales dentro de los artículos del blog**.

```html
<nav>
  <a href="../index.html">Inicio</a>
  <a href="index.html" aria-current="true">Blog</a>
  <a href="../about.html">Acerca de</a>
</nav>
```

Añadiré un enlace para regresar al blog al final del artículo. Ya que estamos en la carpeta del `blog`, apuntar al archivo `index.html` es todo lo que necesitamos para regresar al inicio del blog.

```html
<a href="index.html" class="button">&larr; Regresar al blog</a>
```

La parte `class="button"` es un estilo que Simple.css hace que un enlace de texto parezca un botón. El código `&larr;` es un código especial llamado una _entidad HTML_. Se utilizan para codificar caracteres especiales. Este en particular es una _flecha hacia la izquierda_. Puede ver una [lista de otras entidades en este enlace](https://perma.cc/BEA6-LF46).

Añadiré tres artículos al blog fechados con unos pocos días de separación entre ellos, solo como ejemplo. cuando termine tendré estos artículos.

-   [Cómo le enseñé a mi gato a hacer un sitio web con HTML](https://victorhck.neocities.org/blog/2024-04-12-whiskers)
-   [La vez que construí un sitio web para extraterrestres](https://victorhck.neocities.org/blog/2024-04-15-aliens)
-   [Por qué el chocolate negro es lo mejor que existe](https://victorhck.neocities.org/blog/2024-04-20-chocolate)

Mi estructura de archivos tendrá un aspecto como este:

-   `blog`
    -   `2024-04-12-whiskers.html`
    -   `2024-04-15-aliens.html`
    -   `2024-04-20-chocolate.html`
    -   `index.html`
-   `css`
    -   `simple.css`
-   `imagenes`
    -   `victorhck.jpg`
    -   `espacio.jpg`
-   `about.html`
-   `index.html`

### Dando formato al texto

Vamos echar un vistazo a algunas de las etiquetas que puede utilizar en sus artículos del blog y también en otras páginas.

Para las negritas o cursivas, podemos utilizar las etiquetas `<strong>` y `<em>`, respectivamente.

```html
<p>
  ¡Después de tres días, <strong>mi gato Whiskers puede crear páginas web</strong> mejor que <em>yo</em> lo puedo hacer!
</p>
```

Que daría este resultado.

![Captura de pantalla de un texto HTML renderizado que muestra lo siguiente en negrita : "Whiskers ahora puede crear páginas web"](imagenes/adding-a-blog-3_es.webp)

### Bloque de citas

Podemos utilizar la etiqueta `<blockquote>` para citar una frase de otra persona, un libro, otro sitio web o incluso una cita propia.

```html
<blockquote>
  "HTML es <strong>elemental</strong> mi querido Watson."<br>
  <cite>&mdash; Whiskers, probablemente</cite>
</blockquote>
```

Aquí estoy utilizando `<strong>` para dar un énfasis extra a la cita del gato. Estoy utilizando la etiqueta `<cite>` para mostrar el origen de la cita. La etiqueta `<br>` _se cierra sola_, por lo que no utiliza otra etiqueta de cierre, crea un salto de línea, que mueve el elemento de `<cite>` en la línea siguiente. He utilizado también otro caracter especial, `&mdash;`, para crear un [_guión medio_](https://practicaltypography.com/hyphens-and-dashes.html).

![Un bloque de cita mostrado en el navegador web. La cira es: "HTML es elemental mi querido Watson." la palabra "elementary" está en cursiva y también en negrita. También se muestra una pequeña barra vertical en azul a la izquierda de la cita, añadiendo un énfasis visual. Debajo de la cita, se nombra al autor de la cita, un gato llamado Whiskers "— Whiskers, probablemente" que es mostrado en una fuente más pequeña y alineado el texto a la izquierda, creando un efecto visual de atribución de la cita al gatito.](imagenes/adding-a-blog-4_es.webp)

Los bloques de citas están normalmente creados como bloques de texto con una sangría diferente, a menudo con un borde o fondo de color para dar un énfasis extra. La imagen anterior muestra cómo Simple.css le da ese estilo (a menos que indique lo contrario, todas las imágenes del ejemplo están con el estilo que les proporciona Simple.css).

### Resumen: encabezados y listas

Ya tratamos estos dos elementos de manera rápida en el capítulo 2, [Añadir contenido a su sitio web](#Cap2), pero creo que está bien recapitular un poco. Los artículos de nuestro blog ya utilizan el encabezado principal `<h1>`, pero si quiere escribir artículos que necesitan más encabezados, se puede hacer sin problema.

Los encabezados en HTML son jerárquicos, esto significa que el encabezado `<h2>` debería ir detrás del encabezado de tipo `<h1>`, el encabezado de tipo `<h3>` debería seguir al encabezado `<h2>`, y así sucesivamente. Técnicamente, HTML ofrece seis niveles de encabezado `<h1>` hasta `<h6>`. Pero la moderación aquí es la clave. Pregúntese si _realmente_ necesita tantos niveles de encabezado en su página web para hacerla sencilla de comprender. Mi consejo es utilizar tres niveles de encabezado como máximo o incluso menos.

Y por supuesto, también tenemos las listas, que las vimos en el capítulo 2 y que vamos a repasar a continuación. Tenemos dos tipos de listas, una que llamamos _sin orden_ porque los elementos no están numerados y la lista _ordenada_ porque a los elementos los precede un número.

Este es un ejemplo de lista _sin orden_ en la que utilizamos la etiqueta `<ul>` para englobar a todos los elementos de la lista y la etiqueta `<li>` para cada _elemento de la lista_. Estas son las [4 libertades del software libre:](https://www.gnu.org/philosophy/free-sw.es.html#four-freedoms)

```html
<ul>
  <li>La libertad de ejecutar el programa como se desee, con cualquier propósito (libertad 0).</li>
  <li>La libertad de estudiar cómo funciona el programa, y cambiarlo para que haga lo que se desee (libertad 1). El acceso al código fuente es una condición necesaria para ello.</li>
  <li>La libertad de redistribuir copias para ayudar a otros (libertad 2).</li>
  <li>La libertad de distribuir copias de sus versiones modificadas a terceros (libertad 3).</li>
</ul>
```

Que tendrá este aspecto:

-   La libertad de ejecutar el programa como se desee, con cualquier propósito (libertad 0).
-   La libertad de estudiar cómo funciona el programa, y cambiarlo para que haga lo que se desee (libertad 1). El acceso al código fuente es una condición necesaria para ello.
-   La libertad de redistribuir copias para ayudar a otros (libertad 2).
-   La libertad de distribuir copias de sus versiones modificadas a terceros (libertad 3).

Y aquí veremos un ejemplo de lista _ordenada_ (con algunos puntos en negrita para darles énfasis).

```html
<ol>
  <li>
    <strong>Felicidad en cualquier parte:</strong> Puede comer chocolate en cualquier sitio: en el trabajo, en el parque en casa.
  </li>
  <li>
    <strong>Mejora instantánea del estado de ánimo:</strong> Comiendo con prudencia una pequeña porción de chocolate le hará sentirse mejor. Científicamente probado*. (*La verdad es que creo que no, pero es cierto.)
  </li>
  <li>
    <strong>Creatividad sin límites:</strong> Diferentes formas, con otros alimentos. Es una delicia probar nuevas combinaciones de chocolate negro.
  </li>
</ol>
```

Así es como se ve.

1.  **Felicidad en cualquier parte:** Puede comer chocolate en cualquier sitio: en el trabajo, en el parque o en casa.
2.  **Mejora instantánea del estado de ánimo:** Comiendo con prudencia una pequeña porción de chocolate le hará sentirse mejor. Científicamente probado\*. (\*La verdad es que creo que no, pero es cierto.)
3.  **Creatividad sin límites:** Diferentes formas, con otros alimentos. Es una delicia probar nuevas combinaciones de chocolate negro.

Puede incluso crear listas _anidadas_ como esta.

```html
<ul>
  <li>
    Primer punto principal
    <ul>
      <li>sub punto</li>
      <li>Otro sub punto</li>
    </ul>
  </li>

  <li>
    Segundo punto principal
    <ul>
      <li>sub punto</li>
      <li>Otro sub punto</li>
    </ul>
  </li>
</ul>
```

Que quedaría algo así.

-   Primer punto principal
    -   Sub punto
    -   Otro sub punto
-   Segundo punto principal
    -   Sub punto
    -   Otro sub punto

### Dividir el contenido

Una de las maneras en las que podemos añadir espacio entre los elementos es mediante el uso de la etiqueta `<br>` o con la etiqueta _break_. La etiqueta break, añade un salto de línea. Por ejemplo, veamos este haiku (de [Robert Cole](http://www.npr.org/blogs/thetwo-way/2013/05/02/180532424/send-your-haiku-to-mars-nasa-seeks-poets#comment-882372940)).

```html
<p>
  Un orbe rojo atemporal
  flota perezosamente en el éter
  sin impresionarse por la guerra.
</p>
```

De manera predeterminada, el navegador mostrará todo el texto en una única línea ignorando los espacios en blanco en su HTML.

![Una única línea de texto mostrada en el navegador web: "Un orbe rojo atemporal flota perezosamente en el éter sin impresionarse por la guerra." El texto es mostrado de la manera estándar con una fuente sans serif sin un estilo adicional, y centrado horizontalmente en la página.](imagenes/adding-a-blog-5_es.webp)

Por un lado, esto es algo bueno: significa que podemos formatear nuestro código como queramos sin que nuestros visitantes vean un montón de saltos de línea y sangrías en la página que no pretendíamos. Pero a veces, _queremos_ tener saltos de línea, como en el ejemplo del haiku anterior para que se vea correctamente.

Podemos arreglar nuestro haiku añadiendo un par de etiquetas `<br>`.

```html
<p>
  Un orbe rojo atemporal<br>
  flota perezosamente en el éter<br>
  sin impresionarse por la guerra.
</p>
```

![El haiku anterior ahora se muestra en el navegador web con un formato más natural y saltos de línea al final de cada frase: "Un orbe rojo atemporal flota perezosamente en el éter sin impresionarse por la guerra."](imagenes/adding-a-blog-6_es.webp)

Esto es útil en pequeñas dosis, pero úselo con moderación. La mayoría de las veces, el espacio entre elementos debe controlarse con CSS, aplicando `margin` o `padding`, por ejemplo. Afortunadamente, nuestra hoja de estilo Simple.css tiene un buen espaciado predeterminado. Trataremos sobre el uso de CSS para espacios personalizados en el [capítulo extra](#Cap12) al final del libro.

Otra forma de dividir el contenido manualmente es utilizar una _regla horizontal_, o la etiqueta `<hr>`. Por lo general, tiene el estilo de una línea horizontal. Esto puede resultar útil cuando desea separar contenido, como una nueva sección o una nueva escena, en el caso de una historia. Así es como puede verse.

![Dos párrafos de texto de marcador de posición representados en un navegador web. Los párrafos están separados por una línea horizontal, lo que proporciona una división visual clara. El texto se muestra en una fuente sans-serif estándar, y cada párrafo tiene un espacio entre líneas adecuado, lo que mejora la legibilidad.](imagenes/adding-a-blog-7_es.webp)

---

**Nota**

¿Qué pasa con el texto sin sentido? Es un texto en latín llamado _[lorem ipsum](https://es.wikipedia.org/wiki/Lorem_ipsum)_ que se utiliza a menudo en situaciones de diseño en las que desea ver cómo se ve el texto sin distraerse con lo que dice el texto.

---

### Código y texto preformateado

He estado utilizando estas etiquetas _un montón_ en las páginas que ha estado leyendo en este libro. Considere este párrafo:

```html
<p>
  Al final del primer día, estaba familiarizado con etiquetas básicas como <code>html</code>,
  <code>head</code>, y <code>body</code>. El segundo día, estaba creando párrafos y listas. Al tercer día, ya había pasado a crear impresionantes diseños con <code>article</code> y <code>section</code>.
</p>
```

Que mostrará las partes del texto del código en una fuente monoespaciada y en un color diferente, como esta:

![Un párrafo de texto representado en un navegador web con etiquetas HTML específicas resaltadas en rojo. El texto dice: "Al final del primer día, estaba familiarizado con etiquetas básicas como html, head y body." Las palabras resaltadas "html," "head," y "body" están en rojo con fuente monoespaciada, mientras que el resto del texto permanece en negro, llamando la atención sobre estos términos específicos.](imagenes/adding-a-blog-8_es.webp)

Me ha visto incluir los símbolos menor que (`<`) y mayor que (`>`) en los elementos de mi código en las páginas de este libro (como este, `<a>`). Eso requiere un poco de trabajo extra. Ya que si quiero mencionar una etiqueta `<a>`, no puedo simplemente escribir `<code><a></code>` porque el navegador pensará que estoy creando un enlace literal dentro de la etiqueta `<code>`. Para incluir los símbolos menor que y mayor que (a veces llamados "corchetes angulares"), necesitaremos las entidades HTML `&lt;` y `&gt;`, respectivamente. Eso le indicará al navegador que queremos representar los símbolos reales.

```html
<p>
  Al final del primer día, estaba familiarizado con etiquetas básicas como
  <code>&lt;html&gt;</code>, <code>&lt;head&gt;</code>, y
  <code>&lt;body&gt;</code>. El segundo día, estaba creando párrafos y listas.
  Al tercer día, ya había pasado a crear diseños impresionantes con
  <code>&lt;article&gt;</code> y <code>&lt;section&gt;</code>.
</p>
```

Eso nos mostraría lo siguiente.

![Un párrafo similar al anterior pero con etiquetas HTML rodeadas por corchetes angulares, enfatizando su papel como elementos HTML. El texto dice: "Al final del primer día, estaba familiarizado con etiquetas básicas como html, head y body. El segundo día estaba creando párrafos y listas. Y al tercer día ya había pasado a crear diseños impresionantes con article y section."](imagenes/adding-a-blog-9_es.webp)

Como vimos anteriormente, al representar su contenido, el navegador ignora la mayor parte de los espacios en blanco de su código. Pero a veces desea conservar el espaciado exacto y los saltos de línea. Un ejemplo divertido es el arte ASCII, que es el arte creado con caracteres de texto sin formato.

```
    ___       ___       ___       ___   
   /\__\     /\  \     /\__\     /\__\  
  /:/__/_    \:\  \   /::L_L_   /:/  /  
 /::\/\__\   /::\__\ /:/L:\__\ /:/__/   
 \/\::/  /  /:/\/__/ \/_/:/  / \:\  \   
   /:/  /   \/__/      /:/  /   \:\__\  
   \/__/               \/__/     \/__/
```

Lo anterior debería aparecer como las letras “HTML” usando un efecto 3D. Funciona porque utiliza una fuente monoespaciada y conserva todos los espacios en blanco. ¿Cómo lo hice? utilicé la etiqueta `<pre>`, que es para texto _preformateado_. Úselo así

```html
<pre>
    ___       ___       ___       ___   
   /\__\     /\  \     /\__\     /\__\  
  /:/__/_    \:\  \   /::L_L_   /:/  /  
 /::\/\__\   /::\__\ /:/L:\__\ /:/__/   
 \/\::/  /  /:/\/__/ \/_/:/  / \:\  \   
   /:/  /   \/__/      /:/  /   \:\__\  
   \/__/               \/__/     \/__/
</pre>
```

Si quiere jugar con más arte de texto ASCII, eche un vistazo a este [generador de arte con texto](https://perma.cc/E5NZ-SV56).

### Apartes

La etiqueta `<aside>` es divertida ya que Simple.css lo diseña de una manera interesante. Son útiles para llamadas o _asides_ para el contenido principal. Por ejemplo,incluí un aparte que enumera los ingredientes en mi [artículo del blog sobre el chocolate](https://victorhck.neocities.org/blog/2024-04-20-chocolate).

![Captura de un artículo del blog titulado "Por qué el chocolate es lo mejor," fechado el 20 de abril de 2024. La página presenta un menú de navegación con los siguientes botones "Inicio," "Blog" (resaltado), y "Acerca de". La publicación analiza la alegría y la versatilidad del chocolate, con una lista en el cuadro de la barra lateral. "Ingredientes del chocolate" (cacao, azúcar). El diseño es limpio y está bien espaciado para facilitar la lectura.](imagenes/adding-a-blog-10_es.webp)

Simple.css diseñará el lado como un cuadro redondeado y lo desplazará hacia un lado. Esta es una forma sencilla de agregar notas adicionales o contenido secundario a una página.

### Marcar, tachar, eliminar, insertar

Aquí hay más etiquetas de formato de texto para usted. Utilice `<mark>` para resaltar un texto. Si quiere tachar un texto ~no deseado~, encierre el texto con la etiquetas `<s>`. Si desea mostrar explícitamente las ediciones de un documento, utilice la opción de la etiqueta `<del>` para indicar una eliminación y la etiqueta `<ins>` para mostrar el texto insertado. Por ejemplo, esto es de mi publicación de chocolate.

![Captura de pantalla de texto con formato tachado y subrayado. la frase "son los vegetales" está tachada, y "chocolate" está subrayada enfatizando el reemplazo de "vegetales" con "chocolate" para resaltar una preferencia humorística en la oración.](imagenes/adding-a-blog-11_es.webp)

### Complete la página de índice de nuestro blog

Bien, hemos cubierto una variedad de etiquetas que puedes usar para _marcar_ los diferentes tipos de contenido. Puede tomarse un tiempo y jugar con estos. ¡No hay prisa! Estaré aquí cuando quiera continuar. Una vez que tenga dos o tres publicaciones de blog, pongámoslas en la página principal del blog.

Si abre `blog/index.html`, tiene un aspecto un poco vacío. Lo solucionaremos ahora mostrando el título de cada publicación del blog, la más reciente primero, la fecha de publicación y un resumen de una oración. Al hacer clic en el título de una publicación del blog, el lector debería acceder a ella.

Usemos la etiqueta `<article>` para cada uno porque cada uno representa una composición independiente. Como beneficio adicional, Simple.css los diseñará como tarjetas. Usemos `<h2>` para el título de la publicación del blog, dentro del cual pondremos un enlace (la etiqueta `<a>`). Utilizaremos la etiqueta `time` para la fecha. Usaremos un párrafo normal, o la etiqueta `<p>`, para el resumen. El código final se ve así.

```html
<main>
  <article>
    <h2>
      <a href="2024-04-20-chocolate.html">
        Por qué el chocolate es lo mejor que existe
      </a>
    </h2>
    <p><time datetime="2024-04-20">20 de abril de 2024</time></p>
    <p>
      El chocolate es la comida reconfortante por excelencia debido a su versatilidad.
      variedad, portabilidad, poder para mejorar el estado de ánimo y un sinfín de sabores creativos.
    </p>
  </article>
</main>
```

El enlace en la cabecera llevará un atributo `href` , al destino del enlace. Ya que estamos en la carpeta del `blog`, podemos utilizar el nombre del archivo como destino.

Estamos utilizando la etiqueta `<time>` para proporcionar una versión de la fecha compatible con máquinas. Esto podría ser útil para los motores de búsqueda que buscan en su sitio o admiten posibles funciones del navegador que se basan en fechas. La etiqueta `<time>` toma un atributo llamado `datetime` donde puede proporcionar la [versión legible por máquina.](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time#valid_datetime_values).

Añada un `<article>` como el anterior para cada publicación de blog a la que desee vincular. Terminará con algo como esto.

![Captura de pantalla de una página de listado de blogs con un encabezado que contiene botones de navegación para "Inicio," "Blog" (resaltado), y "Acerca de." El título principal dice "Blog." A continuación se muestran tres vistas previas de publicaciones de blog con títulos en azul. "Por qué el chocolate es lo mejor que existe," "La vez que construí un sitio web para extraterrestres," y "Cómo le enseñé a mi gato a hacer un sitio web con HTML," cada uno con un breve resumen y fecha.](imagenes/adding-a-blog-12_es.webp)

### Una tabla de los elementos (HTML)

¡Uf! Hemos visto bastantes etiquetas y hemos agregado mucho contenido durante este capítulo. Puede haber mucho que recordar. Si alguna vez necesita buscar cómo usar una etiqueta HTML en particular, o si desea ver qué etiquetas HTML están disponibles, consulte esta útil [Referencia de elementos HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) en MDN. [MDN](https://developer.mozilla.org) Es más o menos el manual de usuario oficial de la web. Simplemente busque cualquier etiqueta, atributo o concepto sobre el que desee saber más.

### Actualizar el sitio en vivo (opcional)

Si desea cargar sus cambios en Neocities, siga el mismo proceso que en capítulos anteriores. Arrastre y suelte la carpeta `blog` en la zona de colocación para cargar la carpeta completa a la vez. Dado que actualizó el menú de navegación en todas las páginas, también querrá volver a cargar las páginas Inicio y Acerca de.

Por supuesto, también puede seguir trabajando. _de manera local_ en lugar de cargar su progreso ahora. ¡Usted decide!


<center>-#-</center>

<a id="Cap7">
## Añadir un currículum (o CV)

En los capítulos anteriores, aprendimos cómo agregar todo tipo de contenido a nuestras páginas HTML. Ahora veremos cómo agregar estructura a una página grande de contenido. Realizaremos una página de currículum.

Ahora, un currículum será diferente para diferentes personas. Si está en el mundo académico, puede crear un _curriculum vitae_. Las personas que han trabajado durante muchos años pueden tener un currículum extenso, mientras que los estudiantes en la universidad pueden no tener mucho historial laboral.

No se preocupe si no tienes mucha experiencia. Puede agregar secciones que destaquen su educación, en particular títulos, trabajos en cursos y actividades escolares. O puede concentrarse en el trabajo voluntario o a tiempo parcial que haya realizado.

Otra opción es hacerlo menos como un currículum y más como una cartera de proyectos si eso es más aplicable a usted. Puede incluir cualquier habilidad relevante que tenga (¡como HTML!). Pruebe una búsqueda en la web para obtener consejos sobre currículums. La web está llena de consejos sobre currículums para personas en diferentes momentos de sus carreras.

Pero si no siente que este asunto del currículum es para usted, también está bien. Siéntase libre de tomar las ideas de marcado que exploramos aquí y utilizarlas como quiera. Es su sitio web y es importante que disfrute haciéndolo y aprendiendo un montón durante el proceso práctico que estamos llevando a cabo.

## Crear el archivo del currículum

Creee un archivo de nivel superior de nuestra jerarquía de archivos, llamado `currículum.html`, y copie el contenido de una de las otras páginas de nivel superior en él.

---

**Nota**

Si está utilizando Visual Studio Code, seleccione una de las páginas de nivel superior existentes en la barra lateral, luego cópiela y péguela. Se creará una copia de la página, a la que podrá cambiarle el nombre.

---

Independientemente de cómo cree el archivo, asegúrese de actualizar el `<título>`, `<h1>`, y `<nav>`. En mi caso pondré el nombre en la etiqueta `<h1>` y mis estudios y experiencia debajo en una etiqueta `<p>`.

```html
<header>
  <nav>
    <a href="index.html">Inicio</a>
    <a href="blog/index.html">Blog</a>
    <a href="about.html">Acerca de</a>
    <a href="currículum.html" aria-current="page">Currículum</a>
  </nav>

  <h1>Victorhck</h1>
  <p><em>Aprendiz de todo lo que me interesa</em></p>
</header>
```

### Un documento con secciones

Un currículum a menudo está dividido en secciones, las más comunes son la experiencia, la educación y los conocimientos. HTML tiene la herramienta para crear una sección genérica en un documento, la etiqueta `<section>`. Cada sección debería tener un encabezado [según la documentación](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section).

Cabe la pena destacar que es válido utilizar únicamente encabezados en este caso, si lo desea. Opto por utilizar la etiqueta `<section>` para ofrecer un ejemplo de cómo utilizarla y porque el estilo que da Simple.css a esta etiqueta ofrece un vistoso espaciado y divisores entre las distintas secciones.

Crearé las siguientes secciones. Pero recuerde, que puede añadir o quitar según desee para su caso personal y no es necesario que utilice las mismas que yo o incluso el mismo orden. Siéntase libre de adaptarlo a sus necesidades.

-   Conocimientos
-   Experiencia
-   Proyectos seleccionados
-   Educación

### Conocimientos

Para esta sección, hará un listado de los conocimientos más relevantes, listándolos con pequeños puntos azules. Utilizaré un encabezado de nivel 2 y englobaré todo en una etiqueta `<section>.`

```html
<section>
  <h2>Conocimientos</h2>

  <ul>
    <li>HTML / CSS</li>
    <li>JavaScript</li>
    <li>TypeScript</li>
    <li>Vue</li>
    <li>PHP</li>
    <li>Sass</li>
    <li>Electron</li>
    <li>Sketch</li>
  </ul>
</section>
```

Que se vería así.

![Captura de pantalla de un "Currículum" para Victorhck. El encabezado de la página incluye los botones de nevegación "Inicio," "Blog," "Acerca de," y "Currículum" (resaltado). El título de la página "Victorhck" es mostrado en negrita con un subtítulo "Aprendiz de todo" en texto más pequeño y en cursiva. Debajo del encabezado, una sección titulada "Conocimientos" ofrece una lista de varias tecnologías web y cada elemento precedido de un pequeño punto.](imagenes/adding-a-resume-1_es.webp)

Es una visión clara del listado de conocimientos. Pero a decir verdad, creo que hay un poco de espacio desperdiciado. Estaría mejor si pudiera dividir la lista en dos columnas. No hay una manera estricta en HTML de hacer esto, pero creo que utilizando un poco de CSS podríamos conseguirlo.

Hasta ahora ha visto muchas veces las etiquetas utilizando _atributos_. Cada página de nuestro sitio que estamos construyendo tiene enlaces mediante la etiqueta `<a>`, y cada enlace tiene el atributo `href`, por poner un ejemplo. Otro atributo muy útil es `style`. Este, nos permite aplicar un estilo CSS directamente a un elemento HTML. Trataré más sobre CSS en uno de los capítulos extra al final de este libro, pero por ahora vamos a utilizar el atributo `style` para dividir la lista en dos columnas.

```html
<section>
  <h2>Conocimientos</h2>

  <ul style="columns: 2">
    <li>HTML / CSS</li>
    <li>JavaScript</li>
    <li>TypeScript</li>
    <li>Vue</li>
    <li>PHP</li>
    <li>Sass</li>
    <li>Electron</li>
    <li>Sketch</li>
  </ul>
</section>
```

Lo que resulta en una lista más agradable de ver y un mejor aprovechamiento del espacio.

![Captura de pantalla de la página actualizada del "Currículum". La sección de  "Conocimientos" Ahora está organizada en dos columnas, cada una listando diferentes conocimientos técnicos ofreciendo una presentación visualmente más armónica y aprovechando el espacio en blanco.](imagenes/adding-a-resume-2_es.webp)

### Experiencia

No soy un experto en currículums, pero creo que pondré mi experiencia laboral a continuación, ya que probablemente es lo que más le interesa a un posible empleador en mi campo. Esto será diferente si no tiene mucha experiencia o siente que la educación u otras calificaciones son más relevantes.

Marcar contenido es tanto un arte como una ciencia. No existe una única forma correcta de hacerlo. Un principio rector para elegir qué etiquetas usar es garantizar que las opciones sean significativas y no se basen únicamente en la apariencia.

Por ejemplo, puede estar tentado a utilizar un encabezado `<h6>` en alguna parte de su página, porque quiere un encabezado que no sea muy grande. Pero a menos que ese encabezado tenga efectivamente 6 niveles, `<h6>` no es la mejor elección.

Le mostraré qué marca escogí yo, qué aspecto tiene y luego lo explicaré.

```html
<section>
  <h2>Experiencia</h2>

  <h3>Ingeniero Frontend</h3>

  <p>
    <strong>MRI Technologies</strong><br>
    <time datetime="2019-08">Agosto de 2019</time>&ndash;Presente
  </p>

  <ul>
    <li>Crear y mantener una aplicación de gestión de trajes espaciales para la NASA</li>
    <li>
      Construir y mantener un sistema de gestión de documentos para Collins Aerospace
    </li>
    <li>Crear interfaces reactivas con Vue, API REST y GraphQL</li>
  </ul>

  <!-- ...el resto de trabajos irán aquí -->
</section>
```

Esto nos dará una sección que tendrá un aspecto como este.

![Captura de pantalla de la sección "Experiencia" de una página mostrando el currículum. El título de la sección es "Experiencia" está en negrita y a tamaño grande "Ingeniero Frontend" se muestra de manera prominente, seguido del nombre de la empresa "MRI Technologies" en negrita, con el tiempo que estuve trabajando "Agosto de 2019–Presente" debajo. Una lista describe las responsabilidades que tenía en ese puesto.](imagenes/adding-a-resume-3_es.webp)

Enumeraré varios puestos de trabajo que he tenido, por lo que utilizaré el título del puesto como título (nivel 3, ya que se incluye en el título de nivel 2 de _Experiencia_). A continuación, quiero mostrar el empleador y el período de tiempo. Elegí usar un solo párrafo para mostrarlos juntos. Estoy usando un salto de línea manual para llevar el rango de tiempo a la segunda línea.

Otra forma de hacerlo es poner el nombre del empleador en el encabezado después del puesto de trabajo. No creo que una forma sea más correcta que la otra y prefiero reducir la cantidad de texto grande en la página.

---

**Nota**

Estamos trabajando dentro de las limitaciones de Simple.css en este momento. Si _realmente_ quisiéramos controlar el aspecto de las cosas, agregaríamos algo de CSS personalizado. No haremos eso ahora, pero consulte los capítulos adicionales al final del libro para obtener más información sobre CSS.

---

Envolvemos la fecha en una etiqueta `<time>` y proporcionamos [fecha en formato legible por la máquina](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time#valid_datetime_values) con un _atributo_ `datetime`. Estoy utilizando una _entidad_ HTML, `&ndash;` para colocar un guion entre la fecha de comienzo y de final. Esto es para utilizar el caracter _guion_, que es un poco más largo que el guion normal (`-`) y es [utilizado en tipografía para rangos numéricos](https://practicaltypography.com/hyphens-and-dashes.html).

---

**Nota**

Eche un vistado a esta [lista de entidades HTML](https://perma.cc/BEA6-LF46) para tener una referencia de los caracteres especiales que puede utilizar en HTML.

---

Finalmente, he utilizado una _lista sin orden_ para mostrar unos puntos en los que enumero mi papel en la empresa y las responsabilidades.

Continuaré y añadiré el resto de mi experiencia laboral. Añadiré el código completo para esto al final del capítulo. También puede [echar un vistazo a mi currículum de demostración](https://victorhck.neocities.org/curriculum) y [ver código fuente](https://gitlab.com/victorhck/htmldemo).

### Proyectos seleccionados

Cambiamos a la sección siguiente, en la que me gustaría llamar la atención sobre los proyectos seleccionados en los que he trabajado. Esta es una versión para el currículum de lo que es un portafolio o muestra del trabajo realizado, donde puedo mostrar los sitios web que he realizado e incluir enlaces a ellos. Los currículums impresos tienen que estar basados en texto, pero como esta es una página web, podría incluir una imagen o dos en esta sección.

Para estos proyectos utilizaré la etiqueta `<h3>` para el título del proyecto y pondré un párrafo con una descripción. Si el proyecto sigue activo en la red, añadiré un enlace a él. Aquí hay un ejemplo.

```html
<section>
  <h2>Proyectos seleccionado</h2>

  <h3>Mississippi Gulf Coast Community College</h3>

  <p>
    Trabajé en este sitio web en mi rol de diseñador y desarrollador en Mad Genius. Creé varias de las secciones dinámicas y con uso intensivo de datos, como el catálogo de cursos con capacidad de búsqueda y el índice completo "de la A a la Z". Estas secciones hicieron un uso intensivo de la interfaz de usuario reactiva, integraciones de API de terceros y desarrollo de complementos personalizados de WordPress.
  </p>

  <p><a href="https://mgccc.edu/">mgccc.edu</a></p>

  <!-- ...el resto de proyectos iría aquí -->
</section>
```

### Formación

Y finalmente, añadiré mis títulos universitarios, año de graduación y áreas de estudio. Utilizaré párrafos simples usando la etiqueta `<strong>` para las palabras a las que quiero dar énfasis y `<br>` para los saltos de línea manuales.

```html
<section>
  <h2>Formación</h2>

  <p>
    <strong>Master of Business Administration</strong>, <time>2009</time><br>
    <em>Mississippi State University, Starkville, MS</em>
  </p>

  <p>
    <strong>Bachelor of Business Administration</strong>, Information Systems,
    <time>2007</time><br>
    <em>Mississippi State University, Starkville, MS</em>
  </p>
</section>
```

### Ejemplo completo

Aquí tiene el código completo, incluyendo la cabecera y las áreas de los diversos contenidos.

```html
<header>
  <nav>
    <a href="index.html">Inicio</a>
    <a href="blog/index.html">Blog</a>
    <a href="about.html">Acerca de</a>
    <a href="resume.html" aria-current="page">Currículum</a>
  </nav>

  <h1>Victorhck</h1>
  <p><em>Ingeniero Frontend</em></p>
</header>

<main>
  <section>
    <h2>Skills</h2>

    <ul style="columns: 2">
      <li>HTML / CSS</li>
      <li>JavaScript</li>
      <li>TypeScript</li>
      <li>Vue</li>
      <li>PHP</li>
      <li>Sass</li>
      <li>Electron</li>
      <li>Sketch</li>
    </ul>
  </section>

  <section>
    <h2>Experiencia</h2>

    <h3>Ingeniero Frontend</h3>

    <p>
      <strong>MRI Technologies</strong><br>
      <time datetime="2019-08">Agosto de 2019</time>&ndash;Presente
    </p>

    <ul>
      <li>Crear y mantener una aplicación de gestión de trajes espaciales para la NASA</li>
      <li>Construir y mantener un sistema de gestión de documentos para Collins Aerospace</li>
      <li>Crear interfaces reactivas con Vue, API REST y GraphQL</li>
    </ul>

    <h3>Desarrollador Web/Diseñador</h3>

    <p>
      <strong>Mad Genius</strong><br>
      <time datetime="2015-05">Mayo de 2015</time>&ndash;<time datetime="2019-08">Agosto de 2019</time>
    </p>

    <ul>
      <li>Bocetos, creación de prototipos y diseño de interfaz de usuario</li>
      <li>Desarrollo de temas y complementos para WordPress</li>
      <li>UI reactiva con Vue y Knockout</li>
      <li>Integraciones de API de terceros</li>
    </ul>

    <h3>Desarrollador web</h3>

    <p>
      <strong>Trabajador por cuenta propia</strong><br>
      <time>2007</time>&ndash;<time>2015</time>
    </p>

    <ul>
      <li>Comunicación con clientes</li>
      <li>Desarrollar sitios web cumpliendo los estándares y funcionales</li>
      <li>Realizar sitios web adaptadas a todos los dispositivos</li>
      <li>Participar como voluntario en muchos proyectos sin ánimo de lucro</li>
    </ul>
  </section>

  <section>
    <h2>Formación</h2>

    <p>
      <strong>Master en administración de empresas</strong>, <time>2009</time><br>
      <em>Mississippi State University, Starkville, MS</em>
    </p>

    <p>
      <strong>Ciclo formativo de Información de sistemas</strong> <time>2007</time><br>
      <em>Mississippi State University, Starkville, MS</em>
    </p>
  </section>
</main>
```

Puede ver el resultado en [el sitio web de prueba](https://victorhck.neocities.org/curriculum), pero aquí tiene una captura de pantalla de la página completa.

![Captura de pantalla completa de un "Currículum". El título "Victorhck" y el subtítulo "Ingeniero Frontend" se muestran en grande. Más abajo se muestra la sección de "Conocimientos" que muestra el contenido en dos columnas. La sección de  "Experiencia" detalla el historial laboral, incluyendo las tareas propias del puesto. La sección de "Formación" muestra una lista de los títulos obtenidos (todos ellos ficticios, ya que Victorhck no ha estudiado en Mississipi, ni ha ido a la universidad...).](imagenes/adding-a-resume-4_es.webp)


<center>-#-</center>

<a id="Cap8">
## Intermedio: instalar un servidor web local

HTML es un lenguaje accesible, y esa fue una de las razones por las que quise hacer este libro web. Es agradecido a la hora de comenzar. Si recuerda el primer capítulo (ese primer sitio web que creamos que era solo una frase o dos), recordará que no usamos ni una sola etiqueta HTML. Pero aún así podíamos abrir el archivo en el navegador y ver el contenido. Pusimos ese archivo en la web y ¡funcionó! Puede comenzar de manera simple y aumentar la complejidad según sea necesario.

Ahora estamos en uno de esos puntos. En el próximo capítulo, crearemos una página divertida con chistes, recursos de juegos de mesa y videos de YouTube integrados.

Desafortunadamente, los videos de YouTube no funcionarán con la forma en que hemos estado obteniendo una vista previa de nuestro sitio: abriendo archivos HTML con el navegador web. En su mayor parte, esa es una forma perfectamente correcta de obtener una vista previa de HTML. Pero en los casos en los que obtengamos datos de otros sitios web (como la transmisión de vídeo), necesitaremos imitar un servidor web de la vida real.

Un servidor web es un programa que hace que un sitio web esté disponible en una dirección. Cuando visita esa dirección con un navegador web, obtiene el sitio web. Instalaremos y ejecutaremos uno de estos para que nuestro sitio web esté disponible en una dirección local, es decir, una a la que solo pueda acceder nuestra computadora, no todos los usuarios de Internet.

Le daré varias opciones según el sistema operativo y los conocimientos técnicos necesarios. Así que no es necesario que lo lea todo. Utilice los enlaces a continuación para ir a la sección que corresponda a su caso.

-   [Visual Studio Code (multiplataforma)](https://victorhck.gitlab.io/htmlparapersonas/intermission-installing-a-local-web-server#visual-studio-code-\(cross-platform\))
-   [macOS](https://victorhck.gitlab.io/htmlparapersonas/intermission-installing-a-local-web-server#macos)
-   [Windows y multiplataforma](https://victorhck.gitlab.io/htmlparapersonas/intermission-installing-a-local-web-server#windows-and-cross-platform)
-   [Python y PHP (multiplataforma)](https://victorhck.gitlab.io/htmlparapersonas/intermission-installing-a-local-web-server#python-and-php-(cross-platform))

### Visual Studio Code (multiplataforma)

Microsoft publica una extensión de VS Code llamada [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server). Se ejecuta su sitio en un servidor web local y se actualiza automáticamente a medida que lo cambia. Puede instalarlo desde este enlace o hacer clic en el ícono de extensiones y buscarlo.

![Captura de pantalla de la sección de nuevas extensiones de Visual Studio Code mostrando la página de la extensión  "Live Preview". La extensión está creada por Microsoft y tiene una descripción, calificaciones, instrucciones de uso y un botón de instalación visible.](imagenes/intermission-installing-a-local-web-server-1.webp)

Una vez instalada, podrá ver que la opción _Show Preview (o Mostrar previsualización)_ está disponible cuando hace clic con el botón derecho sobre un archivo.

![Se abre una ventana de VS Code que muestra el código HTML. El archivo "index.html" está seleccionado en la barra izquierda, mientras que se muestra un menú contextual encima del archivo index.html con la opción "Show Preview o Mostrar previsualización" resaltada.](imagenes/intermission-installing-a-local-web-server-2.webp)

Al hacer clic en él, se abrirá un panel lateral con una vista web en una dirección local. Puede usar esa vista previa, abrirla en el navegador navegando a la dirección, o hacer clic en _Abrir en el navegador_ en el menú de la barra de direcciones.

![Captura de pantalla de una ventana de VS Code. En el lado izquierdo hay un código HTML de una página web personal. En el lado derecho, se muestra la vista previa de la página web. "Blake's Homepage" con botones de navegación y una imagen de un cielo nocturno estrellado. La URL está resaltada en una barra de navegación.](imagenes/intermission-installing-a-local-web-server-3.webp)

### macOS

El autor original del tutorial también es usuario de Mac, por lo que recomienda la aplicación [WorldWideWeb](https://iconfactory.com/worldwideweb/). Es gratis para nuestros propósitos, pero tiene una actualización Pro que recargará automáticamente la página cuando realice cambios.

Funciona diciéndole la carpeta de su sitio web y luego haciendo clic en el botón de reproducción.

![Captura de pantalla de la ventana de la aplicación titulada "WorldWideWeb", mostrando dos secciones principales: "Website Folder" y "Web Server." La sección "Website Folder" incluye un icono de una carpeta con el nombre "my-site," y la sección "Web Server" tiene un botón de reproducir marcado "El servidor está parado." Hay flechas rojas apuntando a cada icono para indicar todos los pasos a seguir.](imagenes/intermission-installing-a-local-web-server-4.webp)

Una vez que haga clic en el botón de reproducción, su sitio estará disponible en alguna dirección. Haga clic en _Open Browser o Abrir navegador_ para visitar la URL en su navegador web predeterminado.

![Captura de pantalla de la misma ventana. La interfaz muestra una carpeta de sitio web llamada "my-site" y un servidor web con la URL "http://blakes-mac-studio.local:8080". Hay íconos para acciones de carpeta y botones etiquetados como "Reveal in Finder" y "Open Browser". La URL y el botón Abrir navegador están resaltados.](imagenes/intermission-installing-a-local-web-server-5.webp)

Y ahora observe que estamos viendo nuestro sitio en nuestra nueva y brillante dirección web.

![Ventana de un navegador web llamada "Blake's Homepage" con enlaces de navegación para Inicio, Blog, Acerca de y Currículum. La sección principal presenta una imagen de un cielo nocturno estrellado con nebulosas coloridas. Una flecha roja apunta a la barra de URL en la parte superior de la pantalla.](imagenes/intermission-installing-a-local-web-server-6.webp)

### Windows y multiplataforma

Para los usuarios de Windows, tengo dos opciones para ustedes. Si está utilizando Visual Studio Code, le recomiendo ir a esa sección y consultar la extensión Live Preview de Microsoft.

De lo contrario, intente [Simple Web Server](https://simplewebserver.org/). Una vez que lo haya instalado, puede hacer clic en el botón para crear un nuevo servidor.

![Una captura de pantalla de la aplicación Simple Web Server. La pantalla muestra el texto: Aún no has creado ningún servidor en el centro con un icono de servidor encima. En la esquina inferior derecha, hay un botón amarillo con la etiqueta Nuevo servidor, resaltado con una flecha roja.](imagenes/intermission-installing-a-local-web-server-7.webp)

Luego puede apuntarlo a la carpeta de su sitio web haciendo clic en el botón del icono de carpeta y seleccionando la carpeta adecuada.

![La imagen muestra la ventana 'Agregar servidor' desde la aplicación Simple Web Server. Incluye campos para 'Ruta de carpeta' y 'Puerto', con opciones para Opciones básicas, Opciones avanzadas y Páginas de error. Los botones etiquetados como Cancelar y Crear servidor se encuentran en la parte inferior.](imagenes/intermission-installing-a-local-web-server-8.webp)

Una vez que haya creado el servidor, lo verá en la lista de servidores. Haga clic en él para abrirlo. Desde allí, verá la URL donde está disponible su sitio y podrá hacer clic en el enlace para abrirlo en su navegador predeterminado.

![Una ventana de Simple Web Server titulada 'Editar servidor' muestra opciones para un servidor web en ejecución. La URL resaltada es 'http://127.0.0.1:8080' y parece que se puede hacer clic en ella. Hay campos para la ruta de la carpeta, el puerto (establecido en 8080) y una casilla de verificación para la accesibilidad de la red local. En la parte inferior están los botones cancelar y guardar cambios.](imagenes/intermission-installing-a-local-web-server-9.webp)

---

**Nota**

Simple Web Server es multiplataforma y también funciona en macOS y Linux. Dicho esto, recomiendo WorldWideWeb para usuarios de Mac a menos que necesiten varios servidores ejecutándose simultáneamente.

---

### Python y PHP (multiplataforma)

Esta es una opción más técnica. No es necesario ser un hacker de élite, pero deberá ejecutar un programa de línea de comandos desde su aplicación de terminal.

#### Python

Si no tiene ninguno de los dos en su máquina, Python es el más fácil de configurar. Vaya a la [página de descargas de Python](https://www.python.org/downloads/) y descargue el instalador para su sistema (obtenga la versión 3).

Abra una terminal en su sistema y mediante el comando `cd` vaya hasta el directorio donde almacena los archivos de su sitio web. Allí ejecute este comando para arrancar el servidor web Python de pruebas.

```bash
python3 <span class="token parameter variable">-m</span> http.server
```

Esto hará que su sitio esté disponible en `localhost` en cualquier puerto que especifique (normalmente el 8000). Así que la dirección de su sitio web sería `http://localhost:8000`.

#### PHP

La instalación de PHP está fuera del alcance de este libro, pero está disponible para casi todos los sistemas. PHP nació como una tecnología de sitios web y, como comentaré en un capítulo adicional, [PHP es útil para reutilizar fragmentos de HTML](#Cap13) (como el menú de navegación) entre múltiples páginas del mismo sitio.

Si PHP está en su sistema, puede ejecutar el servidor de desarrollo PHP de manera similar al ejemplo de Python anterior.

```bash
php <span class="token parameter variable">-S</span> localhost:8000
```

Esto hará que su sitio esté disponible en `http://localhost:8000`.

<a id="Cap8_URL">
### URL relativas versus absolutas

Hasta ahora, dado que abrimos los archivos de nuestro sitio web directamente en el navegador, necesitábamos usar URL relativas. Las URL relativas se escriben desde la perspectiva del archivo actual. Por ejemplo, si estoy en una subpágina y quiero vincularme a una página de nivel superior, necesito usar la sintaxis `..` para "subir" un nivel y encontrar la página de destino.

Cuando ejecutamos un servidor web, podemos usar URL absolutas. Una URL absoluta siempre se escribe desde la perspectiva del nivel más alto (el _nivel más alto_ significa la carpeta que le indicamos al servidor web que use). No importa en qué subpágina esté, puedo vincularme a la página de inicio del sitio web de la siguiente manera.

```html
<a href="/">Ir a la página de incio</a>
```

La barra diagonal representa el nivel superior (también podría haber escrito `/index.html` pero no es necesario porque los servidores web la usarán automáticamente si existe). Si quisiera vincular a la página `acercade.html`, podría hacerlo de la siguiente manera.

```html
<a href="/acercade.html">Ir a la página Acerca de</a>
```

Lo bueno es que no importa en qué página estoy: puede ser una página de nivel superior o una subpágina. Esta ruta siempre conducirá a la página Acerca de, sin importar dónde se encuentre la página actual. Digamos que estamos en una página anidada en una carpeta.

```html
<!-- imagine que actualmente estamos en una página del blog /blog/mi-post.html-->
<h1>Mi blog post</h1>

<!-- en lugar de esto, que *sí* funciona -->
<a href="../acercade.html">About</a>

<!-- podemos hacer esto -->
<a href="/acercade.html">About</a>
```

Antes no usábamos URL absolutas porque no estábamos usando un servidor web. Si hubiéramos intentado utilizar URL absolutas al abrir nuestro sitio web directamente en el navegador, la barra habría apuntado hacia la carpeta de nivel superior de _todo el ordenador_, lo que ciertamente no es lo que queríamos.

Ahora que estamos usando un servidor web, le dejaré a usted si quiere regresar y cambiar todas las rutas, pero eso hace que copiar y pegar el menú sea más fácil. Crear enlaces entre páginas es más sencillo cuando se utilizan URL absolutas.

<center>-#-</center>

<a id="Cap9">
## Añadir una página divertida

Muy bien, ¡es hora de _divertirse_! Bueno, espero que todo lo que hemos visto hasta ahora haya sido divertido. Pero todavía quiero mostrarle algunas cosas que puede hacer con HTML. Dejé esta página para el final porque usaremos algunas de las etiquetas HTML más complejas.

### Crear el archivo

Vamos a crear el archivo `fun.html` en el nivel superior de la carpeta de nuestro sitio web. Utilice el contenido de la página de inicio como punto de partida, y después cambie el `<título>` y el encabezado `<h1>` a _Diversión_ o algo similar. Limpie el contenido de dentro de la etiqueta `<main>`.

Ahora, dividiremos esta página en varias secciones de manera similar a como hicimos en la página del currículum.

### Chistes

Primero, agreguemos una sección para algunos chistes.

```html
<section>
  <h2>Chistes</h2>

  ...Los chistes irán aquí
</section>
```

La idea es mostrar la configuración del chiste pero ocultar el remate detrás de un clic. Puedes echar un vistazo a [la página de demostración aquí](https://victorhck.neocities.org/diversion). Utilizaremos la etiqueta `<details>` y `<summary>` con estos elementos lograremos el comportamiento que queremos. Estos elementos funcionan de la siguiente manera.

```html
<details>
  <summary>Este contenido se mostrará de forma predeterminada.</summary>

  <p>
    Al hacer clic en el contenido anterior, este contenido oculto se volverá visible.
  </p>
</details>
```

Aquí hay una demostración en video de este elemento en acción.

![El vídeo muestra una grabación del efecto anterior, en el que parte del contenido se muestra al hacer clic sobre una parte del texto que siempre se muestra, revelándose el resto del texto.](imagenes/adding-a-fun-page-1_es.mp4)

Voy a agregar tres chistes ciertamente malos.

```html
<section>
  <h2>Chistes</h2>

  <details>
    <summary>¿Qué carga más que una batería de litio?</summary>
    <p>Una de litio y medio.</p>
  </details>

  <details>
    <summary>¿Por qué estaba triste el libro de matemáticas?</summary>
    <p>Porque tenía muchos problemas.</p>
  </details>

  <details>
    <summary>¿Qué le dice un jardinero a otro?</summary>
    <p>Seamos felices mientras podamos.</p>
  </details>
</section>
```

Este es simplemente un ejemplo un poco tonto, pero los elementos `<details>`/`<summary>` son muy útiles cuando quiera que las personas que leen su web vean un titular e indaguen un poco más si lo desean. Por ejemplo, en una lista de preguntas frecuentes (FAQ).

### Utilizar tablas para juegos de mesa

A continuación, usemos las tablas HTML. La etiqueta `<table>` y sus etiquetas relacionadas nos brindan formas poderosas de mostrar información. Para fines de aprendizaje, crearemos una pequeña tabla. Pero si necesita mostrar muchos más datos de manera organizada y _tabulada_, eche un vistazo [a la página sobre tablas de MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table).

En los juegos de rol de mesa como _Dungeons and Dragons_, el director del juego a menudo necesita improvisar para crear encuentros para los jugadores aventureros. Una de esas formas es utilizar una tabla aleatoria. Es una tabla que unirá las tiradas de dados con elementos, criaturas o eventos específicos. Haremos una tabla con ocho posibles encuentros que podría encontrar el grupo aventurero. El director del juego lanzará un dado de ocho caras y utilizará el encuentro resultante en consecuencia.

Así será la tabla final.

![Una tabla titulada 'Tira (1d8) Encuentro' con dos columnas. La columna de la izquierda enumera los números del 1 al 8, y la columna de la derecha enumera los encuentros correspondientes: 1. Banda de duendes, 2. Mercader errante, 3. Grupo de bandidos, 4. Manada de lobos, 5. Juglares ambulantes, 6. Niño perdido, 7. Trampa oculta, 8. Viejo ermitaño.](imagenes/adding-a-fun-page-1_es.webp)

Primero, crearé una nueva sección con `<section>` que tendrá un encabezado y un texto introductorio sobre D&D. Luego, presentaré brevemente la tabla de encuentros aleatorios.

```html
<section>
  <h2>Cosas relacionadas con el juego de rol D&D</h2>

  <p>
    Dungeons & Dragons (D&D) es un divertido juego de mesa en el que creas personajes y vives aventuras épicas con amigos. Guiado por un Dungeon Master (DM), tirarás dados para ver qué sucede a continuación. Se trata de creatividad, trabajo en equipo y pasarlo genial mientras realizas misiones, luchas contra monstruos y encuentras tesoros increíbles.
  </p>

  <h3>Tabla de encuentros aleatorios</h3>

  <p>
    Esta es una tabla que puedes usar para decidir aleatoriamente qué enemigo o criatura se encontrarán los jugadores. Simplemente tira un d8.
  </p>

  ...La tabla irá aquí
</section>
```

Utilizamos la etiqueta `<table>` para crear una tabla. Una tabla puede tener una sección de cabecera y una sección para el contenido.

```html
<table>
  <thead></thead>
  <tbody></tbody>
</table>
```

La tabla necesita dos columnas: una para la tirada de dados y otra para el encuentro correspondiente. Vamos a crear una _fila en la tabla_ dentro de `<thead>`. Completaré la sección principal y luego la explicaré.

```html
<table>
  <thead>
    <tr>
      <th>Roll (1d8)</th>
      <th>Encuentro</th>
    </tr>
  </thead>
  <tbody></tbody>
</table>
```

La etiqueta `<tr>` crea una fila en la tabla o _table row_. Dentro de la fila, añadiremos dos celdas a la tabla. Porque estos son encabezados de columnas, utilizaremos un encabezado _table header_ o `<th>` una para la tirada de dados y otra para el resultado. Así es como se verá hasta ahora.

![Una imagen que describe Dungeons & Dragons (D&D) como un divertido juego de mesa que implica creación de personajes y aventuras. Hay una sección de Tabla de encuentros aleatorios con los encabezados de una tabla eliminados.](imagenes/adding-a-fun-page-2_es.webp)

A continuación, podemos completar nuestra tabla usando la etiqueta _table data cell_ o `<td>`. Pondremos estas filas dentro de la sección del cuerpo.

```html
<table>
  <thead>
    <tr>
      <th>Roll (1d8)</th>
      <th>Encuentro</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>1</td>
      <td>Banda de duendes</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Mercader errante</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Grupo de bandidos</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Manada de lobos</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Juglares ambulantes</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Niño perdido</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Trampa oculta</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Viejo ermitaño</td>
    </tr>
  </tbody>
</table>
```

¡Son muchas etiquetas! Con suerte, puede seguir la lógica aquí. Dentro de `<tbody>`, creamos ocho _table rows_, cada una con dos _table data cells_. Y eso nos dará nuestra tabla final.

![Una tabla titulada 'Roll (1d8) Encuentro' con dos columnas. La columna de la izquierda enumera los números del 1 al 8, y la columna de la derecha enumera los encuentros correspondientes: 1. Banda de duendes, 2. Mercader errante, 3. Grupo de bandidos, 4. Manada de lobos, 5. Juglares ambulantes, 6. Niño perdido, 7. Trampa oculta, 8. Viejo ermitaño.](imagenes/adding-a-fun-page-1_es.webp)

Las tablas HTML también pueden hacer algunas cosas que haría en un programa de hoja de cálculo, como hacer que una celda abarque varias columnas. No entraremos en eso aquí, pero recuerde que las tablas son muy potentes si lo necesita.

### Insertar vídeos

Por último, pero no menos importante, demosle vida a nuestra página _¡diversión!_ agregando algunos videos. Optaré por un poco de música realizada con sintetizadores. Por supuesto, le animo a que inserte los vídeos de YouTube que prefiera. Algunos YouTubers optan por no permitir que sus vídeos se inserten en otros sitios, así que téngalo en cuenta.

Haré una nueva sección para mis videos.

```html
<section>
  <h2>Synthwave mixes</h2>

  ...los vídeos irán aquí
</section>
```

Primero, tomaré esta mezcla de música llamada Waves ([https://www.youtube.com/watch?v=b6toYA0W4IA](https://www.youtube.com/watch?v=b6toYA0W4IA)). Si visita esa página, verá un botón para compartir debajo del video. Al hacer clic en ese botón, se mostrarán varias opciones para compartir el video.

![Captura de pantalla de un cuadro de diálogo para compartir de YouTube para la creación de una publicación, que muestra las opciones para compartir para Insertar, WhatsApp, Facebook, X (anteriormente Twitter), Correo electrónico y KakaoTalk. También hay un hipervínculo único con un botón de "Copiar" junto a él, y una casilla de comprobación para comenzar en un minuto específico del vídeo.](imagenes/adding-a-fun-page-4_es.webp)

Seleccione "Insertar" si está disponible. Una vez que haga eso, verás un código HTML y un botón _Copiar_. Continúe y copie el código. Puede pegar el código después de la etiqueta `<h2>`.

```html
<section>
  <h2>Synthwave mixes</h2>

  <iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/b6toYA0W4IA?si=-Iu68cVS5E08st5O"
    title="Reproductor de vídeo de YouTube "
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen
  ></iframe>
</section>
```

Este código utiliza la etiqueta `<iframe>`. No entraré en muchos detalles sobre este elemento, pero en resumen, se utiliza para mostrar una página web dentro de otra página web. Pero cuando recargo la página, aparece el error "Video no disponible". ¿Por qué?

![Captura de pantalla de una página web titulada "Synthwave mixes" con un reproductor de vídeo integrado en el centro que muestra un mensaje que dice "Vídeo no disponible. Ver en YouTube." Hay una barra de direcciones en la parte superior que indica la ruta del archivo local.](imagenes/adding-a-fun-page-5.webp)

Es porque todavía tengo mi sitio web abierto como un archivo. Necesitamos obtener datos de otro sitio web (YouTube), pero las funciones de seguridad del navegador nos impiden hacerlo.

#### Poner en marcha nuestro servidor web local

¡Pero no hay de qué preocuparse! Es por eso que instalamos un servidor web local en el capítulo anterior. Si aún no lo ha hecho, inicie su servidor web siguiendo el método que eligió en el capítulo anterior.

---

**Nota**

Desafortunadamente, las cosas se ponen un poco raras aquí. Algunas de estas opciones de servidor, como Live Preview y Simple Web Server, abren de forma predeterminada el navegador en la dirección IP `127.0.0.1`, que es esencialmente equivalente a `localhost`, el valor que utilizan otros servidores locales.

Por razones que no comprendo del todo, los vídeos insertados no funcionarán al acceder al sitio mediante la dirección IP. Necesitas usar `localhost`. Afortunadamente, eso es tan fácil como reemplazar manualmente `127.0.0.1` con `localhost` en la barra de direcciones. Si utiliza Microsoft Live Preview, debe ver el sitio en su navegador web en lugar de en la ventana de vista previa.

---

Utilizaré [WorldWideWeb](https://iconfactory.com/worldwideweb/) para este ejemplo. Cuando lo apunte a la carpeta de mi sitio y haga clic en el botón de reproducción, mi servidor se ejecutará y podré visitarlo en la dirección proporcionada.

![Captura de pantalla de la misma ventana. La interfaz muestra una carpeta de sitio web llamada "mi sitio" y un servidor web con la URL "http://blakes-mac-studio.local:8080". Hay íconos para acciones de carpeta y botones con la etiqueta "Mostrar en Finder" y "Abrir navegador". La URL y el botón Abrir navegador están resaltados.](imagenes/intermission-installing-a-local-web-server-5.webp)

Vuelva a verificar la barra de direcciones de su navegador para asegurarse de acceder a la versión del servidor web en lugar del archivo directo.

![Una página web titulada "Synthwave mixes" que incluye un reproductor de vídeo de YouTube integrado. El vídeo se titula "Waves - A Chillwave Mix Vol. 2" y tiene una imagen de portada con un diseño futurista, que incluye un planeta y un rayo de luz. Ahora hay una dirección web HTTP en lugar de una ruta de archivo local.](imagenes/adding-a-fun-page-6.webp)

¡Impresionante! Escogeré dos videos más para añadirlos.

-   [https://youtu.be/rDfS8B2-Mt4](https://youtu.be/rDfS8B2-Mt4)
-   [https://youtu.be/yb0DR\_qRetA](https://youtu.be/yb0DR_qRetA)

Con estos haré lo mismo que hice con el primero. Abra la página del video, haga clic en _Compartir_, y después _Insertar_, y copie el código proporcionado. Pegue el código de cada vídeo debajo del primero.

Después insertaré mis videos, pero ahora noto algo más. Sería bueno si estos videos abarcaran todo el ancho de mi página. Además, veamos cómo se vería nuestro sitio web en un teléfono.

![Con Safari en modo de diseño responsivo y la ventana reducida al ancho del dispositivo móvil, el video insertado de YouTube sobresale del costado de la página, lo que provoca que aparezca una barra de desplazamiento horizontal.](imagenes/adding-a-fun-page-7.webp)

Si veo el sitio web usando el _modo de diseño responsivo_ de Safari y estrecho la ventana gráfica, veo que los videos insertados se muestran justo en el lado derecho de la página. No queda bien visualmente.

Hay varias formas de solucionar este problema. Usaremos una solución de terceros.

#### Etiquetas HTML personalizadas

HTML nos proporciona una manera de crear nuestras propias etiquetas personalizadas. Estos se denominan componentes web. Normalmente utilizan una combinación de HTML, CSS y JavaScript para definir la apariencia y el comportamiento del componente. Crear nuestros propios componentes web está fuera del alcance de este libro, pero está bien. No necesitamos crear uno nosotros mismos; Podemos utilizar componentes web que otras personas han creado.

Vamos a utilizar [Lite YouTube Embed](https://github.com/paulirish/lite-youtube-embed#readme). Siéntase libre de leer sobre lo que puede hacer. Para nuestros propósitos, solo queremos instalarlo y hacer que muestre un video de ancho completo y que se reduzca correctamente en los teléfonos.

Antes de ver cómo instalar este componente, veamos cómo lo usaríamos. Proporciona una nueva etiqueta personalizada, `<lite-youtube>`. Le da un _atributo_ de `videoid`, que es el ID del vídeo de YouTube. Puedes encontrar el ID del video en la URL. Esta es mi :

```
https://www.youtube.com/watch?v=b6toYA0W4IA
                                |_________|
                                 ID del video
```

```html
<lite-youtube videoid="b6toYA0W4IA"></lite-youtube>
```

¡Mucho más limpio que el `<iframe>`!

Bien, instalemos esto. Necesitamos dos archivos: un archivo JavaScript y un archivo CSS. El desarrollador del componente proporciona estos archivos y, juntos, incluyen todo el código que hace que el componente se vea y funcione correctamente. Te daré un enlace directo a ambos. Guarde el archivo CSS en la carpeta `css` de su sitio web. Luego, cree una carpeta `js` para el archivo JavaScript.

-   Archivo JS: [https://cdnjs.cloudflare.com/ajax/libs/lite-youtube-embed/0.3.2/lite-yt-embed.min.js](https://cdnjs.cloudflare.com/ajax/libs/lite-youtube-embed/0.3.2/lite-yt-embed.min.js)
-   Archivo CSS: [https://cdnjs.cloudflare.com/ajax/libs/lite-youtube-embed/0.3.2/lite-yt-embed.min.css](https://cdnjs.cloudflare.com/ajax/libs/lite-youtube-embed/0.3.2/lite-yt-embed.min.css)

Visite cada uno de esos enlaces y utilice _Archivo > Guardar página como…_ (Ctrl+S en Windows, Command+S en macOS). Una vez que ya haya guardado los archivos añádalos a la sección `<head>` de la página. Así es como quedaría.

```html
<head>
  <title>Diversión en la página de Victorhck</title>
  <meta charset="utf-8">

  <link rel="stylesheet" href="css/simple.css">
  <link rel="stylesheet" href="css/lite-yt-embed.min.css">
  <script src="js/lite-yt-embed.min.js"></script>
</head>
```

Primero, añadimos el archivo CSS (el orden en que se haga no es importante). Lo llamaremos de manera similar a como lo hicimos con el archivo Simple.css, utilizando la etiqueta `<link>`. También llamaremos al código de JavaScript. Para eso, utilizaremos la etiqueta `<script>`. Lleva el atributo `src`, que es la ruta del archivo.

Una vez que estos dos archivos estén presentes, podremos utilizar el nuevo componente. Volviendo a nuestro ejemplo, tenemos esta URL de YouTube:

[https://www.youtube.com/watch?v=b6toYA0W4IA](https://www.youtube.com/watch?v=b6toYA0W4IA)

Necesitamos obtener el ID de esta URL. En una URL de un vídeo de YouTube, el ID es la porción de texto que va detrás de `v=`. En nuestro caso, sería `b6toYA0W4IA`. Así que podemos insertar el vídeo utilizando la siguiente sintaxis.

```html
<lite-youtube videoid="b6toYA0W4IA"></lite-youtube>
```

Haré lo mismo con los otros dos vídeos del ejemplo.

```html
<lite-youtube videoid="b6toYA0W4IA"></lite-youtube>

<lite-youtube videoid="rDfS8B2-Mt4"></lite-youtube>

<lite-youtube videoid="yb0DR_qRetA"></lite-youtube>
```

¡Tiene buena pinta!

![Una página web con un diseño responsivo mostrando las portadas de tres vídeo sobre música realizada con sintetizadores.  La anchura de los vídeos ha sido solucionada, pero todavía se ven muy juntos de manera vertical, tocándose entre ellos.](imagenes/adding-a-fun-page-8.webp)

Añadiré algunas _separaciones horizontales_ para crear una separación entre los vídeos.

```html
<lite-youtube videoid="b6toYA0W4IA"></lite-youtube>
<hr>
<lite-youtube videoid="rDfS8B2-Mt4"></lite-youtube>
<hr>
<lite-youtube videoid="yb0DR_qRetA"></lite-youtube>
```

Y ahora veamos qué aspecto tiene la página al visualizarla desde un dispositivo móvil.

![La misma imagen que antes, excepto que ahora se ven entre los tres vídeos una fina línea que los separa, quedando visualmente mejor.](imagenes/adding-a-fun-page-9.webp)

¡Genial!

## Ejemplo con el código completo

Para ver esta página en acción, [echa un vistazo a la página de ejemplo](https://victorhck.neocities.org/diversion). Este es el código completo para la página _¡Diversión!_.

```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Diversión - Web de Victorhck</title>

    <link rel="stylesheet" href="css/simple.css">
    <link rel="stylesheet" href="css/lite-yt-embed.min.css">
    <script src="js/lite-yt-embed.min.js"></script>
  </head>

  <body>
    <header>
      <nav>
        <a href="index.html">Inicio</a>
        <a href="blog/index.html">Blog</a>
        <a href="about.html">Acerca de</a>
        <a href="resume.html">Currículum</a>
        <a href="fun.html" aria-current="page">Diversión</a>
      </nav>

      <h1>Diversión</h1>
    </header>

    <main>
      <section>
        <h2>Chistes</h2>

        <details>
          <summary>¿Qué carga más que una batería de litio?</summary>
          <p>Una de litio y medio.</p>
        </details>

        <details>
          <summary>¿Por qué está triste el libro de matemáticas?</summary>
          <p>Porque tiene muchos problemas.</p>
        </details>

        <details>
          <summary>¿Qué le dice un jardinero a otro?</summary>
          <p>Seamos felices mientras podamos</p>
        </details>
      </section>

      <section>
        <h2>Cosas relacionadas con el juego de rol D&D</h2>

        <p>
          Dungeons & Dragons (D&D) es un divertido juego de mesa en el que creas personajes y vives aventuras épicas con amigos. Guiado por un Dungeon Master (DM), tirarás dados para ver qué sucede a continuación. Se trata de creatividad, trabajo en equipo y pasarlo genial mientras realizas misiones, luchas contra monstruos y encuentras tesoros increíbles.
        </p>

        <h3>Tabla de encuentros aleatorios</h3>

        <p>
           Esta es una tabla que puedes usar para decidir aleatoriamente qué enemigo o criatura se encontrarán los jugadores. Simplemente tira un d8.
        </p>

        <table>
          <thead>
            <tr>
              <th>Roll (1d8)</th>
              <th>Encuentro</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>Banda de duendes</td>
            </tr>
            <tr>
              <td>2</td>
              <td>Mercader errante</td>
            </tr>
            <tr>
              <td>3</td>
              <td>Grupo de bandidos</td>
            </tr>
            <tr>
              <td>4</td>
              <td>Manada de lobos</td>
            </tr>
            <tr>
              <td>5</td>
              <td>Juglares ambulantes</td>
            </tr>
            <tr>
              <td>6</td>
              <td>Niño perdido</td>
            </tr>
            <tr>
              <td>7</td>
              <td>Trampa escondida</td>
            </tr>
            <tr>
              <td>8</td>
              <td>Viejo ermitaño</td>
            </tr>
          </tbody>
        </table>
      </section>

      <section>
        <h2>Synthwave mixes</h2>

        <lite-youtube videoid="b6toYA0W4IA"></lite-youtube>
        <hr>
        <lite-youtube videoid="rDfS8B2-Mt4"></lite-youtube>
        <hr>
        <lite-youtube videoid="yb0DR_qRetA"></lite-youtube>
      </section>
    </main>

    <footer>
      <p>Hecho con ❤️ y ☕️ por Victorhck.</p>
    </footer>
  </body>
</html>


```

## Publicar el sitio

¡Lo consiguió! Con esta página completada, ha finalizado la parte principal de este libro web. Siguiendo los pasos que hemos realizado en los capítulos anteriores, actualice su sitio en Neocities con esta nueva página. Recuerde actualizar el menú de las otras páginas para incluir esta recién creada.

<center>-#-</center>

<a id="Cap10">
## Logro conseguido: Hypertexter

Felicidades: ¡Ha realizado un gran sitio web con HTML! Lo que comenzó como una o dos frases escritas en el bloc de notas se convirtió en un sitio web mcon muchas secciones y páginas. En el proceso ha aprendido todo tipo de cosas:

-   Crear páginas HTML
-   Estructurar contenido con encabezados y secciones
-   Enlazar a otras páginas web
-   Dar formato al texto
-   Citar texto con un bloque de citas
-   Mostrar datos utilizando tablas
-   Ocultar contenido detrás de un sumario sobre el que poder hacer clic
-   Crear contenido secundario utilizando apartes
-   Poner en marcha un servidor local de pruebas
-   Insertar imágenes
-   Insertar vídeos
-   Utilizar componentes creados por terceros
-   Crear un sitio web disponible para todo el mundo en internet
-   …y muchos otros temas.

Espero que se sienta facultado para crear sus propios sitios web personalizados. Pero incluso si no crea sitios web desde cero, la familiaridad con HTML puede ser útil. Muchos sistemas de gestión de contenido le permiten poner HTML personalizado en una página. Incluso saber cómo usar la etiqueta `<a>` para crear enlaces tiene su propio pequeño superpoder.

Bueno, ¿y ahora?

### Capítulos extra

Hemos completado el contenido principal que quería tratar en _HTML para personas_. Dicho esto, tengo algunos temas que me gustaría tratar como un apéndice al libro principal.

-   **[Personalizando Simple.css](#Cap11)**. Incluso sin necesidad de aprender mucho sobre CSS, puede cambiar la apariencia de su sitio web modificando algunas variables.
-   **[Lo básico de CSS](#Cap12)**. Esta sección le enseña cómo realizar páginas web con una gran apariencia y diseño desde cero utilizando CSS.
-   **[Reutilizar HTML con PHP](#Cap13)**. Echaremos un vistazo sobre cómo reutilizar partes de HTML, como por ejemplo el menú de navegación, utilizando lenguaje PHP. Esta es una introducción muy ligera sobre programación a la hora de aplicarlo en sitios web dinámicos.

<a id="Recursos">
### Recursos de este libro

He ido dejando aquí y allá durante el libro una buena colección de enlaces interesantes de demostraciones y de documentación interesantes. Como utilidad, aquí hago una lista con los principales.

-   **[La página de demostración de Blake](https://demo.htmlforpeople.com/)**. Esta es la versión del autor Blake del sitio web que este libro web te ha ido enseñando cómo hacerla. Si has seguido todas las lecciones y has realizado tu propia página web, [el autor estará encantado de que se lo hagas saber](https://blakewatson.com/about/#contact-me).
-   **[La página de demostración de Victorhck](https://victorhck.neocities.org/)**. Siguiendo los pasos del autor, yo también he creado mi página de demostración en Neocities. Si has seguido todas las lecciones que he traducido y has realizado tu propia página web, [también a mí me gustará saberlo](https://victorhckinthefreeworld.com/contacto/).
-   **[Código fuente de la página de la página de demostración de Blake](https://github.com/blakewatson/htmlforpeopledemo)**. Este es el repositorio del código del sitio web de demostración. Aquí, puedes navegar por el código y descargarlo si lo deseas.
-   **[Código fuente de la página de la página de demostración de Victorhck](https://gitlab.com/victorhck/htmldemo)**. Este es el repositorio del código del sitio web de demostración que he realizado yo. Aquí, puedes navegar por el código y descargarlo si lo deseas.
-   **[La versión con PHP del sitio web de Blake](https://github.com/blakewatson/htmlforpeopledemo/tree/php)**. Esta es otra versión del código fuente donde el autor ha convertido el sitio utilizando PHP tal como se ha descrito en el capítulo extra, [Reutilizar HTML con PHP](#Cap13).
-   **[Demostración de planetas del sistema solar](https://planets.htmlforpeople.com/)**. Esta web es una demostración de la página web que hemos realizado en el capítulo extra, [Lo básico de CSS](#Cap12).
-   **[El código fuente de la página planetas del sistema solar](https://github.com/blakewatson/css-basics)**. Este es el repositorio del código de la página.

### Recursos y documentación útiles

-   **[MDN](https://developer.mozilla.org)**. Si necesita detalles sobre una etiqueta HTML en particular, alguna propiedad CSS u otra información técnica específica, este es el mejor lugar para obtenerla. MDN es más o menos el manual oficial del usuario para la realización de un sitio web.
-   **[Neocities](https://neocities.org/)** y [Neocities FAQs](https://neocities.org/contact). He escogido utilizar este servicio de alojamiento web en el libro porque es gratuito y tiene un espíritu similar (creación de sitios web centrada en las personas). Las preguntas frecuentes (FAQ) tienen mucha buena información e información sobre el servicio si desea más información al respecto.
-   **[Tutoriales de Neocities](https://neocities.org/tutorials):** Una lista de tutoriales y recursos publicados por Neocities. Eche un vistazo a su gran [curso de HTML](https://neocities.org/tutorial/html/1).
-   **[Simple.css](https://simplecss.org/)**. Este es el entorno CSS que hemos utilizamos en todo el libro. El sitio tiene documentación sobre cómo usar Simple.CSS y una demostración de varios elementos HTML.
-   **[Tipografía práctica de Butterick](https://practicaltypography.com/)**. Un excelente libro sobre tipografía y diseño. Si tiene poco tiempo, eche un vistazo a su [Tipografía en diez minutos](https://practicaltypography.com/typography-in-ten-minutes.html).
-   **[EntityCode](https://entitycode.com/)**. Una referencia de _entidades HTML_ que puede utilizar para reproducir caracteres especiales y símbolos.
-   **[Verificador de contraste de color](https://coolors.co/contrast-checker)**. Una buena herramienta para asegurarse de que su texto y colores de fondo tengan suficiente contraste para ser legible.

### Lugares donde hospedar una página web estática

Además de Neocities, existen otras buenas alternativas donde hospedar sus páginas web HTML.

-   **[Yay.boo](https://yay.boo/):** Un nombre gracioso, publicación de sitios web realmente fácil. Arrastre y suelte una carpeta, elija un nombre y su sitio web está en línea. El nivel gratuito pone un enlace yay.boo en la esquina de su sitio.
-   **[Glitch](https://glitch.com/):** Esta es una buena opción si quieres realizar toda la tarea de programación directamente desde el navegador. Construye primero tu página y después publícala.
-   **[Netlify](https://www.netlify.com/):** Más sofisticado, pero tiene una opción de [arrastrar y soltar una carpeta para publicar](https://perma.cc/W3PH-5KRS) y le da más funcionalidades centradas en el desarrollo.

### Editores de código alternativos

Utilizo [Visual Studio Code](https://code.visualstudio.com/) como mi editor de texto de código y lo he utilizado a lo largo de este libro. Y por una buena razón, es gratuito y masivamente popular. Pero no es el único editor de código que existe.

Utilizo Mac, así que no estoy muy familiarizado con los editores de texto para otros sistemas operativos, pero existen algunos a los que debería echar un vistazo y evaluarlos por usted mismo. Algunos son gratuitos, otros son de pago y otros tienen ambas opciones.

-   **[Sublime Text](https://www.sublimetext.com/):** Multiplataforma con un periodo de prueba sin límite (que de vez en cuando le recordará que debe pagar). Sublime Text fue el estándar en el desarrollo web hasta que VS Code le arrebató el trono. Sigue siendo muy bueno. Muy rápido y ligero. El sistema de complementos y extensiones es más difícil de utilizar, pero puede que no necesite ninguna para realizar tareas básicas de HTML/CSS, ya que tiene un buen soporte para ambos, tal como viene de serie.
-   **[WebStorm](https://www.jetbrains.com/webstorm/):** Uno de muchos _IDEs_ (iniciales de integrated development environments o entornos de desarrollo integrado) de pago, de JetBrains. Es multiplataforma y tiene un buen montón de funcionalidades. Es de pago, pero tiene un periodo de prueba de 30 días de manera gratuita. A la gente le encanta. No lo he utilizado mucho, así que no puedo opinar mucho al respecto, salvo que tiene muy buena reputación.
-   **[Zed](https://zed.dev/):** Multiplataforma (Mac and Linux, y pronto también para Windows) es gratuito. Parece una mezcla entre VS Code y Sublime Text y tiene mucha fama a la hora de escribir este libro.
-   **[Nova](https://nova.app/):** Solo disponible para Mac y de pago (pero con un periodo de prueba gratuito). Es una secuela de Coda, un gran editor de desarrollo web para Mac del mismo desarrollador (Panic). Las aplicaciones de Panic son siempre fantásticas, así que dale a Nova un vistazo si utiliza Mac.
-   **[NotePad++](https://notepad-plus-plus.org/):** Un editor gratuito y de código abierto para Windows. No puedo decir mucho sobre él más que lleva mucho tiempo en el mercado.
-   **[BBEdit](https://www.barebones.com/products/bbedit/):** Uno de los programas de Mac más antiguos que todavía están en activo. BBedit es de pago, pero ofrece un modo de prueba y un modo gratis para siempre que lo limita a un subconjunto de características en particular.
-   **[Glitch](https://glitch.com/):** Sí, es el mismo que el publicado en la lista anterior de host para webs. Glitch es una buena opción si quiere trabajar "en la nube". Ofrece una interfaz basada en la web para realizar sitios web, incluyendo crear archivos y editar código. Todo se realiza en el navegador, lo que es una buena opción si no quiere estar descargando e instalando cosas en su equipo.
-   Y muchos, muchos más. Hay demasiados para enumerar aquí, pero si ninguno de estos se adapta a sus gustos, consulte su motor de búsqueda favorito y prepárese para el diluvio de resultados.

Permítame ahora que como traductor de este libro web tome la palabra. Yo (Victorhck) soy un defensor del [software libre](https://www.gnu.org/philosophy/free-sw.es.html), por lo que pongo más énfasis en que el software que utilizo esté publicado bajo una licencia libre, que me de libertad y no tanto en el precio que tiene el software que utilizo.

Soy usuario de un sistema GNU/Linux y nunca he utilizado Mac. A continuación le voy a dar mis opciones de software libre respecto a editores de texto. Las dos primeras son las que utilizo de manera diaria, por ejemplo para escribir y traducir este libro.

-   **[Kate](https://kate-editor.org/es/)**: Un editor de texto muy sencillo, pero potente creado por la comunidad de [KDE](https://kde.org/). Tiene un montón de funcionalidades y opciones. Es multiplataforma, software libre y además gratuito. Es el editor que he utilizado a la hora de crear este libro web junto con el siguiente editor.
-   **[Vim](https://www.vim.org/)**: Un editor de texto multiplataforma, software libre y gratuito, que lleva ya muchos años en el mundo del software. Muy utilizado por las personas que desarrollan software. Tiene una curva de aprendizaje pronunciada, pero una vez que se aprende lo básico es muy potente. Puede aprender Vim de la manera más inteligente con [esta guía de inicialización](https://victorhck.gitbook.io/aprende-vim).
-   **[Emacs](https://www.gnu.org/software/emacs/)**: Junto con Vim otro de los editores clásicos con grandes amantes y detractores, pero sin duda una opción muy potente, aunque también con una curva de aprendizaje. Software libre, multiplataforma y gratuito.

<center>-#-</center>

<a id="Cap11">
## Personalizar Simple.css

Simple.css nos da una base para poner en marcha una página web agradable visualmente y muy limpia en diseño. Pero también ofrece bastante personalización sin tener que realizar mucho trabajo extra por nuestra parte. Utiliza un funcionalidad de CSS llamada _propiedades personalizadas_ (a menudo llamadas _variables_). Estas variables nos permiten cambiar colores y fuentes tipográficas en una web con un mínimo de retoque en el código.

### Echando un vistazo dentro de Simple.css

Vamos a abrir el archivo `simple.css` que hemos añadido previamente a nuestro sitio web, para ver a cuales variables podemos acceder. No se deje disuadir por la cantidad de código que hay guardado en el archivo. Solo nos vamos a detener en una pequeña porción. Al inicio del archivo, verá un código similar al siguiente:

```css
/* Global variables. */
:root,
::backdrop {
  /* Set sans-serif & mono fonts */
  --sans-font: -apple-system, BlinkMacSystemFont, 'Avenir Next', Avenir,
    'Nimbus Sans L', Roboto, 'Noto Sans', 'Segoe UI', Arial, Helvetica,
    'Helvetica Neue', sans-serif;
  --mono-font: Consolas, Menlo, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace;
  --standard-border-radius: 5px;

  /* Default (light) theme */
  --bg: #fff;
  --accent-bg: #f5f7ff;
  --text: #212121;
  --text-light: #585858;
  --border: #898ea4;
  --accent: #0d47a1;
  --accent-hover: #1266e2;
  --accent-text: var(--bg);
  --code: #d81b60;
  --preformatted: #444;
  --marked: #ffdd33;
  --disabled: #efefef;
}
```

Nos estamos adentrando en algunas sintaxis CSS, pero tal vez no sea tan aterrador como parece. Vamos a desglosarlo.

En CSS, el navegador ignora el texto entre `/*` y `*/`. Es una manera de escribir notas para usted mismo u otras personas que puedan leer su código, llamado _comentarios_. En este caso, los comentarios nos ayudan a separar el código en diferentes grupos relacionados.

La línea que dice `:root` significa que el siguiente bloque de código, la parte que va entre llaves, `{}`, se aplica a toda la página. De momento vamos a ignorar `::backdrop`.

Dentro de las llaves, encontramos una lista de _propiedades_. Ya vimos las propiedades de CSS en un capítulo previo. Por ejemplo, hemos utilizado `columns: 2` en la página del currículum para ajustar una lista en dos columnas. En este caso las, `columnas` son una _propiedad_ y `2` es un _valor_.

Cualquier propiedad que comience con `--` es una _propiedad personalizada_, o _variable_. Es una manera de reutilizar un valor en mútiples lugares. Por ejemplo, si tenemos una variable `--accent: blue`, podemos utilizar simultáneamente el color `--accent` en múltiples elementos. Y si incluso decidieramos configurar el color predominante en otro color, por ejemplo `rojo`, podríamos actualizarlo en un único lugar escribiendo `--accent: red`—y cada elemento que utilizara la variable `--accent` se vería actualizada automáticamente.

Mirando más arriba en el código Simple.css anterior, vemos que tenemos dos grupos de variables. Hay propiedades relacionadas con las fuentes utilizadas, seguidas de una lista de variables relacionadas con el color que representan lo que simple llama al tema "predeterminado (claro)".

Veremos las fuentes más tarde. Primero veamos los colores.

En este caso, la mayoría de las variables de color se representan como códigos hexadecimales. Todo lo que necesita saber sobre los códigos hexadecimales es que son una de varias formas de especificar un color en CSS. Vaya a casi cualquier motor de búsqueda y busque "seleccionador de color". Será recibido con un widget que puede usar para elegir un color y recuperar su código hexadecimal junto con otros formatos.

Bien, entonces, ¿cómo establecemos nuestros propios colores? ¿Los cambiamos aquí por dentro de `simple.css`? Realmente _podría hacer eso_ ya que funcionaría. Pero hay una manera mejor.

### Crear una hoja de estilo personalizada

CSS son las siglas en inglés de _Cascading Style Sheets_ en español se podría traducir por hojas de estilo en cascada. La palabra _cascading_ es particularmente útil. Para simplificar, esto significa que el orden de CSS importa, las reglas posteriores tienen preferencia sobre las reglas anteriores. Para nuestros propósitos, esto significa que podemos crear nuestro propio archivo CSS, y mientras este sea procesado por el navegador _después_ de `simple.css`, las reglas que escribamos tendrán preferencia. Así que no estamos _cambiando_ `simple.css`. Lo estamos _sobreescribiendo_.

Cree un archivo en su carpeta `assets/css` llamada `custom.css`.

Ahora, vamos a enlazarla a nuestro sitio. Necesitará hacer esto en cada página de su sitio web, pero por ahora vamos a empezar en la página principal, en el archivo en el nivel superior `index.html`. Dentro de la sección `<head>`, ya estamos haciendo referencia al archivo `simple.css` con una etiqueta `<link>`. Haremos lo mismo para nuestro nuevo archivo `custom.css` justo debajo de esa línea. Como he dicho, aquí el orden en que se llamen a los archivos importa. Queremos que nuestra nueva hoja de estilo vaya detrás de la de Simple, así podremos sobreescribir sus variables.

```html
<head>
  <title>La web de Victorhck</title>
  <meta charset="utf-8">

  <link rel="stylesheet" href="css/simple.css">
  <link rel="stylesheet" href="css/custom.css">
</head>
```
---

**Nota**

Esto funcionará solo en la página de inicio, pero no para otras páginas, recuerde actualizar la ruta al archivo de manera correcta (debería ser la misma que la ruta de `simple.css`).

---

Ahora, vamos a sobreescribir algunas variables. En nuestro archivo `custom.css`, primero vamos a establecer un bloque de código `:root` similar al de `simple.css`. Después vamos a coger una de las variables, por ejemplo `--bg` (es el color _del fondo_), y establecerlo a otro color, por ejemplo rojo, así que usaremos `red`.

```css
:root {
  --bg: red;
}
```
---

**Nota**

No hay nada misterioso sobre el nombre de la variable `--bg`. El creador de Simple.css decidió llamarlo de esa manera, así que esto es lo que necesitamos para sobreescribirla.

---

Si recarga la página en el navegador, debería ver un flameante rojo en el fondo de la página. Vamos a escoger un color algo más cómodo para leer. Puede utilizar [esta herramienta para escoger un color](https://www.google.com/search?q=color+picker) para su web, utilice uno de los muchos [colores disponibles en CSS](https://perma.cc/JF5G-REYD), o, si utiliza Visual Studio Code, utilice la herramienta propia para escoger un color al pasar el ratón sobre el valor de un color.

![En una ventana del edito Visual Studio Code, un archivo CSS llamado "custom.css" está abierto. El editor muestra una herramienta para escoger un color junto con el código que establece el color del código con la propiedad. La herramienta de escoger el color muestra varias muestras de rojo junto con sus valores RGB para que sea fácil seleccionar uno y ajustarlo.](imagenes/customizing-simple-css-1.webp)

Pero antes de escoger colores, vamos a hablar del modo oscuro.

### El modo oscuro

Simple.css admite de manera automática el uso de modos claros y oscuros basándose en los ajustes del sistema del visitante de la web. Si tiene ajustado el modo oscuro o claro en su sistema, la web se verá con diferentes colores. Si echamos un vistazo al archivo `simple.css`, podremos ver la versión de todas las variables para el modo oscuro justo debajo de las variables que hemos visto anteriormente.

```css
/* Dark theme */
@media (prefers-color-scheme: dark) {
  :root,
  ::backdrop {
    color-scheme: dark;
    --bg: #212121;
    --accent-bg: #2b2b2b;
    --text: #dcdcdc;
    --text-light: #ababab;
    --accent: #ffb300;
    --accent-hover: #ffe099;
    --accent-text: var(--bg);
    --code: #f06292;
    --preformatted: #ccc;
    --disabled: #111;
  }
  /* Add a bit of transparency so light media isn't so glaring in dark mode */
  img,
  video {
    opacity: 0.8;
  }
}
```

Este bloque utiliza una funcionalidad llamada _media queries_. En este caso la regla `@media` especifica que la regla de estilo dentro del bloque se debería utilizar si el usuario ha indicado su preferencia por el modo oscuro.

La primera regla establece el color del esquema a oscuro y entonces _redefine_ el color de las variables que se aplican al documento (por ejemplo a toda la página). La segunda regla hace que las imágenes y vídeos sean un poco transparentes, para que no sean “muy deslumbrantes en el modo oscuro.”

No sabemos si las personas que visitan nuestra web prefieren el modo claro u oscuro, así que deberíamos configurar los colores de manera adecuada para ambos modos. Si quiere, puede copiar estos dos bloques de código (por ejemplo el bloque de “Global variables” y el bloque de “Dark theme”) del archivo `simple.css` en su archivo `custom.css` y después proceder a cambiar los valores de los colores a su elección. O podría especificar solo aquellos que desee cambiar. Sea como sea, asegúrese de tener los colores correctos en la sección adecuada.

### Un ejemplo de personalización

Para el tema predeterminado claro, he decidido utilizar únicamente nombres de colores que entiende CSS como un ejercicio divertido. Puede pensar en los nombres ya establecidos como en una caja de pinturillas, hay muchas, pero no representan todos los colores posibles. Pero son una manera sencilla de referirse a un color de una manera similar a como lo hacemos entre las personas.

Y por otro lado, en el modo oscuro, necesito un toque más matizado. Utilizaré la herramienta para escoger colores de Visual Studio Code para seleccionar algunos colores muy específicos. Está representados en formato `rbg` porque es lo que escogió el editor cuando seleccione los colores.

Este es el código que he creado en mi archivo `custom.css`.

```css
:root {
  --bg: mintcream;
  --border: darkslategray;
  --accent-bg: honeydew;
  --text: darkslategray;
  --accent: mediumvioletred;
  --accent-hover: mediumvioletred;
  --marked: mediumspringgreen;
}

/* Dark theme */
@media (prefers-color-scheme: dark) {
  :root,
  ::backdrop {
    color-scheme: dark;
    --bg: rgb(17, 18, 18);
    --border: rgb(80, 90, 90);
    --accent-bg: rgb(35, 35, 36);
    --text: ghostwhite;
    --accent: lightskyblue;
    --accent-hover: lightblue;
    --marked: gold;
  }
}
```

Aquí hay una captura de las dos imágenes juntas del índice del blog de nuestra página web con los modos claro y oscuro.

![Una imagen dividida verticalmente mostrando la misma página web, pero usando dos modos de colores distintos: a la izquierda, la página se muestra con el modo claro, con colores blancos, rosas y verdes pálido. A la derecha, utilizando el modo oscuro personalizado con colores oscuros, y azul para enlaces y botones. Ambas versiones muestran el mismo contenido del índice de nuestro blog, mostrando las entradas publicadas y un pequeño resumen](imagenes/customizing-simple-css-2.webp)

### Escoger colores accesibles

Algunas combinaciones de colores pueden hacer que sea difíciles de leer debido al poco contraste entre ellos. Debe asegurarse de que hay bastante contraste entre el color del texto y el color del fondo.

Hasta cierto punto puede confiar en sus propios ojos, pero debe tener en cuenta que todo el mundo no es igual. Afortunadamente hay estándares de cuanto contraste debería tener el texto. Puede utilizar este útil [comprobador de contraste](https://perma.cc/KGB2-G7Y4). Dele dos colores y le dirá si hay suficiente contraste entre ellos.

### Cambiar la fuente tipográfica

Ya escribí sobre ello anteriormente, pero quizás ha notado un par de variables relacionadas con las fuentes y la variable de color definidas en `simple.css`. Una de ellas es, `--sans-font`, que es responsable de la mayoría del texto de la página (la otra, `--mono-font`, es utilizada para cosas como mostrar el código, como estoy haciendo en este párrafo).

Si no está familiarizado, las fuentes _sans-serif_ son aquellas que no tienen _serifas_, esas pequeñas protuberancias como pies que se encuentran en otras fuentes como Times New Roman. Simple utiliza la variable `--sans-font` para la mayor parte del texto en la página de manera predeterminada, pero se puede sobreescribir con lo que queramos.

Primero, hablemos sobre las fuentes tipográficas en la web.

### Fuentes en la web

Las personas que visiten su sitio web solo pueden ver las fuentes instaladas en sus sistemas. Eso significa que si usted, el autor de la página web, especifica en su archivo CSS alguna fuente aleatoria que descargó de un sitio web, _usted_ verá esa fuente en la página web. Pero sus visitantes verán _otra cosa_, a menos que también tengan esa fuente instalada en sus sistemas.

Ese es el motivo, por el que se especifican múltiples fuentes tipográficas en un archivo CSS. Si la primera fuente especificada no está disponible en el equipo del visitante, el navegador probará con la siguiente, y así consecutivamente.

```css
body {
  /* la primera fuente necesita el uso de comillas porque el nombre contiene espacios */
  font-family: "Some Rando Font", Georgia, serif;
}
```

El estilo anterior establece la fuente para la sección `<body>`. El navegador intentará utilizar primero “Some Rando Font.” Si no está disponible en el equipo del visitante, lo intentará utilizando Georgia. Si _esa_ tampoco está disponible, le diremos al navegador que utilice la fuente predeterminada `serif` que tenga disponible.

Esta es una buena referencia para encontrar [las fuentes más comunes encontradas en los dispositivos de las personas](https://practicaltypography.com/system-fonts.html) para ver sus opciones. Siempre es útil proporcionar un puñado de buenas opciones.

A veces, tiene una fuente que usted _realmente_ quiere que sus visitantes puedan ver aunque sabe que no la van a tener instalada en sus sistemas. Afortunadamente, hay maneras de conseguir esto. Es lo que se llama _fuentes web_. Es demasiado complejo para tratarlo aquí, pero trataré sobre ello brevemente en el próximo capítulo, [Lo básico de CSS](#Cap12). Para resumir, es un método para ofrecer de manera automática la fuente tipográfica que desea a quien visite su página web.

## Sobreescribiendo la variable de la fuente

Vamos a utilizar una fuente con serifa. Aunque el archivo css Simple llame a la variable `--sans-font`. Podemos establece la que queramos. Usaremos Georgia, que siempre es cómoda de leer.

Podemos cambiar la variable de Simple `--sans-font` dentro del bloque `:root` así se aplicará a toda la página.

```css
:root {
  --sans-font: Georgia, "Times New Roman", serif;
  --bg: mintcream;
  --border: darkslategray;
  --accent-bg: honeydew;
  --text: darkslategray;
  --accent: mediumvioletred;
  --accent-hover: mediumvioletred;
  --marked: mediumspringgreen;
}
```

Hemos especificado la fuente, Georgia, pero también ofrecemos dos opciones de respaldo. Hemos especificado Times New Roman como nuestra segunda opción. Tenga en cuenta que esta debe ir entre comillas, ya que su nombre contiene espacios.

Utilizamos una palabra clave de CSS, `serif`, para la tercera opción. Esto indica al navegador que utilice la fuente predeterminadas _serif_, cualquiera que sea. A menudo, será Times New Roman. Otras palabras clave que encuentra aquí son `sans-serif`, `monospace`, y `cursive`, [entre otras](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family#syntax)

Aquí tiene un ejemplo de un artículo del blog usando la fuente Georgia.

![Captura de un artículo del blog, titulado "Por qué el chocolate es lo mejor que existe," fechado el 20 de abril de 2024. Utilizando un tema claro personalizado. El texto se muestra en una fuente serifa en vez de en una fuente sin serifas.](imagenes/customizing-simple-css-3_es.webp)

### Hágalo a su medida

He escogido Simple.css para este libro porque hace que HTML se vea bien sin necesidad de ningún trabajo extra. Pero también lo escogí porque puede ser personalizado con unas cuantas variables CSS. Aunque solo sean los colores y las fuentes, hay un sin fín de posibilidades para que su sitio sea único.

Le animo a explorar el mundo del color y experimentar con distintas combinaciones. En el siguiente capítulo extra, trataré más aún sobre CSS y cómo ir más allá del uso de Simple.css y escribir sus propios estilos.

<center>-#-</center>

<a id="Cap12">
## Lo básico de CSS

Para este capítulo, no vamos a utilizar Simple.css en nuestro sitio. Vamos a escribir nuestros propios estilos y para ello, Voy a utilizar una página simple como ejemplo. Puede aplicar aquello que ha aprendido aquí a su Simple.css. Pero para este capítulo, quiero mostrarle desde cero cómo darle un estilo paso a paso a un sitio web.

Veremos de manera específica cómo darle estilo a los elementos tipográficos, es decir el texto para hacerlo más agradable y que la página se pueda leer de manera fluida. Pero CSS puede hacer mucho más. Es una herramienta muy potente. Si este capítulo le da alguna idea, le animo a que explore CSS más allá de lo que trataremos en este capítulo.

### Presentación de los planetas del sistema solar

He creado esta sencilla página HTML que utiliza un puñado de elementos tipográficos y presenta un buen punto de partida para aplicar estilos. Puede usar cualquier contenido que quiera si tiene algo en mente para seguir los ejemplos que veamos a continuación. Pero también puede usar la misma página HTML que usaré yo.

Puede ver el código fuente en su navegador con el [comando de ver el código fuente](https://perma.cc/3WP3-R9XL) o echando un vistazo [al código hospedado en GitLab](https://gitlab.com/victorhck/htmldemo/-/blob/main/sistema_solar.html). Y puede ver [el resultado final aquí](https://victorhck.neocities.org/sistema_solar) si quiere echar un vistazo del resultado final.

Esta página presenta los planetas del sistema solar y le da una breve información sobre cada uno de ellos. Es muy simple y básica a propósito. Es un texto sin mucha pretensión, ya que servirá de ejemplo para aplicar ciertos estilos, pero la infromación dada es correcta hasta donde yo sé.

### Punto de partida

En nuestra web de pruebas he creado un archivo llamado `sistema_solar.html` y he añadido el siguiente código dentro. Y he creado un nuevo archivo de estilos css que será el que vamos a utilizar en este apartado de pruebas para la página del sistema solar. En el archivo se asume que tiene el archivo de estilos `styles.css` en el directorio `css`. También se asume que tiene la imagen, `PIA06193~medium.jpg`, en el directorio `imagenes` junto con las imágenes que hemos utilizado en la web. Puede obtener esa imagen desde [el sitio web de la NASA](https://perma.cc/76GH-PWHQ).

HTML completo.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Planetas del sistema solar</title>
    <link rel="stylesheet" href="css/styles.css">
  </head>
  <body>
    <main>
      <h1>Planetas del sistema solar</h1>

      <p class="intro"><span class="caps">Nuestro sistema solar</span> es un lugar enorme y fascinante, que consta del sol y diversos cuerpos celestes que orbitan alrededor, incluyendo los 8 planetas mayores. Cada planeta tiene unas características únicas. En este artículo, vamos a explorar los atributos distintivos de cada planeta, ofreciendo un resumen de qué les hace únicos (y aprender un poco sobre <abbr title="siglas en inglés de Cascading Style Sheets; en español: «hojas de estilo en cascada">CSS</abbr> mientras lo hacemos).</p>

      <h2>Mercurio</h2>
      <p>
        Mercurio es el planeta mas próximo al sol y el más pequeño en nuestro sistema solar. Tiene una atmósfera muy fina y su superficie está cuviera de cráteres.
      </p>

      <h2>Venus</h2>
      <p>
        Venus es el seguno planetacercano al sol y es conocido por su espesa atmósfera tóxica y las temperaturas extremas en su superficie. A menudo es llamado como "la hermana de la tierra" por su tamaño similar y composición.
      </p>

      <h2>La tierra</h2>
      <p>
        La tierra es el tercer planeta cercano al sol y el único planeta en albergar vida. Tiene un clima diverso en su superficie, con grandes ríos, montañas y bosques.
      </p>
      <blockquote>
        <p>
          La Tierra es un escenario muy pequeño en una vasta arena cósmica. Piensa en los ríos de sangre derramados por todos aquellos generales y emperadores, de modo que en gloria y triunfo, podrían convertirse en los amos momentáneos de una fracción de un punto.
        </p>
        <cite>— Carl Sagan</cite>
      </blockquote>

      <h2>Marte</h2>
      <p>
        Marte es el cuarto planeta desde el sol, a menudo es llamado "el planeta rojo" debido a su apariencia rojiza. Tiene los mayores volcanes y cañones del sistema solar.
      </p>

      <h2>Júpiter</h2>
      <p>
        Júpiter es el quito planeta y el mayor del sistema solar. Tiene un gran punto rojo que es una gigantesca tormenta y una docena de lunas.
      </p>

      <h2>Saturno</h2>
      <p>
        Saturno, es el sexto planeta desde el sol, es famoso por su gran sistema de anillos que orbitan a su alrededor. Es el segundo planeta más grande del sistema solar.
      </p>

      <figure>
        <img src="imagenes/PIA06193~medium.jpg" alt="Este gran mosaico consta de 126 imágenes adquiridas en forma de mosaico, cubriendo un extremo de los anillos de Saturno al otro y todo el planeta en el medio.">

        <figcaption>
          Fuente: <a href="https://images.nasa.gov/details/PIA11141">https://images.nasa.gov/details/PIA11141</a>
        </figcaption>
      </figure>

      <h2>Urano</h2>
      <p>
        Urano es el séptimo planeta del sistema solar y tiene un color azul verdoso único debido al metano en su atmósfera.  is the seventh planet from the Sun and has a unique blue-green
        color due to methane in its atmosphere. Gira de lado, haciéndolo único entre los planetas.
      </p>

      <h2>Neptuno</h2>
      <p>
        Neptuno es el octavo planeta y el planeta más lejano del sol en nuestro sistema solar. Es conocido por su color azul intenso y por fuertes vientos, algunos de los más rápido del sistema solar.
      </p>

      <h2>Recursos adicionles</h2>
      <p>
        Para más información sobre los planetas, visite 
        <a href="https://solarsystem.nasa.gov/planets/overview/"
          >NASA Solar System Exploration</a
        >
        website.
      </p>

      <h2>Otros cuerpos celestes mayores</h2>
      <ul>
        <li>Plutón</li>
        <li>Ceres</li>
        <li>Haumea</li>
        <li>Makemake</li>
        <li>Eris</li>
        <li>Ganímedes</li>
        <li>Titán</li>
        <li>Europa</li>
      </ul>

      <h2>Código de ejemplo</h2>
      <pre><code>function getPlanetInfo(planet) {
    const planets = {
        Mercurio: 'El planeta más pequeño y cercano al sol.',
        Venus: 'Conocido por su atmósfera gruesa y tóxica.',
        La tierra: 'El único planeta conocido que admite vida.',
        Marte: 'El planeta rojo con el volcán más grande.',
        Júpiter: 'El planeta más grande con un gran punto rojo.',
        Saturno: 'Famoso por su sistemas de anillos.',
        Urano: 'Único por su rotación lateral.',
        Neptuno: 'Conocido por su color azul profundo y sus fuertes vientos.'
    };
    return planets[planet] || 'Planeta no encontrado';

}</code></pre>
</main>

    <footer>
      <p>
        Sitio web de prueba para aprender CSS. Parte de <a href="https://victorhck.gitlab.io/htmlparapersonas/">HTML para personas</a> por <a href="https://victorhckinthefreeworld.com/">Victorhck</a>. Eche un vistazo <a href="https://gitlab.com/victorhck/htmlparapersonas">al código fuente en GitLab</a>.
      </p>

  </body>
</html>
```

Como el archivo `styles.css` está vacío, tendremos únicamente los estilos predeterminados del navegador. Este es el aspecto que tendría:

![Captura de pantalla de un navegador mostrando una página web llamada, "Planetas del sistema solar." Cada planeta tiene una breve descripción resaltando sus caracterísiticas únicas. La página utiliza solo el estilo del navegador predeterminado y está por completo sin estilo.](imagenes/css-basics-01_es.webp)

El viejo Times New Roman y líneas de texto que ocupan todo el ancho de la ventana del navegador. No se ve muy bien, pero tiene algo agradable y pintoresco. Y, lo que es más importante, no está roto. Muchos sitios están exagerados con diseños extravagantes, megabytes de imágenes y JavaScript, y comportamientos hostiles para el usuario (ya sabe, como, "Veo que solo ha leído dos frases de este artículo, pero sé que debe estar muriendo por suscribirse a mi boletín, así que déjeme mostrarle esta ventana emergente gigante de aquí").

Así que vamos a imaginarnos a nosotros mismos como una especie de médicos web. Primero, no haremos ningún daño. Mejoraremos la legibilidad de la página y la haremos bonita (bueno, lo que yo creo que es bonito, de todos modos, siéntase libre de divergir y agregar sus propios estilos a medida que avanzamos). Pero nos abstendremos de hacer algo tan drástico que haga que la página sea más difícil de leer de lo que es ahora.

### La etiqueta estilo

Podemos escribir el código CSS directamente en nuestro archivo `html` utilizando la etiqueta HTML especial, `<style>`. Podemos poner la etiqueta `<style>` dentro de la sección `<head>` en nuestro fichero, así:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mi sitio web</title>
    <meta charset="utf-8">

    <style>
      el código CSS iría aquí
    </style>
  </head>

  <body>
    ...
  </body>
</html>
```

Esto es perfectamente válido, pero si tiene más de una página en su sitio web, debería copiar y pegar el contenido de la etiqueta `<style>` en cada página para tener el mismo estilo en cada página. En vez de eso, lo más común es poner todo el código CSS en un archivo separado como hemos venido viendo hasta ahora y después _enlazarlo_ mediante la etiqueta `<link>` en cada página de la sección `<head>` de su sitio web.

```html
<link rel="stylesheet" href="styles.css">
```

### Primeros pasos para mejorar la página

En mi caso crearé un archivo llamado `styles.css`. Y es en ese archivo donde escribiré todo mi CSS personalizado desde cero. En el código HTML deberemos incluir una etiqueta `<link>` en la sección `<head>` para enlazar ese estilo a la página, como hemos visto anteriormente.

Podemos conseguir grandes mejoras con únicamente un par de líneas de CSS. Por ejemplo, uno de los problemas es que la página es demasiado de ancha en la ventana del navegador en nuestro equipo de escritorio. Las líneas largas son difíciles de leer. Vamos a solucionar eso dándole a la página un máximo de anchura. De acuerdo con [Butterick’s Practical Typography](https://practicaltypography.com/line-length.html), deberíamos ser capaces de meter entre uno y dos alfabetos en una única línea. En mi caso voy a configurar el ancho a 65 _caracteres_.

```css
main {
  max-width: 65ch;
}
```

Esta _regla_ CSS se refiere al elemento `<main>` de nuestra página y le obliga a no exceder nunca del ancho establecido.

---

**Nota**

Vale, no son [estrictamente 65 caracteres de ancho](https://perma.cc/66QM-Q2AF). La unidad `ch` en CSS está basada en cómo es de ancho el caracter `0` (cero) en la fuente especificada. Así que realmente estamos diciendo. "No dejes que el ancho de la página sea mayor de 65 caracteres `0`.”

---

Ignorando la imagen enorme de Saturno, que en un momento nos pondremos con ella, ahora tiene otro aspecto y ya ha mejorado bastante. Pero la tendencia actual es preferir el texto centrado en la página, así que vamos a establecer eso ahora mismo.

```css
main {
  margin-inline: auto;
  max-width: 65ch;
}
```

En los idiomas que leemos de izquierda a derecha como el Español, `margin-inline` es el margen horizontal, o izquierdo y derecho. Estableciéndolo a `auto`, le estamos diciendo, "no me importa cómo son de anchos los mágenes izquierdo y derecho, simplemente haz que sean iguales." El navegador conoce cómo queremos que sea de ancha la página, así que calculará el margen necesario para que sean iguales en ambos lados, centrando el texto.

También tenemos un elemento `<footer>` que reside fuera del elemento `<main>`, así que vamos a darle un estilo separado con el mismo ancho y el mismo margen.

```css
footer {
  margin-inline: auto;
  max-width: 65ch;
}
```

Y continuando con esto, vamos a hacer que la imagen de Saturno no sobresalga de la página.

```css
img {
  max-width: 100%;
}
```

El código `max-width` puede ser entendido como un porcentage de su elemento que contiene. Estableciéndolo al 100% significa, "No dejes que las imágenes del elemento sean mayores que sus contenedores".”

Y ahora nuestra página ya tiene un aspecto mucho más agradable.

![La misma página que la captura anterior, pero ahora el texto está centrado y tiene una anchura más adecuada que lo hace más sencillo de leer.](imagenes/css-basics-02_es.webp)

### Anatomía de una regla CSS

Eche un vistazo a una de las reglas que hemos visto. Esta regla limita el ancho de las imágenes al ancho de sus contenedores.

```css
img {
  max-width: 100%;
}
```

Vamos a diseccionar el comando en dos partes. Primero, especificamos a qué elementos de la página va a afectar. Esa es la parte que va antes de las llaves (`{}`). A eso se le llama el _selector_ porque _selecciona_ los elementos en la página que van a verse afectados.

La parte dentro de las llaves es donde vamos a poner las propiedades que queremos cambiar. Cada declaración consiste de una _propiedad_ y un _valor_. En este caso hay una declaración. La propiedad es el ancho `max-width`, y el valor es `100%`.

### Tamaño del texto, altura de las líneas y espaciado entre los elementos

El tamaño predeterminado de la fuente es un poco pequeño. Modificaré todo el elemento `html` (es decir, el documento entero) para establecer el tamaño de la fuente `font-size` y la altura de la línea `line-height`.

```css
html {
  font-size: 20px;
  line-height: 1.45;
}
```

Una de las unidades que podemos utilizar para dar el tamaño de las cosas es la unidad del pixel, `px`. Acabo de aprender que `1px` equivale a 1/96 de pulgada (aunque eso varía con la densidad de píxeles del monitor). ¡Vaya! Nunca deja uno de aprender.

Hay muchas maneras de establecer el tamaño del texto. Veremos algunas formas más en un momento.

Estableceré la altura de línea `line-height` utilizando un valor sin unidades de `1.45`. Este es un número que parece estar bien. Consulte [Butterick’s Practical Typography](https://practicaltypography.com/line-spacing.html) y tu propio gusto para encontrar una altura aceptable que especificar para tu fuente. Estoy utilizando un número sin unidades en vez de algo como píxeles `px` debido a [cómo los elementos secundarios heredarán dicho valor](https://perma.cc/7YVZ-53XL), pero por ahora no es necesario que se preocupe mucho sobre esto.

Continuando, me gustaría asegurar que los elementos tienen un espaciado igual entre ellos. Apuntaré a todo lo que esté dentro del elemento `<main>` utilizando un selector universal, el asterisco (`*`).

```css
main * {
  margin-block-start: 0;
  margin-block-end: 1rem;
  /* o podríamos utilizar la sintaxis acortada de la siguiente manera */
  margin-block: 0 1rem;
}
```

Un selector puede ser una cadena de elementos. Por ejemplo, `main p` selecciona cada elemento `<p>` _dentro_ del elemento- `<main>`. Pero quiero apuntar a _todo_ en el elemento `<main>` , así que utilizo el asterisco.

Estoy estableciendo el margen superior e inferior de cada elemento. De manera similar a `margin-inline`, que controla el espaciado horizontal entre los elementos, `margin-block` controla el espaciado vertical entre los elementos (en idiomas que se escriba y lea de izquierda a derecha). Estoy estableciendo el margen superior de los elementos a `0` y el margen inferior a `1rem`. La unidad `rem` es equivalente al tamaño de la fuente del elemento **r**oot el**em**ent (el elemento `<html>`). Como he establecido el tamaño de la fuente de _root_ en `20px`, ese será el valor que tomará `1rem`.

Lo genial de la unidad `rem` es que, al permitirnos basar los valores en el tamaño de fuente del documento, hace que nuestros diseños se sientan más cohesivos.

El aspecto de nuestro texto ahora es más elegante.

![La misma imagen que antes, pero ahora el texto es un poco más grande con un interlineado mayor.](imagenes/css-basics-03_es.webp)

No tengo nada en contra de la fuente Times New Roman, pero tiene un aspecto muy... _de serie_. Podemos mejorarlo y de paso aprender algo más.

### Instalar fuentes tipográficas web

Puede utilizar una fuente, solo si las personas que visitan la web la tienen disponibles en sus dispositivos. Mientras que existen algunas [fuentes del sistema comunes](https://practicaltypography.com/system-fonts.html) y [fuentes predeterminadas comunes](https://perma.cc/9BMG-EMTU), tenemos otra opción para personalizar las fuentes tipográficas. _Las fuentes web_ son aquellas que están disponibles siendo descargadas junto con la descarga de su sitio web. Además de el documento HTML, el archivos CSS, archivos JavaScript, imágenes y otros, las fuentes personalizadas también pueden ser descargadas.

Las fuentes web fonts necesitan estar en un formato específico, e _instaladas_ de una cierta manera, a falta de un término mejor. a certain way, for lack of a better term. Lo normal, es que la gente utilice un servicio como [Google Fonts](https://fonts.google.com/) (gratuito) o [Adobe Fonts](https://fonts.adobe.com) (de pago). Hay un [montón](https://typography.com/webfonts) de [opciones](https://typenetwork.com/), incluyendo alojar las fuentes en su propio servidor junto a los demás archivos del sitio web. Solo debe asegurarse de que la licencia lo permite.

Por simplicidad, utilizaremos un par de fuentes de Google Fonts. Diríjase a [fonts.google.com](https://fonts.google.com). Busque por for “Oswald” y selecciónelo de entre los resultado. Después haga clic en _Get font_.

![Captura de pantalla del sitio web Google Fonts mostrando la fuente "Oswald." El botón "Obtener fuente" está resaltado con una flecha roja. En el texto de prueba inferior se puede leer, "Whereas disregard and contempt for human rights have resulted." El menú del sitio está visible a la izquierda.](imagenes/css-basics-04.webp)

Después de seleccionarlo, no lo descargue todavía. Haga una búsqueda de “source sans.” Source Sans 3 es la versión disponible en el momento de escribir este artículo. Selecciónelo y haga clic en _Get font_.

Cuando tenga las dos fuentes seleccionadas, haga clic en _Get the code_. Estamos buscando el bloque etiquetado _Embed code in the `<head>` of your html_.

![Captura de pantalla de la interfaz de Google Fonts mostrando los detalles de la fuente "Source Sans 3" . Hay un botón con el texto "Copiar código" dentro de un rectángulo que lo resalta que muestra el código HTML para insertar. La interfaz incluye opciones de estilo de la fuente e instrucciones de uso.](imagenes/css-basics-05.webp)

Copie y pegue el código en la sección `<head>` de su sitio web.

```html
<head>
  <meta charset="UTF-8">
  <title>Planetas del sistema solar</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Oswald:[email protected]&family=Source+Sans+3:ital,wght@0,200..900;1,200..900&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
```

En el archivo css añada una declaración `font-family` en el bloque `html` para comprobar que está funcionado. Guarde ambos documentos, el css y el html.

```css
html {
  font-family: 'Source Sans 3', sans-serif;
  font-size: 20px;
  line-height: 1.45;
}
```

Esto establecerá la fuente en todo el documento. El navegador primero intentará usar Source Sans 3. Si por cualquier razón, la fuente no está disponible (digamos por ejemplo que el sitio Google Fonts está caído), entonces `sans-serif` le dirá al navegador que utilice cualquier fuente de tipo sans-serif que esté disponible. Puede añadir otras fuentes de respaldo en _font stack_. Simplemente separe las opciones con comans, como ha visto en el ejemplo anterior.

Actualice la página, ¡y debería mostrarse la nueva fuente! Pero todavía vamos a mejorarlo un poco más integrando adecuadamente ambas fuentes.

### Ajustando los colores y las variables

Si ha leído el capítulo [Personalizando Simple.css](#Cap11), recordará que utilizaba variables CSS para controlar el color y las fuentes. Vamos a realizar eso mismo en nuestro ejemplo. Esto hará que sea más sencillo personalizar las cosas más adelante (que quizás quiera hacerlo una vez que aprenda y si no le gustan mis opciones).

```css
:root {
  --text-color: #303036;
  --muted-text-color: #5e5e67;
  --heading-color: #cd2807;
  --link-color: #028090;
  --background-color: #fffdf7;

  --heading-font: 'Oswald', sans-serif;
  --body-font: 'Source Sans 3', sans-serif;
}
```

Puede nombrar las variables como quiera, siempre que comiencen con `--`. En el ejemplo anterior, estoy estableciendo varios colores y un par de fuentes.

Una vez que ha definido las variables, puede utilizarlas para aplicar esas fuentes y colores en el texto.

```css
html {
  font-family: var(--body-font);
  font-size: 20px;
  line-height: 1.45;
  color: var(--text-color);
  background-color: var(--background-color);
}
```

Utilice la función `var` para utilizar las variables creadas.

### El estilo de los encabezados

Estoy utilizando `<h1>` para el título de la página y `<h2>` para los subencabezados. Vamos a fijarnos en estos elementos y vamos a aplicarles un poco de estilo.

```css
h1 {
  border-block-start: 10px solid var(--heading-color);
  margin-block-start: 4rem;
  margin-block-end: 2rem;
  font-family: var(--heading-font);
  font-weight: normal;
}

h2 {
  margin-block-start: 1.5rem;
  margin-block-end: 0.5rem;
  font-family: var(--heading-font);
  font-size: 1.2em;
  font-weight: normal;
  color: var(--heading-color);
}
```

Estoy haciendo varias cosas aquí. Estoy añadiendo un pequeño margen extra superior a los elementos `<h2>` y un poco de espacio extra sobre `<h1>`.

Me gusta el aspecto que tiene Oswald, la fuente que estoy utilizando para los encabezados, sin estar en negrita. Así que estoy estableciendo `font-weight` a `normal` en vez de `bold`, que es la opción predeterminada para los encabezados.

---

**Nota**

Estamos utilizando [fuentes variables](https://perma.cc/A75H-V4HJ), así que tenemos más opciones que `normal` o `bold`. Trate de utilizar valores de 300, 500, 900 [y otros](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight).

---

Para `<h1>`, mantengo el tamaño `font-size` predeterminado. Para `<h2>`, estoy estableciendo el tamño `font-size` a `1.2em`, que es lo mismo que decir 1.2 veces el _tamaño actual de la fuente_.

Unos cuantos cambios en la tipografía han transformado nuestra página, y ahora tiene un aspecto totalmente diferente.

![La página web titulada "Planetas del sistema solar" ha recibido una actualización en el diseño. La fuente ha sido cambiada y los colores de las funetes actualizados. El fondo también ha sufrido alguna actualización para completar los cambios realizados. El encabezado ahora tiene un borde superior en color rojo, La apariencia es más pulida y mejora diseñada.](imagenes/css-basics-06_es.webp)

Podríamos parar aquí. Ya todo parece que tiene buen aspecto. Pero vamos a seguir dando estilo a nuestro sitio modificando algunos elementos de los que todavía no hemos tocado.

### Enlaces

Si está utilizando mi documento HTML, notará que existen algunas etiquetas `<a>` o hipervínculos o enlaces. Uno apunta a la fuente donde obtener la imagen de Saturno al sitio web de la NASA. Y los demás están en el pie de página.

Vamos a darles un poco de estilo. He escogido un color azul verdoso y vamos a configurarlo en una variable, como hemos aprendido antes.

```css
:root {
  /* ... otro código ... */

  --link-color: #028090;

  /* ... otro código ... */
}
```

Utilizaré eso para establecer el color de todos los elementos `<a>`:

```css
a {
  color: var(--link-color);
}
```

Estamos muy acostumbrados a relacionar un texto azul subrayado con un enlace en el que hacer clic, así que he decidido no desviarme mucho de ese patrón. Pero me gustaría añadir un pequeño efecto de hacer desaparecer el subrayado cuando el curso se pone encima del enlace.

Utilizaré el selector `:hover` _pseudo-class_ pra conseguir ese efecto. Estos selectores se utilizan normalmente para dar estilo a elementos en diferente estados, por ejemplo en nuestro caso un enlace sobre el que el puntero del ratón pasa por encima.

```css
a:hover {
  text-decoration: none;
}
```

La propiedad que queremos es `text-decoration`. De manera predeterminada, los enlaces tienen una decoración del texto `text-decoration` de un `subrayado`. Tiene [algunas opciones](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration) en este enlace, pero voy a escoger `none`.

Esto nos da una sutil interacción con el enlace.

![El vídeo muestra una grabación del efecto anterior, pasando el cursor por encima del enlace y viendo cómo el subrayado desaparece y reaparece cuando lo hago.](imagenes/css-basics-1_es.mp4)

### Abreviaturas

Sobre el tema de los efectos al pasar el ratón por encima de una parte del texto, hay uno del que quizá no se ha dado cuenta. Si echa un vistazo al código HTML de nuestra página de demostración en el primer párrafo, puede leer la siguiente frase.

```
En este artículo, vamos a explorar los atributos distintivos de cada planeta ofreciendo un resumen de qué los hace únicos (y aprender un poco de <abbr title="Cascading style sheets">CSS</abbr> mientras lo hacemos.
```

La etiqueta `<abbr>` ayuda a la persona que visite nuestra web a conocer qué significa cierta abreviatura o acrónimo que usemos en nuestro texto. Cuando pasa el puntero del ratón por encima del texto CSS en la página, verá un pequeño recuadro que mostrará una ayuda útil mostrando a qué se refiere. Ponga la abreviatura dentro de las etiquetas, después utilice el atributo `title` para el texto completo.

Vamos a dar un poco de decoración de texto `text-decoration` para dar pistas al visitante de que puede interactuar con ese elemento.

```css
abbr {
  text-decoration: underline;
  text-decoration-style: dotted;
  text-decoration-color: var(--heading-color);
  text-decoration-thickness: 2px;
}
```

Le estamos dando un subrayado, similar al que tienen los enlaces. Pero haremos que tenga un color rojizo similar al que utilizamos en los encabezados y utilizaremos en estilo punteado o `dotted` para ayudar a diferenciarlo de un enlace. He decidido incrementar el grosor un poco, para hacerlo más fácil de ver.

### Bloque de citas

No puedo dejar pasar la oportunidad de compartir una cita de Carl Sagan en un artículo sobre el sistema solar, incluso como en este caso que solo es un artículo de prueba. Así que incluiré un extracto épico de en esta sección sobre la tierra.

Tiene buen aspecto tal como se ve, tiene una sangría mayor y tiene el aspecto de una cita. Pero sin duda podemos mejorarlo. Priemero le enseñaré el código y después le explicaré qué estoy haciendo.

```css
blockquote {
  margin-inline: 1.5rem 0;
  border-inline-start: 4px solid var(--heading-color);
  padding-inline: 1rem;
  font-size: 0.9rem;
  color: var(--muted-text-color);
}
```

Quiero controlar la sangría y hacerla más coherente basándola en el tamaño de la fuente del documento. En los idiomas en los que se lee y escribe de izquierda a derecha, `margin-inline` controla los márgenes izquierdo y derecho. Estoy proporcionando dos valores, `1.5rem` y `0`, para especificar los márgenes izquierdo y derecho, respectivamente. El margen izquierdo será 1.5 veces el tamaño de la fuente del documento, y eliminaré el margen derecho por completo.

Un diseño muy común que se suele hacer al elemento de `<citas>` es element is darle un borde en el margen izquierdo para que resalte. No veo razón para no hacerlo en este camso también, así que crearemos un borde por el lado izquierdo utilizando `border-inline-start`. Recuerde, `inline` se refiere al eje horizontal. Y `start` significa el primero (que para mí es el lado _izquierdo_; `end` debería ser el lado derecho).

Lo estableceré para que sea una línea con relleno y con un ancho de `4px` y que utilice el color de los encabezados, que hemos establecido como el color principal de nuestra paleta.

Pero tenemos un problema. Si lo dejamos aquí, tendremos un borde que choca contra el texto. Vaya, eso no está bien.

![Imagen que contiene un texto que ofrece una breve descripción de la tierra, incluyendo containing text that provides a brief description of Earth, incluyendo un bloque de cita de Carl Sagan mal estilizado en el que el borde izquierdo toca el texto.](imagenes/css-basics-08_es.webp)

Afortunadamente podemos solucionar esto añadiendo espaciado con `padding`. Le daré una pequeña explicación sobre [_el modelo de caja_](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model). Cada elemento tiene un espacio por fuera de él (margen), un espacio alrededor por dentro (padding o relleno) y una capa opcionar que separa las dos (el borde).

Con estos datos, vamos a añadir un poco de espacio _dentro_ del elemento, que alejará el contenido del borde. Vamos a establecer ese espacio por la izquierda y derecha el mismo para los dos configurando `padding-inline` a un valor de `1rem`, que es el equivalente al tamaño de fuente del documento.

Finalmente, haremos que el tamaño de la fuente sea ligeramente más pequeño y el color del texto un poco más claro. El resultado final es un bloque de cita con un buen aspecto y buen diseño.

![La misma imagen del bloque de cita anterior, pero ahora espaciando entre el borde y el texto es mayor el tamaño de la fuente se ha reducido un poco y el color del texto se ha modificado sutilmente para que sea un poco más claro, casi gris.](imagenes/css-basics-07_es.webp)

Diseñé este estilo de bloque de cita para que se adaptara a la mayoría de los casos de uso, pero podría ir en otra dirección: por ejemplo con un texto grande en cursiva, por ejemplo.

### Listas

Vayamos ahora a modificar un poco las listas sin orden, que en nuestro caso muestra Plutón y otros elementos del sistema solar. Vamos a dar a la lista un poco de sangria, como es común en las listas. Recuerde, HTML también posee listas numeradas. No estamos utilizando de ese tipo en nuestra página (si está utilizando mi ejemplo de HTML), pero podríamos también escribir el estilo para ambos tipos de listas.

Ya sabe que el selector apunta a los elementos a los que queremos darles un estilo. Pero también pueden tener múltiples selectores. Podemos apuntar al elemento `<ul>` y al elemento `<ol>` y darles a ambos la misma sangría haciendo lo siguiente.

```css
ul, ol {
  padding-inline-start: 1.5rem;
}
```

Ha añadido múltiples selectores separándolos con una coma. Esto crea una _lista selector_. El espaciado que estamos utilizando para conseguir dicha sangría del texto será aplicado tanto a _listas sin orden_ (las que detallan cada elemento con un pequeño punto) y _listas ordenadas_ (cada elemento va precedido de un número).

También vamos a ajustar el espaciado entre cada _elemento de la lista_ (elementos `<li>`). Me gusta usar el espaciado de la mitad de lo que estoy usando para los párrafos porque quiero que los elementos de la lista estén más juntos que los párrafos, pero aún con un poco de espacio entre ellos. Como utilicé `1rem` para el espaciado de mis párrafos y otros elementos, utilizaré la mitad de eso, `0.5rem`, para el margen inferior.

```css
li {
  margin-block: 0 0.5rem;
}
```

Recuerde, `margin-block` es el margen superior e inferior en idiomas como el español que se lee y escribe de derecha a izquierda. Podemos establecer ambos valores al mismo tiempo. El superior es equivalente a:

```css
li {
  margin-block-start: 0;
  margin-block-end: 0.5rem;
}
```

Esto significa, para los idiomas que se escribe y lee de izquierda a derecha, que el margen por encima del elemento de la lista es cero y el margen por debajo es de unos diez píxeles (`0.5rem` significa 0.5 veces el tamao de la fuente de **r**oot el**em**ent, que nosostros definimos como `20px`).

El espaciado debería verse bastante bien ahora, pero hagamos algo que pondría celosos a los diseñadores web de la década de 2000. Cambiemos el color de los puntos que preceden cada elemento. En aquella época esto solía ser complicado, pero ahora es sencillo.

```css
li::marker {
  color: var(--heading-color);
}
```

El código `::marker` es llamado un _pseudo-elemento_ porque representa una pieza de un elemento HTML. Dicho `::marker` es parte del _elemento de la lista_ o elemento `<li>`. Contiene un punto (o número) del elemento de la lista. Podemos apuntarlo con nuestro selector y cambiar el color a nuestro color de encabezado rojo.

![Captura de pantalla de una lista en la que cada elemento tiene un pequeo punto delante. La lista se titula "Otros cuerpos celestes" que incluye los elementos Plutón, Ceres, Haumea, Makemake, Eris, Ganímendes, Titán y Europa. Tiene más espacioado entre los elementos de la lista, haciendola sencilla de leer. Los puntos iniciales son rojos, mientras que el texto tiene el mismo color oscuro del texto.](imagenes/css-basics-09_es.webp)

¡Tiene un aspecto genial!

### Texto preformateado

La mayoría de las veces, en nuestros documentos HTML, no nos preocupamos por preservar el espaciado exacto de todo. De hecho, eso sería contraproducente, ya que normalmente sangramos HTML o incluimos líneas vacías para que el código sea más legible. Pero a veces, queremos mostrar el texto exactamente como está formateado. Algunos ejemplos son el arte ASCII y el código informático.

Normalmente mostramos este tipo de texto con la etiqueta `<pre>` en HTML. Preserva todo el espaciado y utiliza una fuente monoespaciada para darle un aspecto consistente. A menudo es combinado con la etiqueta `<code>` para señalar que el texto es código de algún lenguaje de programación He eincluido código en JavaScript relacionado de alguna forma con los planetas simplemente como ejemplo.

Vamos a darle estilo a la etiqueta `<pre>` de la siguiente manera.

```css
pre {
  padding: 1rem;
  background-color: #edebe7;
  border-radius: 4px;
  overflow-x: auto;
  font-size: 0.75rem;
}
```

Queremos que el código aparezca como si estuviera dentro de un contenedor, por lo que proporcionaremos relleno en todo su contenedor. A continuación, estableceremos un color de fondo claro que sea visible contra el fondo de nuestra página, pero no tan oscuro como para dañar el contraste del texto. Las puntas afiladas de las esquinas se ven un poco antinaturales, así que añadiremos `border-radius`, que es un elegante término para establecer cómo de redondas queremos las esquinas.

Podríamos tener largas líneas de código, por lo que debemos especificar qué debe suceder si una línea de código desborda el lado del contenedor. En este caso, lo estableceremos a `auto`, que hará que el navegador muestre una barra de desplazamiento horizontal en el elemento si fuera necesario.

Finalmente, el código monoespaciado puede parecer grande, por lo que lo reduciremos diciendo que debe tener tres cuartas partes del tamaño de texto estándar.

![El ejemplo de una función de JavaScript ha sido tratado con un fondo un poco gris de puntas redondeadas y muestra una fuente monoespaciada. Esta función toma el nombre de un planeta como entrada y devuelve información sobre el planeta.](imagenes/css-basics-10_es.webp)

### Un mejor estilo para las imágenes

Este es el aspecto que tiene ahora mismo nuestra imagen de Saturno.

![La imagen de Saturno, el secto planeta en el sistema solar, mostrando su extensivo sistema de anillos. El planeta se muestra con una porción de su superficie en sombra y los anillos parcialmente iluminados. El texto sobre la imagen ofrece información obre Saturno. La imagen es más estrecha que la columna de texto, tiene unas proporciones rectangulares con las 4 esquinas terminadas en punta.](imagenes/css-basics-11_es.webp)

No está mal, pero parece que la etiqueta `<figure>` está añadiendo un margen por cada lado. Quiero que la imagen ocupe todo el ancho de la columna. También quiero que el pie de foto sea un poco más pequeño.

```css
figure {
  margin-inline: 0;
}

figure img {
  display: block;
  margin-inline: auto;
  border-radius: 4px;
}

figcaption {
  margin-block-start: 0.5rem;
  font-size: 0.8rem;
}
```

Eliminaremos el margen propio de `<figure>`. Así que apuntaremos a las imágenes que están dentro de _figures_ (solo tenemos una, pero podría ser un buen patrón a utilizar su tuviéramos varias) para ello haremos lo siguiente:

-   Establecer `display` a `block`. Las imágenes se establecen a `inline` de manera predeterminada, pero el comportamiento de `block` funciona más como esperarías que funcionara una imagen como esta.
-   Establecer el margen propio a `auto` en caso de que usemos una imagen más pequeña que el ancho de la página, estará centrada en ese caso.
-   Establecer `border-radius` a `4px` eso redondeará las esquinas de la imagen solo un poco.
-   Finalmente, reduciremos el margen por encima del pie de página y reduciremos el tamaño de la fuente con `font-size` al 80% del tamaño de la fuente del documento.

![La misma imagen de Saturno anterior, excepto que ahora el maren ha sdo eliminado y las esquinas de la imagen han sido redondeadas un poco.](imagenes/css-basics-12_es.webp)

¡Ah quedado muy elegante! Unos pequeños ajustes pueden hacer una gran diferencia.

### [El pie de página](https://victorhck.gitlab.io/htmlparapersonas/css-basics#the-footer)

Ya hemos establecido un estilo para el pie de página anteriormente, establecimos el ancho para asegurar que estuviera centrado. Pero podemos mejorar el aspecto general dándole algo más de espacio, dándole un borde superior, reduciendo el texto y usando un color de texto un poco más apagado.

```css
footer {
  margin-block-start: 3rem;
  margin-inline: auto;
  padding-block: 1.5rem 3rem;
  border-block-start: 2px solid var(--heading-color);
  max-width: 65ch;
  color: var(--muted-text-color);
}
```

Algo de esto ya debería serle familiar. Hemos creado un margen superior del elemento con `margin-block-start`. Hemos añadido un borde de `2px` de ancho sobre el pie de página utilizando el mismo color rojo que estamosutilizando en toda la página. Añadiendo `padding-block`, estamos añadiendo algo de espacio entre el texto y el borde we’re adding some space between the text and the border y una buena cantidad de relleno a continuación para proporcionar espacio para respirar en la parte inferior de la página. Finalmente, usaremos el mismo color de texto apagado que usamos en el bloque de cita.

Como ya hemos añadido el margen que queremos al elemento `<footer>`, ahora vamos a eliminar el margen del contenido _dentro_ del pie de página. Utilizaremos a nuestro conocido selector universal (`*`).

```css
footer * {
  margin: 0;
  font-size: 0.9rem;
}
```

Este selector apuntará a todo _dentro_ de la etiqueta `<footer>`. Estableceremos el `margin` a `0` y reduciremos el texto al 90% del tamaño de la fuente del documento.

## Un extra de diversión tipográfica

Ya podríamos finalmente parar aquí, _pero_… vamos a divertirnos un poco.

Mirando el primer párrafo del texto, le asigne una clase de `intro`. Vamos a darle un poco de énfasis haciendo que el texto sea un poco más grande.

```css
.intro {
  margin-block-end: 2rem;
  font-size: 1.2em;
}
```

Cuando colocamos un punto antes de un término en un selector CSS, eso significa que queremos apuntar a cada elemento que tenga esa clase (en este caso es una clase `intro`). Esto hará más grande que el tamaño predeterminado del documento el tamaño de fuente `font-size`. Y con la fuente más grande, necesita un margen extra debajo.

Bien, genial, pero ahora vamos _a por algo extra_. Eche un vistazo al código de nuevo, y verá que he encerrado ls tres primeras palabra en una etiqueta `<span>` con una clase de `caps`.

```css
.caps {
  text-transform: uppercase;
  font-size: 0.78em;
  font-weight: 600;
  letter-spacing: 0.1em;
}
```

Esto nos dará ese elegante efecto literario en el que las primeras palabras están en [versalitas](https://es.wikipedia.org/wiki/Versalita). Por lo general, querrá usar una fuente con [versalitas adecuadas](https://practicaltypography.com/small-caps.html), pero podemos hacer una falsificación decente ya que Source Sans 3 es una fuente variable.

La declaración `text-transform` hará que las letras se muestren en mayúsuclas. Es mejor ahcer eso con CSS en vez de forma manual escribiendo eso en mayúsculas, ya que es algo que está relacionado con el estilo y diseño. Para el tamaño de fuente `font-size`, he estado jugando un poco hasta que me ha parecido adecuado. Principalmente, quiero que las mayúsculas tengan la misma altura que el texto de las minúsculas de la introducción (es decir, la [altura de la x](https://es.wikipedia.org/wiki/Altura_de_la_x)).

Para ayudar a que todo esté más equilibrado, voy a incrementar el peso de la fuente con `font-weight` un poco. Además de los valores de `normal` y `bold`, puede utilizar valores numéricos 100 a 900 si la fuente lo admite, y nuestra fuente variable sí que lo admite.

Por último, se beneficia de aumentar el espacio entre las letras cuando se utilizan todas las mayúsculas. Estoy utilizando la unidad `em`, que está basada en el actual tamaño de fuente `font-size`. Esto es útil porque si cambia el valor de `font-size` en el futuro, el espaciado también cambiará de manera proporcional.

![Captura del título de Panetas del sistema solar. El texto que hay por debajo describe el sistema solar. Se ha aumentado el tamaño del texto y la primera frase del párrafo se ha escrito en versalitas.](imagenes/css-basics-13_es.webp)

¡Y ya lo tenemos! Desde sus humildes comienzos como una página _austera_ y sin estilo con un atractivo pintoresco, ahora parece un artículo autorizado.

### Potencial sin limites

Estos son solo los estilos que elegí según mis preferencias. Podría ir en todo tipo de direcciones diferentes. No estoy necesariamente tratando de imponerle un estilo, aunque sí le señalé algunos principios tipográficos generalmente buenos a seguir. Solo quería darle una muestra de cómo puede aplicar sus propios estilos a una página.

La magia de CSS es que podría tomar una copia exacta de mi código HTML y crear un diseño completamente diferente desde elmismo punto de partida. Esa es la premisa de un experimento web llamado [CSS Zen Garden](https://csszengarden.com/), donde las personas envían sus diseños basados en un código idéntico.

![Captura de pantalla de dos páginas web procedentes del proyecto llamado CSS Zen Garden project. La página de la izquiera se muestra colorida, con un diseño vibrante con colores rosas, violetas y naranjas. La página de la derecha tiene un diseño minimalista y limpio con un gris claro de fondo y un texto en azul. Ambas imágenes muestran las posibilidades del diseño utilizando CSS.](imagenes/css-basics-14.webp)

Estos dos diseños comparten el mismo código HTML. [Son la misma fotografía.](https://www.youtube.com/watch?v=Iloby6ZXRjI)

Espero que este capítulo extra le haya dado una idea de lo que es posible con CSS. Al igual que con HTML, incluso un poco de conocimiento de CSS es valioso: un simple cambio de fuente y color, por ejemplo, puede marcar una gran diferencia. Le animo a que siga explorando CSS si quiere crear diseños personalizados. Es una habilidad gratificante.

<center>-#-</center>

<a id="Cap13">
## Reutilizar HTML with PHP

A lo largo de este libro, una cosa molesta a la que hemos tenido que enfrentarnos es actualizar el menú de navegación en cada página cada vez que cambiamos algo en el menú. Imagínese si no tuviéramos que hacer eso y, en cambio, pudiéramos mantener nuestro menú de navegación en un solo lugar, en un archivo, y hacer que aparezca mágicamente en cada página.

Eso es lo que haremos en este capítulo extra con la ayuda de PHP. PHP son las siglas de _PHP: Hypertext Preprocessor_. Sí, es un [acrónimo recursivo](https://es.wikipedia.org/wiki/Acr%C3%B3nimo_recursivo), porque el acrónimo es parte del nombre, lo que es bastante friki. Pero en la época en la que se creó, eran las iniciales de _Personal Home Page_ o Página de Inicio Personal, ya que inicialmente ese fue su uso.

PHP es un lenguaje de programación presente en la mayoría de la web, principalmente porque el gestor de contenido, [WordPress](https://wordpress.org/), fue creado con ello. PHP es un lenguaje de programación completo, lo que significa que puede hacer casi cualquier cosa. _Hypertext preprocessor_ o preprocesador de hipertexto, es una buena descripción de lo que hace.

Cuando visita un sitio web _estático_, como los que hemos hecho en este libro, el servidor le ofrece el archivo HTML que pidió mediante la URL. Cuando visita un sitio web impulsado con PHP, un script de PHP se está ejecutando en el servidor, que devolverá (normalmente) algún código HTML al navegador. Así que en ambos casos, usted obtiene su HTML de vuelta. entonces ¿cual es la diferencia?

El sitio con PHP puede generar de manera dinámica HTML basándose en la URL y otros datos del navegador que ha hecho la petición. Por ejemplo, podría tener un sitio donde el usuario tuviera un perfil en `example.com/user/victorhck`. Con HTML en texto plano, necesitaría crear ese archivo para cada usuario. Sin embargo, con PHP, podría generar la página sobre la marcha leyendo el nombre de usuario en la URL y construyendo al HTML apropiado para enviarlo de vuelta.

PHP también le permite implementar funciones web más complicadas, como aceptar datos de usuario y guardarlos en una base de datos. Estos pueden ser tan simples como mostrar un contador de visitas dinámico o tan sofisticados como una red social.

Si eso le parece complicado, no se preocupe. No profundizaremos en la construcción de un montón de HTML con PHP. Veremos una función particular de PHP que es útil para nuestros propósitos: la declaración `include`.

### Cómo ejecutar PHP

Neocities, el servicio que hemos estado utilizando para alojar nuestro sitio web personal, no permite ejecutar PHP. Esto es lo mejor, ya que no encaja con el espíritu de Neocities y complicaría un servicio agradable y sencillo. Afortunadamente, hay un montón de servicios asequibles que ofrecen PHP.

Recomiendo lo que se llama _alojamiento compartido_. En pocas palabras, esto generalmente significa que el servicio administrará sus servidores y le dará a usted, el cliente, una carpeta en el servidor donde puede cargar sus archivos (y generalmente incluir acceso a varios servicios).

---

**Nota**

Es posible ejecutar PHP en su ordenador para probar tu sitio web antes de subirlo a un servidor. Sin embargo, la configuración de eso queda fuera del alcance de este libro.

---

La manera más sencilla probablemente sea utilizando una aplicación como [XAMPP](https://www.apachefriends.org/) or [MAMP](https://www.mamp.info) (que es lo que utilizo). También puede [instalar PHP directamente en su sistema](https://perma.cc/MZB9-GKBD) y utilizar su [servidor de desarrollo propio](https://web.archive.org/web/20240711042305/https://www.php.net/manual/en/features.commandline.webserver.php).

La mayoría de los hosts compartidos ofrecen los mismos servicios, pero estos son algunos de los que la gente recomendó cuando [pregunté en Mastodon](https://perma.cc/WAD3-JCNX).

-   [DreamHost](https://www.dreamhost.com/)
-   [SiteGround](https://www.siteground.com/)
-   [Reclaim Hosting](https://www.reclaimhosting.com/)
-   [InfinityFree](https://www.infinityfree.com/)

Y luego está [NearlyFreeSpeech.NET](https://www.nearlyfreespeech.net/), el servicio de hospedaje web [que he estado utilizando durante años](https://blakewatson.com/journal/why-i-host-my-websites-with-nearlyfreespeech-net/). No se puede decir que sea muy amigable para alguien recién llegado, pero la interfaz es de lo más simple, y no hay anuncios molestos o ventas adicionales.

Una vez que tenga una cuenta en uno de estos (o algún otro) proveedor de alojamiento web, debería poder cargar archivos directamente a través de su sitio web o conectándose a su servidor mediante [FTP](https://perma.cc/P7Y7-CR6P).

Los detalles de eso se escapan del alcance de este libro, pero hay toneladas de recursos sobre cómo ponerse en marcha con un servidor web compartido. Unas cuantas búsquedas en la web deberían ponerle en el camino correcto.

Lo bueno de PHP es que es fácil de iniciar. Simplemente tome una de las páginas de su sitio web y cambie la extensión del archivo de `.html` a `.php`. Acaba de crear un archivo PHP perfectamente válido, sin necesidad de realizar cambios.

### Haciendo una página web dinámica

Si todo lo que hace es cambiar la extensión del archivo, todo permanecerá igual para el visitante. Recibirán el HTML igual que antes. Pero ahora que tiene un archivo PHP, puede poner código dinámico en su página web insertándolo en etiquetas PHP.

Por ejemplo, aquí hay una página web que mostrará el año actual.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Mi sitio web</title>
        <link rel="stylesheet" href="https://unpkg.com/sakura.css/css/sakura.css" type="text/css">
    </head>
    <body>
        <h1>Mi sitio web</h1>

        <p>El año actual es: <?php echo date('Y') ?></p>
    </body>
</html>
```

Incluso si nunca vuelve a editar este archivo, siempre estará actualizado (siempre que el servidor lo esté) porque PHP inserta el año en el código HTML cuando se lo solicita la página.

Analicemos la parte dinámica de esto. En primer lugar, el código PHP se escribe entre las etiquetas PHP (`<?php` y `?>`).

El código PHP dentro de estas etiquetas se ejecuta en el servidor antes de que el HTML se envíe al navegador. La instrucción `echo` es la forma en que le hace saber a PHP que quiere que genere algo en la página. La función `date` devuelve la fecha actual, en este caso, le estamos diciendo que únicamente queremos el año.

Así, la función `date` se ejecuta, devolviendo el dato del año actual. Esa parte del texto es entonces procesada por la instrucción `echo`, y esta será insertada dentro del documento HTML.

El código PHP real no se devuelve al navegador y sus visitantes nunca lo verán. En su lugar, aparecerá como HTML normal, con el año actual como si lo hubiera escrito usted.

### Reutilizar parte de su sitio web

Una cosa que hace que PHP sea increíblemente útil es su capacidad para reutilizar partes de HTML en múltiples lugares.

Considere el sitio web que hemos estado construyendo a lo largo de este libro. Tiene la barra de navegación en todas las páginas (excepto el atributo `aria-current`, que cambiará dependiendo de la página en la que se encuentre).

```html
<nav>
  <a href="/index.html" aria-current="page">Inicio</a>
  <a href="/blog/">Blog</a>
  <a href="/about.html">Acerca de</a>
  <a href="/resume.html">Currículum</a>
  <a href="/fun.html">¡Diversión!</a>
</nav>
```

Debemos de mantener el menú de navegación (“nav”) en cada página. No es algo muy difícil en sitios web pequeños con unas pocas páginas. Pero imagine si tiene docenas de páginas en su sitio web. Si decide modificar algo en su menú de navegación, necesitaría ir a _cada una de las páginas_ y hacer el mismo cambio en cada sección que quiera modificar. Con PHP, podemos reutilizar el código de nuestro menú de navegación.

Primero, crearemos un archivo llamado `nav.php`. Puede ubicarlo en cualquier parte de su proyecto, pero yo lo pondré en una carpeta llamada `includes` simplemente para tenerlo todo organizado.

Copie el menú de navegación de su página de inicio (`index.html`) y pegue su contenido en el archivo `nav.php`. Elimine el atributo `aria-current="page"` por ahora, también necesitaremos hacer esa parte dinámica más adelante.

Debería tener un archivo `nav.php` que tenga un aspecto como este:

```html
<nav>
  <a href="/">Inicio</a>
  <a href="/blog">Blog</a>
  <a href="/about.php">Acerca de</a>
  <a href="/resume.php">Currículum</a>
  <a href="/fun.php">¡Diversión!</a>
</nav>
```

Lo anterior no es solo un extracto. Esto es el _contenido entero_ de `nav.php`. A diferencia de otros archivos HTML, que necesitan secciones como `<head>`, `<body>`, etc. Los archivos PHP pueden contener un fragmento de HTML.

---

**Nota**

En el proceso de convertir el sitio de únicamente de HTML a PHP, es un buen momento para convertir los enlaces internos entre páginas a direcciones URL absolutas. Comience con una barra `/` y escriba la ruta completa. Eche un vistazo a esta [sección de URL relativas vs. URL absolutas](#Cap8_URL) del capítulo si todavía no lo ha leído.

---

Ahora, vamos a utilizar ese archivo recién creado. Renombre el archivo `index.html` a `index.php`. Elimine el código completo del bloque `<nav>` y reemplácelo con la siguiente línea de PHP.

```html
<header>
    <?php include "includes/nav.php" ?>

    <h1>La web de Victorhck</h1>
</header>
```

Cuando cargue la página, las cosas deberían seguir teniendo el mismo aspecto que tenían antes. Debería seguir viendo su menú de navegación. Pero la magia es que ahora está utilizando su versión en PHP. Ahora, ya puede comenzar a convertir el resto de las páginas reemplazando el menú existente por el código en PHP que llama a al achivo que hemos creado.

### Convertir páginas HTML a PHP

Generalmente los pasos a seguir son los mismos para cada página:

1.  Cambiar la extensión del archivo de `.html` a `.php`.
2.  Reemplazar el código de la etiqueta `<nav>` con el de PHP incluida la llamada.

Para las páginas del nivel más alto, la llamada de PHP sería así:

```
<?php include "includes/nav.php" ?>
```

Si está editando una subpágina (como la del blog), debería ajustar la ruta de la llamada utilizando `..` para subir un nivel y situarse en la ruta donde está archivo.

```
<?php include "../includes/nav.php" ?>
```
---

**Nota**

Si está preparado para añadir más código, utilice una variable propia de PHP que haga referencia a ese directorio del nivel más alto. La siguiente instrucción funcionará sin importar en qué página se encuentre. Aquí el punto (`.`) conecta las dos cadenas de texto.

```
<?php include $_SERVER['DOCUMENT_ROOT'] . "/includes/nav.php" ?>
```

---

Una vez que lo realice en cada página, habrá reutilizado el menú de navegación. Si desea actualizar el menú en el futuro modificando una sección, simplemente lo hará editando el archivo `nav.php`. y verá que los cambios se realizan en todos los sitios que se reutilice esa llamada al código modificado.

Podría realizar lo mismo para otras partes que tengan elementos que se repitan en su sitio web. Por ejemplo, la mayoría de l sección `<head>` de la página web es la misma en cada página. El pie de página también debería ser el mismo en cada página. Y muchas otras partes.

### Extra: resaltado dinámico del enlace actual del menú de navegación

Cuando hemos mudado nuestro menú de navegación de PHP, hemos perdido algo. Anteriormente, establecíamos el atributo `aria-current` en el enlace apropiado del menú de navegación para indicar qué página es la actual en el menú de navegación. Esto es bueno para la accesibilidad y añade algunas pistas visuales para aquellas personas que la visitan. Pero ¿cómo establecemos cual es la página actual si la navegación se hace únicamente desde un archivo? ¿Cómo sabemos qué página de la lista es la actual?

Considere esta sección un extra de este capítulo extra (sí, un extra, dentro de otro extra). Aquí echaré mano de algunos conceptos de programación. Solo trataré de ellos por encima, ya que programar en PHP es una materia extensa por lo que está fuera del objetivo de este libro que va orientado a principiantes. Dicho esto, con un poco de código (que puedes reutilizar en tu página), puede implementar el `aria-current` _automágicamente_.

Primero, vamos a recapitular lo que significa este atributo. Si un visitante va a la página de Acerca de, queremos que el enlace en el menú de navegación indique que estamos en la página actual (o que un lector de pantalla lo lea si el visitante utiliza uno). Utilizaremos el atributo `aria-current="page"` en ese caso.

También puede darse otro escenario. Si alguien visita un artículo del blog, nos gustaría resaltar el enlace del Blog en el menú de navegación. No es exactamente la página actual, no están en la página de listado del blog, donde apunta el enlace, sino más bien una publicación de blog individual. Aún así, sería bueno resaltar el enlace del blog porque representa la sección actual del sitio: la publicación es una subpágina del blog. En ese caso, podríamos usar `aria-current="true"`. Esto es menos específico y más correcto semánticamente.

Genial, pero ¿cómo podemos añadir esto en PHP?

Hay muchas maneras de hacer esto, y ninguna de ellas es necesariamente más correcta que otra, pero esta es la que creo que es la forma menos complicada de hacerlo.

Esta técnica requerirá que _llamemos a una función_ en cada elemento del menú de navegación. Sería algo como esto:

```html
<nav>
    <a href="/" <?php aria_current('/') ?>>Inicio</a>
    <a href="/blog" <?php aria_current('/blog') ?>>Blog</a>
    <a href="/about.php" <?php aria_current('/about.php') ?>>Acerca de</a>
    <a href="/resume.php" <?php aria_current('/resume.php') ?>>Currículum</a>
    <a href="/fun.php" <?php aria_current('/fun.php') ?>>¡Diversión!</a>
</nav>
```

Necesitaremos una _función_ personalizada llamada `aria_current` (En breve verá el código de dicha función). La función debería recibir un _argumento_, que debería ser el texto de `href`. Será entonces trabajo de la función comparar ese texto con la URL visitada y determinr si debería mostrar, utilizando `echo`, el atributo `aria-current`.

Puede poner la función en el mismo archivo PHP encima del código HTML que teníamos.

```html
<?php
function aria_current($url) {
    // Si $url conincide exactamente con la URL actual, devolverá 'aria-current="page"'.
    if ($_SERVER['REQUEST_URI'] === $url) {
        echo 'aria-current="page"';
        return;
    }

    // En otro caso podría ser una subpágina, así que comprueba si la URL contiene
    // $url. Si lo tiene, devuelve 'aria-current="true"' para indicar que el enlace
    // es pariente de la página actual. Ignorar una única barra inclinada.
    if ($url !== '/' && strpos($_SERVER['REQUEST_URI'], $url) !== false) {
        echo 'aria-current="true"';
        return;
    }
}
?>

<nav>
    <a href="/" <?php aria_current('/') ?>>Home</a>
    <a href="/blog" <?php aria_current('/blog') ?>>Blog</a>
    <a href="/about.php" <?php aria_current('/about.php') ?>>About</a>
    <a href="/resume.php" <?php aria_current('/resume.php') ?>>Resume</a>
    <a href="/fun.php" <?php aria_current('/fun.php') ?>>Fun!</a>
</nav>
```

Genial, vamos a diseccionar el código. Primero, necesitamos abrir un par de etiquetas PHP. Dentro, definiremos una función llamada `aria_current` con un argumento: una variable llamada `$url`.

Puede ver dónde añadí notas llamadas _comentarios_. Cada línea que comienza con dos barras inclinadas (`//`) es considerada un comentario e ignorada, sólo es útil para las personas que ven el código.

La primera parte del código es un _estamento if_. PHP tiene variables globales llamadas `$_SERVER` con toda clase de información, incluyendo qué página está siendo visitada actualmente (lo que llama `REQUEST_URI`). Así que almacenamos y comprobamos si coincide con la URL del elemento del menú de navegación dado (recuerda, estamos ejecutando esta función para cada elemento del menú de navegación). Si lo es, enviaremos `aria-current="page"` utilizando la instrucción `echo`. En ese caso, la salida aparecerá en el punto donde llamamos a la función (que está dentro de la etiqueta `<a>`, donde van los atributos). Después de la instrucción `echo`, utilizamos `return` para parar la función y ya está.

Si la primera comprobación no es cierta, hay una segunda comprobación que queremmos intentar. ¿Es la página actual que estamos visitando una subpágina de un elemento de la barra de navegación?

Esta comprobación tiene dos partes:

1.  Primero, queremos ignorar la página de inicio (`/`) porque, esa obviamente no es una subpágina de nada.
2.  Segundo, comprobaremos la URL que hemos pasado a la función con la URL visitada para ver si tienen una coincidencia.

La segunda parte del test utiliza una función llamada `strpos`. Esta recibe dos argumentos. El primero es una porción de texto en el que quieres buscar (le llamaremos _pajar_). La segunda es un fragmento de texto que está usted buscando (le llamaremos _aguja_). La función devolverá la posición de la _aguja_ en el _pajar_ si la encuentra. Devolverá `false` si no encentra nada en absoluto.

Así que, de nuevo, vamos a ver la variable global propia `$_SERVER['REQUEST_URI']`. Puede imaginar que siendo algo así como `/blog/my-first-post`. Sabemos que el visitante está en una subpágina del blog si encontramos `/blog` dentro de la ruta.

El test se pasará en este caso, y devolveremos `aria-current="true"` utilizando la instrucción `echo`.

Si los dos test fallan, entonces no devolveremos nada.

En resumen, cuando un visitante carga una página en nuestro sitio web, ejecutamos una función en cada elemento de navegación. Si el `href` del elemento del menú de navegación coincide con la URL actual o se encuentra en algún lugar de la URL actual, generamos el atributo `aria-current` apropiado. De lo contrario, no generamos nada.

¡Ufff! Si nunca antes no ha hecho ninguna programación, puede darse una palmadita en la espalda porque ahora lo ha hecho. Si encuentra este tipo de cosas divertidas, puede explorar más de PHP o echar un vistazo a JavaScript.

### Conclusión

Las plantillas de PHP con `include` son una excelente manera de crear HTML sin repetir código. PHP tiene una curva de aprendizaje más baja que otros lenguajes de programación, que es una de las razones por las que lo menciono en este libro para principiantes. Sin embargo, los sitios web se pueden crear con todo tipo de lenguajes de programación (JavaScript, Python y Ruby son otras opciones populares). Este es el mundo de los sitios web dinámicos. Se vuelve bastante salvaje si comienza a pensar en todo lo que puede hacer con él.

Y con esta última lección, ahora ya sí, doy por terminado este último capítulo extra de HTML para personas. Espero que le haya resultado interesante todo lo que hemos repasado y haya aprendido los conceptos básicos para empezar a crear páginas web y le de pie a explorar más este campo. ¡Muchas gracias por leer!

<center>-#-</center>

## ¿Disfrutas del libro?

_HTML para personas_ es un trabajo de dedicación. Si tienes la posibilidad, considera enviar una donación al autor original o a mí como traductor y compartir el libro en tus redes sociales.

[Donar al autor en Ko-fi](https://ko-fi.com/blakewatson)

Otro material del autor:

-   [Una extensión minimalista de nueva pestaña](https://afinestart.me)
-   [Un sitio web de mix de sintetizadores](https://synthwave.live/)
-   [Una pequeña muestra minimalista de caracteres para D&D](https://minimalcharactersheet.com/)
-   [Sitio personal del creador](https://blakewatson.com)

Como traductor ha supuesto un aprendizaje y una dedicación de tiempo y esfuerzo en hacer el mejor trabajo posible y ofrecerlo de manera libre y gratuita como recurso de aprendizaje. Espero que te guste

[Donarme en LiberaPay](https://liberapay.com/victorhck)

-   [Mi blog](https://victorhckinthefreeworld.com/)

[Recursos](#Recursos) · [Versión imprimible (en inglés)](https://victorhck.gitlab.io/htmlparapersonas/printable) · [GitHub](https://github.com/blakewatson/htmlforpeople) · [GitLab](https://gitlab.com/victorhck/htmlparapersonas) · [Reportar un error a la web en inglés](https://github.com/blakewatson/htmlforpeople/issues) · [Sobre el autor](https://blakewatson.com/about) · [Sobre mí](https://victorhckinthefreeworld.com/contacto/) · [Mastodon del creador](https://social.lol/@bw) · [Mi Mastodon](https://mastodon.social/@victorhck)

Un proyecto original de [Blake Watson](https://blakewatson.com). Traducido por [Victorhck](https://victorhckinthefreeworld.com/). Ambos trabajos bajo una licencia [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
