# Autos

## Navegacion

- **Navbar:** La pagina debe tener una [barra de navegacion](https://www.w3schools.com/css/css_navbar.asp) por la cual se pueda acceder a cualquiera de las 4 secciones.
- **Footer:** La pagina debe tener un [pie de pagina](https://www.w3schools.com/tags/tag_footer.asp) con el nombre del autor y un hipervinculo a (esta pagina)[]

## Secciones

### Pagina Principal

- Debe tener un titulo con el nombre de la pagina ( a eleccion ), que sera el mismo que el que aparece en la pestaña ( [title](https://www.w3schools.com/tags/tag_title.asp) )

- Debe tener una foto de portada que ocupe el 80% a 90% del ancho de la pantalla ( [ejemplo](https://www.porsche.com/middle-east/) )

- Debe tener 3 parrafos de por lo menos 3 lineas, se puede usar texto de relleno ( [lorem ipsum](https://docs.emmet.io/abbreviations/lorem-ipsum/) )

### Catalogo y Noticias

- Ambas pantallas tendran [tarjetas](https://www.w3schools.com/w3css/w3css_cards.asp) ( [ejemplo](https://nicolasezequielzulaicarivera.github.io/projects.html), [otro](https://material.io/components/cards#behavior) )
- Las tarjetas estaran dentro de un contenedor con `display:flex` de modo que se ajusten al tamaño de la pantalla ( ver achocando la pantalla del ejemplo )
- Cada seccion requiere por lo menos 3 tarjetas diferentes ( diferentes contenidos ) y 9 tarjetas en total ( pueden ser copias )


#### Contenidos de las tarjetas

- Tarjeta **Catalogo** : 
  - Nombre del Auto
  - Imagen
  - Elemento a eleccion ( Precio, Velocidad, etc ) - por lo menos 1

- Tarjeta **Noticia**
  - Titulo de la noticia
  - Breve descripcion
  - Elemento a eleccion ( imagen, link, etc ) - por lo menos 1

### Contacto

- [Formulario](https://www.w3schools.com/html/html_forms.asp)
  - Inputs de por lo menos 3 tipos diferentes
  - Por lo menos 2 botones (submit, reset, etc)

## Estilo

- Utilizar un estilo simple ( [ejemplo](https://blog.hubspot.com/marketing/examples-brand-style-guides) )
- Elegir un color primario y secundario
  - Utilizar donde parezca mejor ( botones, header, links, bordes, [hover](https://www.w3schools.com/csSref/sel_hover.asp), etc ), por lo menos 3 veces el primario y 1 el secundario
- Fondo blanco, texto negro
- Utilizar [`box-shadow`](https://www.w3schools.com/cssref/css3_pr_box-shadow.asp) para demarcar las tarjetas
- Utilizar otro color de fondo para header / footer

## Estructura del proyecto

📂 pagina_autos         \
 ┣━📂 js                \
 ┣━📂 css               \
 ┃ ┗━📄 style.css       \
 ┣━📂 html              \
 ┃ ┣━📄 catalogo.html   \
 ┃ ┣━📄 noticias.html   \
 ┃ ┗━📄 contacto.html   \
 ┗━📄 index.html
 
 ## Otros
 
 - Todas la imagenes deben tener texto alternativo (alt)

 
 
