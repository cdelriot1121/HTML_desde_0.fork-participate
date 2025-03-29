# Aprendiendo HTML desde cero

## ¿ Qué es HTML?
HTML (HyperText Markup Language) es el lenguaje de marcado utilizado para crear páginas web. Es el estándar para estructurar contenido en la web y se utiliza junto con CSS (Cascading Style Sheets) y JavaScript para crear sitios web interactivos y visualmente atractivos.

## Estructura de un documento HTML
Un documento HTML básico tiene la siguiente estructura:

```html
<!DOCTYPE html> 
<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Título de la página</title>
        <link rel="stylesheet" href="styles.css"> <!-- Enlace a un archivo CSS externo -->
    </head>
    <body>
    </body>
</html>
```
### Desglose de la estructura:
- `<!DOCTYPE html>`: Declara el tipo de documento y la versión de HTML que se está utilizando. En este caso, HTML5.
- `<html lang="es">`: Elemento raíz del documento HTML. El atributo `lang` especifica el idioma del contenido (en este caso, español).
- `<head>`: Contiene metadatos sobre el documento, como el título, la codificación de caracteres y enlaces a archivos CSS o scripts.
- `<meta charset="UTF-8">`: Especifica la codificación de caracteres utilizada en el documento. UTF-8 es la más común y soporta una amplia gama de caracteres.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configura la vista para dispositivos móviles, asegurando que el contenido se ajuste al ancho de la pantalla.
- `<title>`: Define el título de la página que se muestra en la pestaña del navegador.
- `<link rel="stylesheet" href="styles.css">`: Enlaza un archivo CSS externo para aplicar estilos al documento HTML.
- `<body>`: Contiene el contenido visible de la página web, como texto, imágenes, enlaces y otros elementos multimedia.
- `</body>`: Cierra el elemento `<body>`.
- `</html>`: Cierra el elemento `<html>`, indicando el final del documento HTML.

## Elementos HTML básicos
Los elementos HTML son las piezas fundamentales que componen un documento HTML. Aquí hay algunos de los elementos más comunes:

- `<h1>` a `<h6>`: Encabezados de diferentes niveles. `<h1>` es el más importante y `<h6>` el menos importante.
- `<p>`: Define un párrafo de texto.
- `<a>`: Crea un enlace a otra página o recurso. Se utiliza el atributo `href` para especificar la URL del destino.
- `<img>`: Inserta una imagen en la página. Se utiliza el atributo `src` para especificar la URL de la imagen y `alt` para proporcionar un texto alternativo.
- `<ul>`: Crea una lista desordenada (con viñetas).
- `<ol>`: Crea una lista ordenada (numerada).
- `<li>`: Define un elemento de lista, que puede ser parte de una lista desordenada o ordenada.
- `<div>`: Un contenedor genérico que se utiliza para agrupar otros elementos y aplicar estilos o scripts.
- `<span>`: Un contenedor en línea que se utiliza para aplicar estilos a una parte del texto o a un grupo de elementos en línea.
- `<header>`: Define la cabecera de un documento o sección, que generalmente contiene el título y la navegación.
- `<footer>`: Define el pie de página de un documento o sección, que generalmente contiene información de contacto, derechos de autor y enlaces adicionales.
- `<main>`: Define el contenido principal de un documento, que es único y relevante para la página.
- `<section>`: Define una sección temática dentro de un documento, que puede contener encabezados, párrafos y otros elementos.