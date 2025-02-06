# Curso de HTML desde cero a avanzado

# Atributos de la etiqueta form
En está parte del curso veremos los atributos que tiene la etiqueta **form**.

* ### Atributo action:
El atributo **action** es la url que porcesa la información enviada por un medio del formulario. Este valor puede ser sobre escrito por un atributo **formaction** en una etiqueta button o el elemento input.

### Sintaxis:
```html
<form action=""></form>
```

* ### Atriuto method:
El atributo **method** es el método HTTP que el navegador usa para enviar el formulario y tiene los valores de **get y post**.

### Post:
Corresponde al método POST, y los datos del formulario son incluidos en el cuerpo del formulario y son enviados al servidor.

### Ejemplo:
```html
<form method="post"></form>
```

### Get:
Corresponde al método GET, y los datos del formulario son adjunto a la URL del atributo action con un **(?)** como separador y la URL resultante es enviada al servidor.

### Ejemplo:
```html
<form action="?" method="get"></form>
```

> #### En el archivo index html que está en está carpeta del repositorio podrás encontrar como se utilizan cada una de estos atributos de las etiquetas de formularios y verás como se muestra el contenido en tu navegador web.