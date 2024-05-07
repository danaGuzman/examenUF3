1.Primero separamos el codigo html al css.
2.Luego vamos a crear la carpeta de documento para poder añadir el readme y utilizarlo como documentaciòn.
3.Creamos una carpeta para la imagen
4.añadiremos esta imagen al archivo html
4.vamos a implementar algunos estilos para mejorar la accesibilidad del color primeramente, esto lo reviso con una extension en firefox de (WCAG Contrast checker).
5.analizamos que hay algun error de accesibilidad en el button, asi que añadiremos un aria-label
6.ahora vamos a analizar la estructura html para poder modificarla correctamente:
 6.1.Vamos añadirme una etiqueta <title>
 6.2.ahora añadiremos la etiqueta <header>, aparte el titulo lo cambiamos por un <h1>, ya que de esta forma podemos indentificar que es el titulo principal
 6.3.ahora añadiremos la etiqueta <main>, esto sirve para guardar o identificar el contenido principal del html.
 6.4.ahora añadiremos <article>, esto sirve para definir contenido independiente o autonomo, asi sabremos que contenido pertenece a una seccion u otra.
 6.5.añadimos las etiquetas <ul> y <li>, las cuales sirven para crear listas con eventos relacionados, de esta forma se vera mucho mejor estructurado el codigo
 6.6.Añadiremos las etiquetas <ul> y <li> en la zona de autores y series para que de esta manera se vean mas ordenado y porque esta informacion esta relacionada entre si, asi que por eso añadi esto
 6.7.borraremos las eitquetas <br> y reemplazaremos con una unica etiqueta <hr>, de esta manera el html se vera mas limpio y organizada su estructura
 6.8.añadiremos etiqueta para el siguiente titulo <h2>, se hace esta para seguir un orden de titulos, y esta estaba con etiqueta <p> lo cual es incorrecto para un titulo
 6.9.añadiremos etiqueta <ul> y <li>, para mejorar el orden de la lista creada.
7.vamos a añadir el ultimo trozo un <footer> ya que esto nos avisaria de alguna forma que hasta alli concluye la pagina web, y tambien nos da informacion extra.
8.hacemos la prueba de accesibilidad para poder comprabar que sea 100% accesible y me daba un error de que el html no tenia la etiqueta del lenguaje asi que se la añadi.
9.añadiremos etiquetas aria para el header con un rol de banner para indicar que esto es el encabezado de la pagina web.
10.en la <main> añadimos roll=main para indicar que este elemento contiene el contenido principal de la pagina web.
11.en el <footer> hemos añadido ese rol para indicar que este es el pie de pagina de la web
12.se añade un aria-label al <button>, para describir la funcion de este boton.
13.revisamos todo el codigo y añadimos algunas modificaciones restantes como organizar los espacios y esto de manera rapida y sencilla.
14.por ultimo añadiremos css para hacer algo mas bonito en la pagina web y que le sea mas agradable al usuario.
15.revisamos que la accesibilidad este bien y todo correcto.