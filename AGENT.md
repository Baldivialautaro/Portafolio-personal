# Instrucciones para el agente de IA

## Estructura

- Archivos obligatorios: index.html, styles.css, carpeta assets/.
- index.html usa HTML5 semántico: <header>, <nav>, <main>, <section>, <footer>.
- Cada sección de <main> tiene id y un <h2>: sobre-mi, skills, proyectos, contacto.
- Los enlaces externos llevan target="\_blank" y rel="noreferrer".
- Los inputs del formulario van con <label for="..."> vinculado a su id.

## Diseño

- No usar Tailwind CSS. Bootstrap está permitido como opción.
- styles.css en este orden: 1) reset y :root, 2) estilos por sección, 3) @media al final.
- Maquetación con Flexbox y/o CSS Grid.
- Usar clases reutilizables (.btn, .tarjeta, .seccion).
- Combinar px con unidades relativas (rem, %, vh, vw).
