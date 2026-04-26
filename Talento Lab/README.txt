Clase1
Ejercicio práctico #1:
Crear la estructura básica del proyecto, incluyendo las etiquetas <header>, <main>, <nav> y <footer>. 
Dentro de <header>, incluye un título <h1> con el nombre del proyecto.

Clase2
Ejercicio práctico #1:
Crear un bloque <nav> que contenga una lista desordenada (<ul>).
● Dentro de esa lista, agregá elementos (<li>) con enlaces (<a>).
● Usá ejemplos como: "Inicio", "Productos", "Contacto".
● Simulá que los enlaces llevan a secciones internas del sitio.

Ejercicio práctico #2

Inserción de imagen y video

1. Descargar y preparar los archivos:
○ Buscá una imagen que represente el logo de tu sitio web.
○ Guardala como logo.png en la misma carpeta que tu HTML.
Elegí un video representativo (video.mp4) y
descargá también los subtítulos en .vtt si están disponibles (o crealos como subtitulos.vtt).
2. Incorporar la imagen en el <header>:
○ Usá la etiqueta <img src="logo.png" alt="Logo de tu sitio web">.
3. Insertar el video en el <main>:
○ Creá una <section> para insertar el video.
○ Usá la etiqueta <video> con controls.
○ Incluí los subtítulos usando <track src="subtitulos.vtt" kind="subtitles" srclang="es" label="Español">.

Clase3
Ejercicio práctico #1:
Crear un Formulario de Contacto
¿Qué tenés que hacer?
Dentro de la etiqueta <main>, creá un formulario usando Formspree para que pueda enviar mensajes.
El formulario debe incluir:
● Un campo para Nombre (<input type="text">)
● Un campo para Correo electrónico (<input type="email">)
● Un campo para Mensaje (<textarea>)
● Usá la acción y método que Formspree indica para que el formulario funcione correctamente.
● Documentá en tu README.md cómo configuraste Formspree y por qué es útil.

Ejercicio práctico #2:
Crear una tabla de datos de contacto + inspección
¿Qué tenés que hacer?
Dentro del mismo <main>, agregá una tabla que muestre información ficticia de personas que ya enviaron el formulario. (Nombre, correo, mensaje corto, estado del mensaje).
Usá etiquetas <table>, <thead>, <tbody>, <tr>, <th>, <td>.
1. Aplicá una combinación de celdas con colspan o rowspan para representar algo más complejo. Por ejemplo, una fila combinada que diga "Mensajes pendientes de respuesta".
2. Luego, con las herramientas de inspección del navegador (F12 o clic derecho → "Inspeccionar"), revisá:
● La estructura real del HTML.
● Qué pasa si cambiás estilos desde la consola.
● Cómo se ve el padding o el border de cada celda

clase4

Ejercicio práctico #1
Incorporar CSS externo
¿Qué tenés que hacer?
● Crear un archivo llamado styles.css en la misma carpeta donde está tu archivo HTML.
● Vincular ese archivo CSS dentro del <head> de todos tus HTML con la línea:
<link rel="stylesheet" href="styles.css">
● Asegurarte de tener un <header> con un título y un <footer> con un texto de derechos reservados.
<header> <h1>Mi Sitio Web</h1> </header> <footer> <p>© 2024 Mi Sitio Web. Todos los derechos reservados.</p> </footer>
● En el archivo styles.css, aplicar estilos para:
○ Cambiar el color de fondo del header y footer.
○ Cambiar el estilo de la fuente (tipo, tamaño, color).
○ Aplicar márgenes o padding para separar elementos.
○ Usar al menos un selector de clase y un selector de elemento.

Ejercicio práctico #2:
Modificar la barra de navegación (Navbar)
¿Qué tenés que hacer?
● Asegurarte que tu HTML tiene una barra de navegación similar a esta:
<nav> <ul> <li><a href="#">Inicio</a></li> <li><a href="#">Acerca de</a></li> <li><a href="#">Servicios/Productos</a></li> <li><a href="#">Contacto</a></li> </ul> </nav>
● En styles.css, aplicar estos estilos:
○ Usar list-style: none; para que la lista no tenga viñetas.
○ Quitar el subrayado de los enlaces con text-decoration: none;.
○ Cambiar el color del texto de los enlaces con la propiedad color.


clase5
Ejercicio práctico #1
Tipografía con Fuente Externa
Usar Google Fonts para personalizar las fuentes del sitio web.
Pasos a seguir:
1. Ingresá a https://fonts.google.com y elegí dos fuentes:
○ Una para los títulos.
○ Otra para los párrafos.
2. Copiá el enlace que te da Google Fonts y pegalo dentro del <head> de tu archivo HTML.

Ejercicio práctico #2:
Fondo personalizado
Aplicar un fondo visual que refleje estilo y coherencia de diseño.
Opciones posibles:
● Imagen de fondo: agregá una imagen al body o a una sección con background-image.
● Degradado: usá background: linear-gradient(...) para generar un efecto moderno.


Clase6
Ejercicio práctico #1
Crear tarjetas de producto con estilos completos
Tomás (Desarrollador Senior)
“Ahora que dominan medidas, colores, fuentes y el modelo de caja, ¡es momento de crear algo más real! Vamos a construir tarjetas de producto usando todas las propiedades que fueron aprendiendo.”
¿Qué tenés que hacer?
Dentro de tu page servicios/productos en una sección dentro del <main> (<section class="productos">), creá al menos 3 tarjetas de producto pueden utilizar etiquetas como <article> .
Cada tarjeta debe tener:
● Imagen del producto
● Nombre del producto (con fuente externa)
● Descripción breve
● Precio destacado
● Un botón de “Agregar al carrito” con ícono de Font Awesome o Flaticon.

Ejercicio práctico #2
Crear tarjetas de producto con estilos completos
Tomás (Desarrollador Senior)
“Ahora que dominan medidas, colores, fuentes y el modelo de caja, ¡es momento de crear algo más real! Vamos a construir tarjetas de producto usando todas las propiedades que fueron aprendiendo.”
¿Qué tenés que hacer?
Dentro de tu page servicios/productos en una sección dentro del <main> (<section class="productos">), creá al menos 3 tarjetas de producto pueden utilizar etiquetas como <article> .
Cada tarjeta debe tener:
● Imagen del producto
● Nombre del producto (con fuente externa)
● Descripción breve
● Precio destacado
● Un botón de “Agregar al carrito” con ícono de Font Awesome o Flaticon.
(<a>).
En tu CSS, usá display flex en la lista para distribuir horizontalmente los ítems.
Usá propiedades como:
● justify-content: space-around o space-between
● text-decoration: none para quitar el subrayado
● padding, color, background-color para darle estilo
