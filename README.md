# Accesibilidad_web
Es una muestra de como mejorar la accesibilidad de una web, a través de herramientas como WAVE o AXE

# Proceso de Mejora de Accesibilidad en HTML

Este repositorio documenta el proceso de mejora de un archivo HTML con problemas de accesibilidad a uno optimizado y accesible. A continuación, se detallan los cambios realizados y cómo se solucionaron los problemas detectados.

---

## Archivo Original (`index_MALO.html`)

El archivo original tenía muchos problemas de accesibilidad, entre los que se encuentran:

Errores:

-Falta de atributo lang.
-Contraste insuficiente entre el texto y el fondo.
-Imagen sin atributo alt.
-Enlaces no descriptivos ("Click aquí").
-Botón sin texto accesible.
-Formulario sin etiquetas.
-Tabla sin encabezados.

Alertas:

-Uso de <div> en lugar de encabezados.
-Texto en mayúsculas.

## Archivo Modificado (`index_Bueno.html`)

En el archivo modificado hemos corregido dichas alertas y errores, los más significativos son: 

-Agregar el atributo lang al elemento <html>.

-Mejorar el contraste de colores (por ejemplo, texto negro sobre fondo blanco).

-Reemplazar los <div> por encabezados (<h1>, <h2>, etc.).

-Hacer que los enlaces sean descriptivos (por ejemplo, "Descargar XML de Factura 1").

-Agregar texto o atributos ARIA al botón.

-Agregar un atributo alt descriptivo a la imagen.

-Agregar etiquetas <label> a los campos del formulario.

-Usar <th> para los encabezados de la tabla.

-Evitar el uso excesivo de mayúsculas.

-Usar elementos semánticos como <header>, <main>, <footer>, etc.
