# Sabio Lector

**Sabio Lector** es una librería en línea enfocada a la *promoción* de obras literarias de *escritores colombianos* publicadas por editoriales pequeñas o que están fuera de un grupo editorial.

La finalidad de **Sabio Lector** es *ofrecer alternativas de promoción* a los autores y a las editoriales para ampliar la visibilidad de sus obras. 
 
 
## Mapa del sitio

El sitio web está compuesto por las páginas:

- [index](./index.html) *(página inicial)*,
  
- [libros](./pages/libros.html) *(catálogo completo)*,
  
- [novedades](./pages/novedades.html) *(últimos lanzamientos)*,
  
- [recomendados](./pages/recomendados.html) *(libros recomendados por nuestro equipo)*,
  
- [contáctanos](./pages/contactanos.html): *(formulario de contacto)*.
 
 
## Control de versiones

- El sitio es construido sobre una estructura de documentos HTML organizada y prolija.

- Se incorpora a la hoja de estilos contenedores flex y grid con el fin de facilitar la acomodación de elementos.

- Se migra la hoja de estilos a SASS a fin de facilitar la escritura de la hoja de estilos.

- Se incorpora los primeros maps, extends y mixins a fin de controlar las transiciones en el color de fondo de los íconos de redes sociales ubicados en el pie de página.

- Se agregan las descripciones y las palabras claves en cada página del sitio a fin de aplicar reglas básicas de posicionamiento SEO.
  
  - Se incluye la misma descripción del sitio en todas las páginas.
  
  - Se incluyen las siguientes palabras clave:
 
    - **index:** *libros*, *cuento*, *cuento en Colombia*, *narrativa*, *narrativa en Colombia*, *novela colombiana*, *poesía colombiana*, *literatura colombiana*, *autores nacionales*, *autores colombianos*, *novedades*, *los más leídos*, *recomendados*.
  
    - **libros:** *libros*, *cuento*, *cuento en Colombia*, *narrativa*, *narrativa en Colombia*, *novela colombiana*, *poesía colombiana*, *literatura colombiana*, *autores nacionales*, *autores colombianos*, *catálogo*.
 
    - **novedades:** *libros*, *cuento*, *cuento en Colombia*, *narrativa*, *narrativa en Colombia*, *novela colombiana*, *poesía colombiana*, *literatura colombiana*, *autores nacionales*, *autores colombianos*, *novedades*.

    - **recomendados:** *libros*, *cuento*, *cuento en Colombia*, *narrativa*, *narrativa en Colombia*, *novela colombiana*, *poesía colombiana*, *literatura colombiana*, *autores nacionales*, *autores colombianos*, *recomendados*.

    - **contáctanos:** *libros*, *cuento*, *cuento en Colombia*, *narrativa*, *narrativa en Colombia*, *novela colombiana*, *poesía colombiana*, *literatura colombiana*, *autores nacionales*, *autores colombianos,* *contacto*, *contáctanos*.
  
- Se valida que los títulos de cada página sean únicos. Los títulos de las páginas se formaron como sigue: **titulo_pagina | Sabio Lector** a excepción de la página de inicio que mantiene el título **Sabio Lector**.

- Se valida la jerarquía de las titulares (encabezados). Cada página tiene un h1 único reservado para el nombre y logo del sitio; varios h2 asignados como títulos a las secciones; varios h3 y h4 para los títulos de los libros y los nombres de los autores; y un solo h6 reservado para el nombre y logo del sitio ubicado en el pie de página. 