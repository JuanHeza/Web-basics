# HTML
Es el estandar para la creacion de paginas web, Lenguaje de Marcado de Hipertexto (Hyper Text Markup Language)

Es  el que describe la estructura de la pagina web asi como los elementos que se tienen que dibujar en la misma.

Los elementos usualmente son etiquetas 
	una de apertura <> y una de cierre </>
`` 
	<title> Esto es un tutorial </title>
``
aunque hay algunas que no necesitan ambas como ``<br>`` que es usado como separador, al no tener contenido dentro no necesita cerrarse o ``<input type="text" />`` mismo caso , al ser una entrada de valor (en este caso texto) no necesita la etiqueta de cierre pero se acostumbra cerrar con /, de igual manera funciona igual si la lleva o no

Si revisas el archivo *index.html* veras que contiene 

	<!DOCTYPE html>
	<html lang="es">
		<head>
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	        <title>Plantillas</title>
	        <link rel="icon" type="image/gif" href="favicon.png">       
	        <link rel="stylesheet" type="text/css" href="styles.css">
	    		<style type="text/css"></style>
		</head>
		<body>
			aqui va todo el contenido :)
			<script></script>
		</body>
	</html>

``<!DOCTYPE html>`` sirve para decir al navegador que lo que abrio es un documento HTML y lo debe com}nvertir en una web.

La etiqueta ``<html lang="es">`` es el cuerpo principal del documento, todo lo relacionado a esa pagina debe ir dentro de esa etiqueta, la propiedad lang define el idioma de la pagina, en este caso español

``<head>`` son valores que definen el sitio y es lo que ayuda a los navegadores a renderizar y temas de accesibilidad

``<meta>`` es la metadata del sitio, en este ejemplo habla de el tamaño que puede tener **width=device-width** significa que ocupe todo el ancho de la pantalla, tambien se puede incluir una lista de palabras las cuales se asociaran a la pagina y ayudara a los buscadores a encontrarla, similar a las etiquetas de genero en netflix pero estas propiedades son mas avanzadas asi que pueden quedar fuera de momento

``<title>`` define el nombre del sitio, aparecera en la pestaña del navegador

``<link>`` define los archivos externos que se van a utilizar para el icono (aparece en la pestaña) asi como la hoja de estilos (lo explico despues)

``<style>`` define las propiedades que tendran los elementos del sitio, color, tamaño, posicion, fuente, transparencia, apariencia general y en algunos casos animaciones, los estilos se pueden agregar en el archivo HTML usando esta etiqueta o usando ``<link>`` para llamar un archivo CSS externo, como en el ejemplo

``<body>`` ya es la estructura completa del archivo, ahi van los elementos que seran dibujados, campos de texto, botones, imagenes, cajas, el sitio en general

``<script>`` es similar a ``<style>`` pero diferente, se usa para incluir codigo javascript (js para abreviar) que se usa para muchas cosas, desde hacer las interacciones mas dinamicas como que un boton desaparezca cuando se presiona hasta cosas mas complejas como recopilar datos de un formulario y enviarlos al servidor, se puede escribir todo el codigo dentro de la etiqueta o en un archivo JS pero no es llamado usando usando ``<link>``, se agrega el atributo **src** a esta etiqueta como ``<script src="myscripts.js">``

Eso es lo mas basico, conocer la estructura principal de un archivo HTML, todas las etiquetas *(excepto link, style, script y meta mas que cuando son necesarias)* siempre deben ir en el archivo para que pueda funcionar como es debido

Dicho eso, vamos a ver algunas etiquetas y los usos que estas tienen
[2 - Etiquetas](2-etiquetas.md)