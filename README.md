# Accesibilidad_web
Es una muestra de como mejorar la accesibilidad de una web, a través de herramientas como WAVE o AXE

# Proceso de Mejora de Accesibilidad en HTML

Este repositorio documenta el proceso de mejora de un archivo HTML con problemas de accesibilidad a uno optimizado y accesible. A continuación, se detallan los cambios realizados y cómo se solucionaron los problemas detectados.

---

## Desarrollo del PROMPT: 

El objetivo es mejorar la accesibilidad del código HTML que te voy a pasar para cumplir con los estándares WCAG 2.2 en los niveles AA. Para ello, se deben aplicar varias mejoras, incluyendo:

    -Uso de etiquetas semánticas en lugar de div genéricos.
    -Implementación de atributos ARIA para mejorar la experiencia de usuarios con tecnologías de asistencia.
    -Corrección de jerarquía de encabezados para mantener una estructura lógica.
    -Mejora del contraste entre texto y fondo.
    -Optimización de la navegación por teclado, asegurando accesibilidad en elementos interactivos.
    -Corrección de formularios, incluyendo etiquetas label y atributos aria-required.
    -Claridad en enlaces y botones, asegurando que sus descripciones sean comprensibles.
    -Validación del código con herramientas de accesibilidad como WAVE, Axe y Lighthouse.

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
-Mejorar el contraste de colores (ejemplo, texto negro sobre fondo blanco).






Accede a mi index.html para más información con capturas detalladas del proceso: [AntonioManresa9](https://github.com/AntonioManresa9).
