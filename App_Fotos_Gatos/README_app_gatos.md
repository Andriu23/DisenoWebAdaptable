_________________________________
Paso 1
En este taller, comenzarás trabajando con elementos HTML básicos como títulos, párrafos y listas, construyendo una aplicación de fotos de gatos.

Comienza el taller agregando un elemento h1con el texto de CatPhotoApp.

_________________________________
Paso 2
Debajo del elemento h1, añade un elemento h2con este texto:

Cat Photos

_________________________________
Paso 3
Crea un elemento pdebajo de tu elemento h2y dale el siguiente texto:

Everyone loves cute cats online!

_________________________________
Paso 4
Los comentarios te permiten dejar mensajes sin afectar la visualización en el navegador. También te permite desactivar el código. Un comentario en HTML comienza con <!--, contiene cualquier número de líneas de texto y termina con -->.

Aquí tienes un ejemplo de un comentario con el texto TODO: Remove h1:

Código de ejemplo
<!-- TODO: Remove h1 -->
Agregue un comentario sobre el elemento pcon este texto:

TODO: Add link to cat photos

_________________________________
Paso 5
HTML5 tiene diferentes elementos que ayudan a diferenciar diferentes tipos de contenido. Estos elementos hacen que tu código HTML sea más fácil de leer y ayudan con el Posicionamiento en buscadores (Search Engine Optimization - SEO) y accesibilidad.

El elemento mainse utiliza para representar el contenido principal del cuerpo de un documento HTML. El contenido dentro del elemento maindebe ser único para el documento y no debe repetirse en otras partes del documento.

Código de ejemplo
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
Identifique la sección principal de esta página agregando una etiqueta de apertura <main>antes del elemento h1y una etiqueta de cierre </main>después del elemento p.

_________________________________
Paso 6
En el paso anterior, has colocado los elementos h1, h2, comentario y pdentro del elemento main. Esto se llama anidamiento . Los elementos anidados deben colocarse dos espacios más a la derecha del elemento en el que están anidados. Este espacio se llama sangría (sangría en programación) y se utiliza para facilitar la lectura de HTML.

Aquí tienes un ejemplo de anidación y sangría:

Código de ejemplo
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
El elemento h1, el elemento h2y el comentario están sangrados en dos espacios más que el elemento mainen el código de abajo. Usa la barra espaciadoraen tu teclado para agregar dos espacios más delante del elemento ppara que también esté sangrado correctamente.

_________________________________
Paso 7
Puedes agregar imágenes a tu sitio web usando el elemento img. Los elementos imgtienen una etiqueta de apertura sin una etiqueta de cierre. Un elemento sin etiqueta de cierre se conoce como elemento vacío .

Agregue un elemento imgdebajo del elemento p. En este punto, ninguna imagen aparecerá en el navegador.

_________________________________
Paso 8
Los atributos HTML son palabras especiales usadas dentro de la etiqueta de apertura de un elemento para controlar el comportamiento del elemento. El atributo srcen un elemento imgespecifica la URL (donde se localiza la imagen).

Aquí hay un ejemplo de un elemento imgcon un atributo srcapuntando al logo de freeCodeCamp:

Código de ejemplo
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
Dentro del elemento imgexistente, agregue un atributo srccon esta URL:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg

_________________________________
Paso 9
Todos los elementos imgdeben tener un atributo alt. El texto del atributo altes utilizado por lectores de pantalla para mejorar la accesibilidad y se muestra en caso de que la imagen caiga al cargar.

Aquí tienes un ejemplo de un elemento imgcon un atributo alt:

Código de ejemplo
<img src="cat.jpg" alt="A cat">
Dentro del elemento img, agrega un atributo altcon este texto:

A cute orange cat lying on its back

_________________________________
Paso 10
Puedes hacer un enlace que te llevará a otra página con el elemento ancla ( a).

Aquí hay un ejemplo que enlaza a https://www.freecodecamp.org:

Código de ejemplo
<a href="https://www.freecodecamp.org"></a>
Agrega un elemento ancla después del párrafo que te lleve a https://freecatphotoapp.com. En este punto, el enlace no aparecerá en la vista previa.

