# web-2o-trimestre
La página la he creado yo solo y su temática es de venta de productos electrónicos, específicamente ordenadores y móviles.
A continuación voy a explicar cada parte de la página, empezando por su estructura:

La página está compuesta por dos carpetas con los scripts y las imágenes, además de las páginas de HTML y CSS por separado:  

![1](https://i.imgur.com/DuBhDsg.png) 

Sobre los scripts, la página contiene 7:

- cambiarcolor.js: Para cambiar de color el texto de la página.
  
- textocursor.js: Añade una función al cursor con la que se muestra una palabra al ponerse sobre cualquier imagen.
  
- ventanaemergente1y2.js: Estos son dos scripts separados, pero aquí los pongo juntos porque su función es la misma, hacer aparecer dos ventanas emergentes que sirven como publicidad.
  
- barrabusqueda.js: Para buscar las secciones que se encuentran en la página, pudiendo reconocer cualquier nombre que contenga las letras introducidas.
  
- carrusel.js: Permite la funcionalidad del carrusel de imágenes.
  
- formulario.js: Permite recibir una respuesta automatizada al enviar el formulario de contacto.

Todos ellos están comentados en los archivos de la web.



Al cargar la página, lo primero que llama la atención son las ventanas emergentes que aparecen gracias a los scripts "ventanaemergente1y2.js", que actúan como anuncios de productos de la propia página. Estos son interactivos, ya que pueden ser eliminados por el usuario si lo desea.

![2](https://i.imgur.com/x34ZDYH.png)



Ahora, empezando con la estructura de la página, lo primero que se encuentra es la cabecera, que está compuesta por los siguientes apartados:

![3](https://i.imgur.com/WJbKK02.png)  

- El logo funciona como un botón que redirige al usuario al inicio, es decir, al mismo sitio en el que está.
  
- El botón "Categorías" almacena los enlaces a las principales secciones de la página (Sobremesa, portátiles y móviles) que se encuentran ocultos en un principio.

- El enlace "Contacto" redirige a la sección de contacto que se encuentra en la parte inferior de la página.

- Un botón que incluye la función de cambiar el color del texto de la página, permitiendo personalizarla con cualquier color posible.

- Una barra de búsqueda que es puramente estética y que únicamente contiene un script (barrabusqueda.js) para reconocer las principales secciones de la página si el usuario escribe sus nombres o alguna letra que coincida.

![4](https://i.imgur.com/0vmPlI8.png)



Continuando con la siguiente sección, hay un carrusel de imágenes que funciona con dos botones para moverse entre los diferentes productos. Aquí se aplican dos scripts, el de "carrusel.js" y el de "textocursor.js" (aunque este está en cualquier sección que tenga imágenes).

![5](https://i.imgur.com/EHw76rD.png)

Luego empieza las pincipales secciones, que en cuanto a la estructra son iguales. Están compuestas de un título, una frase y cuatro productos separados en dos, con sus nombres y precios. Tienen también un botón llamado "Ver características" que está de adorno y no es necesario incluirlo.

![6](https://i.imgur.com/rhlhewf.png).
![7](https://i.imgur.com/dF8pq6G.png)
![8](https://i.imgur.com/hiyxdeR.png)


Finalmente está la sección de contacto, en la que se encuentra un formuulario de contacto que imita lo que sería el envío de datos por parte del usuario gracias al script "formulario.js", que muestra un mensaje cuando el formulario es enviado.

![9](https://i.imgur.com/BfCsNsG.png)

También es responsive, lo que significa que se adapta a diferentes tipos de dispositivos, cosa que se puede comprobar en la función "Inspeccionar" dentro de la web, aunque igualmente pondré un par de imágenes para mostrarlo. Además, las principales casillas que hay que rellenar contienen atributos que hacen que sea obligatorio rellenarlas todas, además de otras condiciones.

![10](https://i.imgur.com/ejIsUIY.png)
![11](https://i.imgur.com/RmyR4IF.png)

En resumen y hablando de la interactividad, los principales puntos que se demandaban en la rúbrica se han cumplido, como se ha podido ver en la documentación. Por esto creo que, aunque siendo mejorable, la web es correcta dentro que lo que se pedía hacer.
