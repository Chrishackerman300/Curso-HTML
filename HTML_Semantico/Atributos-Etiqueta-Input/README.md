# Curso de HTML desde cero a avanzado

# Atributos de la etiqueta input
En está parte del curso veremos los atributos que tiene la etiqueta **input**.

* ### Atributo value:
El atributo **value** sirve para especificar un valor inicial en el input.

### Sintaxis:
```html
<input value="Nombre">
```

* ### Atributo readonly:
El atributo **readonly** sirve para especificar que un input no se puede cambiar.

### Sintaxis:
```html
<input readonly>
```

* ### Atributo disabled:
El atributo **disabled** con esté el input quedará deshabilitado, **no se puede ciclar y el valor no se envía cuando enviamos el formulario**.

### Sintaxis:
```html
<input disabled>
```

* ### Atributo size:
El atributo **size** especifíca como de ancho tiene que ser el input, y el número de carácteres.

### Sintaxis:
```html
<input size="100px">
```

* ### Atributo maxlength:
el atributo **maxlength** establece el máximo número de carácteres del input.

### Sintaxis:
```html
<ipnut maxlength="300">
```

* ### Atributo autocomplete:
El atributo **autocomplete** define si el formulario o el input debería de tener autocompletado o no por parte del navegador. Los valores son **(off y on)**. Pero **se incluye en el form**.

### Sintaxis:
```html
<input autocomplete>
```

* ### Atributo novalidate:
El atributo **novalidate** es para el form, y especifíca que los datos no tienen que validarse en el envío.

### Sintaxis:
```html
<input novalidate>
```

* ### Atributo placeholder:
El atributo **placeholder** especifíca un texto en el input que se ve antes de rellenarlo con los tiposÑ **text, search, url, tel, email y password**.

### Sintaxis:
```html
<input placeholder="Aqui ponemos lo que querrámos">
```

* ### Atributo required:
El atributo **required** determina si el input debe ser rellenado antes de enviar lso datos del formulario. Funciona con los tipos: **text, search, url, tel, email, password, date, picker, number, checkbox, radio y file**.

### Sintaxis:
```html
<input type="text" required>
<input type="checkbox" required>
<input type="email" required>
<input type="password" required>
```

* ### Atributo step:
El atributo **step** especifíca el intervalo entre los que cambian los números del input. Funciona cono los tipos: **number, range, date, datetime-local, month, time y week**.

### Sintaxis:
```html
<input type="number" step>
<input type="range" step>
<input type="date" step>
<input type="datetime-local" step>
```

> #### En el archivo index html que está en está carpeta del repositorio podrás encontrar como se utilizan cada una de estos atributos de las etiquetas de inputs y verás como se muestra el contenido en tu navegador web.