-Este código HTML crea una página web estructurada en varias secciones. Comienza con <!DOCTYPE html>, que indica que el 

documento sigue el estándar HTML5. <html lang="es"> establece que el contenido está en español. En la sección <head> 

se incluyen los metadatos del documento: <meta charset="UTF-8"> define la codificación de caracteres UTF-8, asegurando 

compatibilidad con caracteres especiales; <meta name="viewport" content="..."> permite que la página sea responsive, 

adaptándose a diferentes dispositivos; <title> define el título que aparece en la pestaña del navegador, y 

<!--link rel="stylesheet" href="css/stylesheet.css"--> enlaza un archivo externo de estilos CSS para el diseño visual.

En el <body> se encuentra el contenido visible. La etiqueta <header> contiene un encabezado principal con un título <h1>

y una barra de navegación <nav> con una lista desordenada <ul> de enlaces <li> que dirigen a distintas páginas del sitio

mediante etiquetas <a href="...">.

La sección principal de la página está dentro de <main> y se divide en dos partes: la primera, <section id="Descripción">

, tiene un contenedor <div> con clase descripcion-caja que incluye un párrafo <p> describiendo el propósito de la tienda

en línea. La segunda parte, <section id="login" class="login-caja">, presenta un formulario de inicio de sesión 

<form action="/login" method="POST"> que envía datos al servidor. Este formulario incluye campos de entrada <!--input-->

con etiquetas <label>: uno para el correo electrónico (type="email") y otro para la contraseña (type="password") marcados 

como obligatorios con el atributo required. También incluye un botón de envío (type="submit") y un enlace <a> a la 

página de registro.

Por último, el <footer> contiene un breve texto sobre los términos y condiciones del sitio. Todo esto estructura una 

página web funcional con navegación básica, un formulario y secciones informativas, lista para estilizarse con el 

archivo CSS enlazado.

Este código HTML amplía una página web con una sección dedicada a "Artículos destacados". El <body> contiene un título 

principal definido con <h1> que introduce el contenido principal de esta página. A continuación, se utiliza un contenedor

<div> con la clase container que agrupa varios artículos individuales, cada uno representado por un <article> con la clase article-card.

Dentro de cada artículo, se incluye una imagen (<img>) con el atributo src que define la ruta de la imagen del producto

y alt que describe brevemente la imagen para propósitos de accesibilidad. Cada artículo tiene un título <h3> que indica

el nombre del producto, un párrafo <p> que muestra el precio, y un <div> con la clase buttons que contiene dos botones 

(<button>): uno para indicar "me gusta" con un ícono de corazón (❤) y otro para seleccionar el artículo.

Los productos incluyen ejemplos como "Abrigo Lacoste", "Reloj Casio", "Cinturón Gucci", y más, todos con información 

básica sobre el precio y una interfaz interactiva para los usuarios. Las clases asignadas (container, article-card, y buttons) 

están diseñadas para estilizarse con el archivo de CSS externo stylesheet2.css, vinculado en la cabecera del documento mediante <link>.

Este diseño es flexible y escalable, permitiendo agregar o eliminar artículos con facilidad, ya que cada uno sigue la 

misma estructura. La página está pensada para proporcionar una experiencia visual limpia y organizada que se puede 

personalizar mediante CSS.
Este código HTML presenta una página web dedicada a "Abrigos de Invierno". En la cabecera (<head>) se incluyen metadatos

como el título (<title>Abrigos</title>), la definición del diseño responsivo para dispositivos móviles 

(<meta name="viewport"...>) y un enlace a un archivo CSS externo (<link rel="stylesheet"...>).

El contenido visible se organiza dentro del <body>. La estructura comienza con un encabezado <header> que contiene un

título principal <h1> para introducir la temática de la página.

La sección principal está definida por un contenedor <div class="container"> que agrupa múltiples artículos 

(<article class="article-card">). Cada artículo representa un abrigo e incluye los siguientes elementos: una imagen 

(<img>) con su ruta (src) y descripción alternativa (alt), un título <h3> con el nombre del abrigo, un párrafo <p> que 

indica su precio, y un contenedor <div class="buttons"> con dos botones (<button>). Uno de los botones tiene un ícono de "me gusta" (❤), mientras que el otro permite seleccionar el artículo.