_________________________________
Paso 11
El texto de un enlace debe colocarse entre la etiqueta de apertura y la etiqueta de cierre de un elemento ancla ( a).

Aquí hay un ejemplo de un enlace con el texto click here to go to freeCodeCamp.org:

Código de ejemplo
<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
Agregue el texto cat photosal elemento ancla. Esto se convertirá en el texto del enlace.

_________________________________
Paso 12
Agrega las palabras See more antes del elemento ancla y  in our gallerydespués del elemento ancla.

_________________________________
Paso 13
Agregue etiquetas ppara convertir See more <a href="https://freecatphotoapp.com">cat photos</a> in our gallery.en un párrafo.

_________________________________
Paso 14
Convierte el texto existente cute catsen un elemento de anclaje que enlaza a:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg

_________________________________
Paso 15
Para abrir enlaces en una pestaña nueva, puede usar el atributo targeten el elemento ancla ( a).

El atributo targetespecifica dónde abrir el documento vinculado. target="_blank"abre el documento vinculado en una nueva pestaña o ventana.

Aquí está la sintaxis básica para un elemento acon un atributo target:

Código de ejemplo
<a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>
Agrega un atributo targetcon el valor _blankal elemento ancla ( a) de cat photosen la etiqueta de apertura, para que el enlace se abra en una nueva pestaña.

_________________________________
Paso 16
Ahora que has añadido el enlace, puedes quitar el comentario.

_________________________________
Paso 17
En los pasos anteriores, use un elemento de anclaje para convertir texto en un enlace. Otros tipos de contenido también se pueden convertir en un enlace envolviéndolos en etiquetas ancla.

Aquí hay un ejemplo de cómo convertir una imagen en un enlace:

Código de ejemplo
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
Convierte la imagen en un enlace rodeándola con las etiquetas correctas. Utiliza https://freecatphotoapp.comcomo valor del atributo hrefdel elemento archor.

_________________________________
Paso 18
Antes de agregar nuevo contenido, deberías utilizar un elemento section, para separar el contenido de fotos de gatos, del contenido que agregaremos después.

El elemento sectionse utiliza para definir secciones en un documento, como capítulos, encabezados, pies de página o cualquier otra sección del documento. Es un elemento semántico que ayuda con el SEO y la accesibilidad.

Código de ejemplo
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
Toma tu elemento h2, dos elementos py el elemento de ancla ( a) y anídalos en un elemento section.

_________________________________
Paso 19
Es hora de agregar una nueva sección con un elemento sección. Agregue un segundo elemento sectiondebajo del elemento sectionexistente.

_________________________________
Paso 20
Dentro del segundo elemento section, añade un nuevo elemento h2con el texto Cat Lists.

_________________________________
Paso 21
Cuando agregas un elemento de encabezado de rango menor a la página, se implica que estás comenzando una nueva subsección.

Después del último elemento h2del segundo elemento section, agregue un elemento h3con este texto:

Things cats love:

_________________________________
Paso 22
Para crear una lista no ordenada de elementos, puedes usar el elemento ul.

Después del elemento h3con el texto Things cats love:, añade una lista desordenada, unordered list - ( ul). Diez en cuenta que nada se mostrará aún.

_________________________________
Paso 23
El elemento lise usa para crear una lista de elementos en una lista ordenada o en una lista desordenada.

Aquí hay un ejemplo de una lista de objetos en una lista desordenada:

Código de ejemplo
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
Dentro del elemento ulanida tres elementos li para mostrar tres cosas que aman los gatos:

catnip

laser pointers

lasagna

_________________________________
Paso 24
Después de la lista no ordenada, agregue una imagen nueva con un valor de atributo src:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg

Y su valor de atributo alta:

A slice of lasagna on a plate.

_________________________________
Paso 25
El elemento figurerepresenta el contenido independiente y te permitirá asociar una imagen a una descripción.

Introduzca la imagen que acaba de agregar dentro de un elemento figure.

_________________________________
Paso 26
Un elemento ( figcaption), se utiliza para agregar una descripción o leyenda para describir una imagen anidada en un elemento figure.

Aquí tienes un ejemplo de un elemento figcaptioncon la leyenda de A cute cat:

