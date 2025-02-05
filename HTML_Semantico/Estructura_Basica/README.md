# Curso de HTML desde cero a avanzado

# Estructura Básica del HTML Semántico
Teniendo en cuenta el esquema anterior, podremos empezar a estructurar nuestra página web con las etiquetas correspondientes.

Empezaremos creando las siguientes etiquetas:

### Etiquetas de raíz:
```html
<!DOCTYPE html>
<html></html>
```

### Etiquetas de Metadátos:
```html
<head></head>
<meta>
<link>
<script></script>
<title></title>
```

### Etiquetas para seccionar el HTML:
```html
<body></body>
<header></header>
<nav></nav>
<main></main>
<section></section>
<article></article>
<aside></aside>
<footer></footer>
```

Después irán las demás etiquetas para seccionar el HTML o las acciones que tendrá una sección de una página web, sea imágenes, videos o información.

## Gráfico de la estructura HTML en código
Ahora vamos a ver como utilizaremos y cual será el orden en el cual acomodaremos nuestras etiquetas vistas anteriormente.

> Código de un archivo .html:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta>
        <link>
        <script></script>
        <title></title>
    </head>

    <body>
        <header></header>
        <nav></nav>

        <main>
            <section>
                <article></article>
            </section>

            <aside></aside>
        </main>

        <footer></footer>
    </body>
</html>
```

Como podemos observar en el siguiente código html, esa es la regla y estructura que se debe de llevar para crear nuestra página web. Podemos ver que cada etiqueta tiene su abertura y su cierre. Como lo mencione en el anterior archvio a estás estrcuturas se les llama como gráfico de cajas por que son elementos que irán dentro de una caja padre.

Un ejemplo sería la etiqueta **html** esa etiqueta es la caja padre de todo nuestro código y maqueteado html, ya que contiene toda la información que tendrá nuestrá página web.