# Curso de HTML desde cero a avanzado

# Etiquetas de Metadatos del Document
Estás etiquetas son las que van hasta arriba de nuestro código de html, estás se irán colocando después de la etiqueta **html** ya que estás etiquetas representán información acerca de nuestro documento web. Las cuales son las siguientes:

* ### Etiqueta head:
Está etiqueta representa una colección de metadatos acerca del documento, incluyendo **(enlaces, definiciones de scripts y hojas de estilos)**. El resto de las etiquetas de metadatos irán dentró de está etiqueta **y no serán visibles en nuestra página web**.

### Sintaxis:
```html
<head></head>
```

* ### Etiqueta meta:
Está etiqueta es usada para definir **otros metadatos que no se pueden definir con una etiqueta html en específico**. Y está etiqueta es huerfána.

### Sintaxis:
```html
<meta>
```

* ### Etiqueta link:
Está etiqueta se usa para enlazar recursos externos a nuestra web como **archivos de estilos, archivos de JavaScript, estilos de letras, etc**. Y está etiqueta es huerfána.

### Sintaxis:
```html
<link>
```

* ### Etiqueta title:
Está etiqueta se usa oara definir el titulo de nuestra página web, **solo se puede usar una vez en todo nuestro documento html**.

### Sintaxis:
```html
<title></title>
```

Si juntamos lo que vimos de nuestras etiquetas de raíz con nuestros metadatos tendremos esto:

### Ejemplo:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta>
        <title></title>
    </head>
</html>