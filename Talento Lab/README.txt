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