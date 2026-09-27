--------------------------
Paso 1
En este taller, crearás una página de librería diseñando fichas que muestren información sobre diferentes libros. Practicarás la organización del contenido utilizando divelementos, clases e identificadores.

Comience a crear la página de su librería creando la plantilla HTML.

Agregue la <!DOCTYPE html>declaración y htmllos headelementos.

Agregue un langatributo al htmlelemento y establézcalo en "en".

--------------------------
Paso 2
Agrega el titleelemento dentro del headelemento.

Establezca el título de la página en XYZ Bookstore Page.

--------------------------
Paso 3
Ahora, mejora la estructura de tu documento HTML para asegurarte de que tu página esté codificada correctamente.

Dentro del headelemento, agregue el <meta charset="UTF-8">elemento.

Por último, añade un bodyelemento debajo de la headsección. Aquí es donde irá todo el contenido visible de la página.

--------------------------
Paso 4
En este paso, agregue un h1elemento con el texto XYZ Bookstore.

--------------------------
Paso 5
Debajo del h1elemento, agregue un pelemento con este texto: Browse our collection of amazing books!.

--------------------------
Paso 6
Este divelemento se utiliza como contenedor para agrupar otros elementos HTML. Lo usarás principalmente divcuando quieras agrupar elementos HTML que compartan un conjunto de estilos CSS.

Debajo del pelemento, añade otro divelemento. Este divservirá como contenedor para las fichas de tu libro.

Nota : Este taller no aplica CSS. Las clases y los elementos agrupados son útiles para el estilo CSS, pero en este taller se utilizan únicamente para estructurar y agrupar contenido. Aprenderás cómo funciona el estilo en un módulo posterior.

--------------------------
Certificación en diseño web adaptable
Crea una página de librería
Instrucciones
índice.htmlEditor
Consola
Ocultar la vista previaAvance
Mueva la vista previa a una ventana nueva y enfóquela.
Paso 7
El classatributo se utiliza para identificar uno o más elementos a los que se les aplica estilo. A diferencia del idatributo, los nombres de clase no tienen por qué ser únicos: varios elementos pueden compartir la misma clase.

Aquí tienes un ejemplo:

Código de ejemplo
<p class="example">example paragraph</p>
Agregue un classatributo a su divelemento y establezca su valor en card-container

--------------------------
Paso 8
Puedes agregar varios elementos dentro de un divelemento para agrupar contenido relacionado. Dentro del elemento que tiene un class, card-containercrea otro divelemento. Este divrepresentará la primera tarjeta de libro.

Agregue un classatributo a este nuevo divelemento y establezca el valor del classatributo en card.

--------------------------
Paso 9
Este idatributo añade un identificador único a un elemento HTML. Cada identificador iddebe ser único dentro de una página y solo debe usarse una vez.

idLos valores no pueden contener espacios y solo deben contener letras, dígitos, guiones bajos y guiones.

Aquí tienes un ejemplo:

Código de ejemplo
<p id="para">example paragraph</p>
Agregue un idatributo a su elemento que tenga una clase de cardy establezca su valor en sally-adventure-book.

--------------------------
Paso 10
Dentro del primer elemento que tenga una clase de card, agregue un h2elemento con el texto Sally's SciFi Adventure.

--------------------------
Paso 11
Debajo del h2elemento en el primer elemento que tiene una clase de card, agregue un pelemento con el siguiente texto:

Código de ejemplo
This is an epic story of Sally and her dog Rex as they navigate through other worlds.

--------------------------
Paso 12
Este buttonelemento se utiliza para crear botones interactivos en una página web. Los botones son elementos interactivos que los usuarios pueden pulsar para realizar acciones.

Agregue un buttonelemento dentro del elemento que tenga un classde card, déle al botón un classatributo establecido en btn, y el texto Buy Now.

--------------------------
Paso 13
Ahora crea una segunda ficha de libro. Añade otro divelemento con el classatributo establecido en card. Observa cómo puedes reutilizar el mismo nombre de clase para varios elementos y así aplicar un estilo coherente.

--------------------------
Paso 14
Agregue un idatributo a su segundo elemento que tenga una clase de cardy establezca su valor en dave-cooking-book. Recuerde que cada iddebe ser único.

--------------------------
Paso 15
Dentro del segundo elemento que tiene una clase de card, agregue un h2elemento con el texto Dave's Cooking Adventure.

--------------------------
Paso 16
Debajo del h2elemento de la segunda tarjeta, añade un pelemento con este texto:

Código de ejemplo
This is the story of Dave as he learns to cook everything from pancakes to pasta, one recipe at a time

--------------------------
Paso 17
Dentro de la segunda tarjeta, agregue un buttonelemento con el classatributo establecido en btny el texto Buy Now.

Ahora ambos buttonelementos comparten el mismo class, lo que significa que se les puede aplicar un estilo coherente en conjunto.

--------------------------
Paso 18
Recuerda que un elemento HTML tiene este aspecto:

Código de ejemplo
<element attribute="value">
    inner text
</element>
Debajo del elemento con la clase card-container, agregue un nuevo pelemento con este texto:

Código de ejemplo
Review your selections and continue to checkout.
Debajo del pelemento, crea un divelemento con el classatributo establecido en btn-container. Este contenedor agrupará los elementos de tu botón de navegación.

--------------------------
Paso 19
Dentro del elemento con la clase btn-container, agregue dos buttonelementos:

Primer botón:

Identificación:view-cart-btn
Clase:btn
Texto:View Cart
Segundo botón:

Identificación:checkout-btn
Clase:btn
Texto:Checkout
¡Enhorabuena! Has logrado construir la estructura de una página de librería utilizando divs, clases e ids para organizar tu contenido.