Código de ejemplo
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
Después de anidar la imagen en el elemento figure, añade un elemento figcaptioncon el texto:

Cats love lasagna.

_________________________________
Paso 27
Para poner énfasis en una palabra o frase específica, puedes utilizar el elemento em.

Enfatiza la palabra loveen el elemento figcaptionenvolviendola en un elemento énfasis em.

_________________________________
Paso 28
Después del elemento figure, añade un elemento h3con el texto:

Top 3 things cats hate:

_________________________________
Paso 29
El código de una lista ordenada, ordenada lista ( ol), es similar al de una lista no ordenada, unordered list (ul), pero los elementos de una lista ordenada aparecen listados.

Debajo del elemento h3, agrega una lista ordenada con estos tres elementos de lista:

flea treatment thunder other cats


_________________________________
Paso 30
Después de la lista ordenada (ol), añade otro elemento figure.

_________________________________
Paso 31
Dentro del elemento figureque acabas de agregar, anida un elemento imgcon un atributo srccon el valor https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg.

_________________________________
Paso 32
Para mejorar la accesibilidad de la imagen que agregaste, agrega un atributo altcon el texto:

Two tabby kittens sleeping together on a couch.

_________________________________
Paso 33
Después del último elemento imgañade un elemento figcaptioncon el textoCats hate other cats.

_________________________________
Paso 34
El elemento strongse utiliza para indicar que una parte de un texto es importante o urgente.

En el figcaptionque acabas de agregar, indica que hatetiene una fuerte importancia envolviéndolo en un elemento strong.

_________________________________
Paso 35
El elemento footerse usa para definir el pie de página de un documento o sección. Un pie de página normalmente contiene información sobre el autor del documento, datos de copyright, enlaces a términos de uso, información de contacto, etcétera.

Después del elemento main, añade un elemento footer.

_________________________________
Paso 36
Anida un elemento pcon el texto No Copyright - freeCodeCamp.orgdentro del elemento footer.

_________________________________
Paso 37
Convierte el texto existente freeCodeCamp.orga un enlace, colocándolo dentro de un elemento ancla ( a). El valor del atributo hrefdebe ser https://www.freecodecamp.org.

_________________________________
Paso 38
Puedes notar que todo lo que has agregado hasta ahora, está dentro del elemento body. Todos los elementos que deben ser renderizados o mostrados en la página, deben ir dentro del elemento body. Sin embargo, otro tipo de información que también es importante va dentro del elemento head.

El elemento headse usa para contener metadatos sobre el documento, como su título, enlaces a hojas de estilo y scripts. Los metadatos son información sobre la página que no se muestra directamente en la página.

Agregue un elemento headsobre el elemento body.

_________________________________
Paso 39
El elemento title(título) determina lo que los navegadores muestran en la barra de título o en las pestañas del navegador.

Agrega un elemento titledentro del elemento headusando el texto a continuación:

CatPhotoApp

_________________________________
Paso 40
Puedes ver que todo el contenido de la página está anidado dentro de un elemento html. El elemento htmles elemento esencial de una página HTML y envuelve todo el contenido en la página.

También puedes especificar el idioma de tu página agregando el atributo langal elemento html.

Agregue un atributo langcon el valor ena la etiqueta de apertura del elemento htmlpara especificar que el lenguaje de la página es el inglés.


_________________________________
Paso 41
Todas las páginas deben comenzar con <!DOCTYPE html>. Esta cadena especial se conoce como declaración y garantiza que el navegador intenta cumplir con las especificaciones de la industria.

<!DOCTYPE html>le dice a los navegadores que el documento es un documento HTML5 la cual es la última versión de HTML.

Agregue esta declaración como la primera línea del código.


_________________________________
Paso 42
Puedes establecer el comportamiento del navegador agregando elementos metaen el head. Aquí tienes un ejemplo:

Código de ejemplo
<meta attribute="value">
Dentro del elemento head, anida un elemento metacon un atributo charsetestablecido al valor UTF-8. Esto indica al navegador cómo codificar los caracteres de la página.

Ten en cuenta que el elemento metaes un elemento vacío.

Con ese último cambio, se ha completado el taller de la aplicación de fotos de gatos. ¡Felicidades!