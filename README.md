# Formulario de contacto InstaPET

El formulario de contacto permite a los cuidadores responsables de animales crear un perfil para registrar a su mascota y darle seguimiento en diversos tratamientos veterinarios.

El formulario contiene un conjunto de campos numéricos y alfanuméricos, donde todos ellos son mandatorios.

El formulario es enviado utilizando el botón "Enviar", y el contenido del formulario puede ser eliminado utilizando el botón "Borrar todo". Ambos botones se encuentran en la parte inferior del formulario.

---

## Estructura de la página

El sitio se implementa mediante un único archivo HTML (index.html), organizado de la siguiente forma:

### Header

Resuelve la relación al archivo de estilos (style.css), y establece el vínculo al favicon mostrado en la pestaña del navegador junto al título de la página.

### Body

El cuerpo de la página organiza su contenido en 3 secciones principales:

**Encabezado:** provee el texto descriptivo de la página.

**Formulario:** Organiza los elementos de entrada de datos al formulario, utilizando las siguientes reglas:

1. El elemento \<form> debe establecer la URL de destino para el envío de datos del formulario
2. Por cada campo de entrada (de tipo \<input> o \<select>) debe existir una etiqueta (\<label>) con un texto descriptivo y que establezca una relación al campo de entrada
3. Todos los campos de entrada (de tipo \<input> o \<select>) son mandatorios, debiendo el usuario ingresar datos en cada uno a fin de poder enviar el formulario

**Area de botones**

Implementa fuera del formulario los botones de envío y de limpieza de campos del formulario, a fin de dar un acceso simplifcado a los mismos.

---

## Estilos

El archivo de estilos (style.css) implementa una mínima cantidad de formatos y colores, a fin de mantener el formulario sencillo en su lectura.

El objetivo principal es mantener todo el cuerpo de la página web centrado, establecer un color de fondo neutro y de alto contraste con el color del texto, y un gradiente de colores exclusivamente en el área del formulario para facilitar la identificación del mismo.

Adicionalmente, agrega márgenes horizontales (en pixels) para separar los campos de entrada de sus respectivas etiquetas.