En el apartado de sudaderas los productos se presentan en tarjetas individuales (<article>) que incluyen una imagen, 

el nombre, el precio y botones para marcar como favorito o seleccionar el artículo. Se muestran ocho sudaderas de marcas

conocidas como Nike, Adidas, Champion, entre otras. Todo está estructurado dentro de un contenedor (<div class="container">) 

y el diseño visual se gestiona a través de un archivo CSS externo. La página es interactiva y organizada, permitiendo 

a los usuarios elegir sus productos favoritos.

En articulos destacados la estructura está organizada dentro de un contenedor (<div class="container">) que agrupa

varios productos, cada uno representado por un artículo (<article class="article-card">).

Dentro de cada artículo se encuentran los siguientes elementosUna imagen del producto (<img>), con el atributo alt para 

descripción accesible.Un título (<h3>) que muestra el nombre del artículo.Un párrafo (<p>) que indica el precio del 

producto.Un bloque de botones (<div class="buttons">) que incluye un botón de "me gusta" (❤) y un botón para seleccionar

el artículo.

Dentro del apartado de pantalones cortos dentro de un contenedor <div class="container">, se presentan varias tarjetas 

de artículo <article class="article-card">, cada una con una imagen del producto <img>, un título <h3> que nombra el 

pantalón corto, un párrafo <p> que muestra el precio del producto y un bloque de botones <div class="buttons"> que 

incluye un botón de "me gusta" (❤) y un botón de "Seleccionar". Los productos incluyen pantalones cortos de marcas 

como Nike, Adidas, Puma, Reebok, Under Armour, Champion, Converse y New Balance, con precios que van desde 25€ hasta 

50€. Todo está estilizado con un archivo CSS externo, brindando una presentación visualmente ordenada e interactiva y 

con esta estructura hemos creado los demas apartados de el HTML  de la pagina web .

CSS:
Stylesheet.css2

El CSS presentado organiza y estiliza una página web de manera profesional, utilizando tipografías modernas como Roboto

y Montserrat y aplicando un diseño responsivo para adaptarse a diferentes dispositivos. Se define una base limpia con body,

eliminando márgenes y paddings predeterminados, aplicando la fuente Roboto y un fondo gris claro (#f4f4f4) para una apariencia

moderna. Los encabezados principales (h1) están diseñados con la fuente Montserrat, un color amarillo brillante (#f9d423)

y un efecto de sombra que los hace destacados y fáciles de identificar como títulos importantes. El encabezado de la página 

(header) utiliza un fondo oscuro semitransparente con un borde inferior amarillo, garantizando que sea distintivo y adecuado

para mostrar títulos o menús.

La navegación se organiza con nav ul en un formato de cuadrícula adaptable, donde los elementos (li) incluyen degradados,

bordes redondeados y un efecto flotante al pasar el ratón, creando una experiencia interactiva y atractiva. Los enlaces 

dentro de los elementos (a) tienen texto en mayúsculas, espaciado entre letras y un efecto de subrayado al pasar el ratón,

mejorando la accesibilidad y profesionalismo. El diseño general se organiza con un contenedor (container) que utiliza un

sistema de cuadrícula adaptable para las tarjetas de contenido (article-card), ajustando el número de columnas según el 

ancho disponible en la pantalla. Las tarjetas tienen un fondo degradado claro, bordes redondeados y sombras que aumentan 

en intensidad y escala al pasar el ratón, haciéndolas visualmente llamativas. Las imágenes dentro de estas tarjetas (img)

se ajustan al tamaño del contenedor con bordes redondeados para mantener la coherencia estética.

Los títulos y descripciones dentro de las tarjetas (h3 y p) están diseñados con colores oscuros y tamaños legibles para resaltar su contenido. Los botones (like-btn y select-btn) son interactivos: el botón de "me gusta" cambia de color al pasar el ratón, incentivando la interacción, mientras que el botón de selección utiliza degradados vibrantes y transiciones suaves que lo hacen destacar, ideal para funciones de confirmación o selección. Finalmente, el diseño incluye un enfoque responsivo mediante una consulta de medios (@media) que adapta la página para pantallas más pequeñas. Esto incluye reducir el tamaño del encabezado, ajustar las cuadrículas de las tarjetas para ocupar menos espacio horizontal y modificar el tamaño de fuente y padding de las tarjetas para mantener la legibilidad en dispositivos móviles
