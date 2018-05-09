# Sitio web de noticias de tecnología con scroll

https://rawgit.com/quiquer7/Tarea---6-y-7/master/news.html

He realizado este sitio web con las librerías jQuery y Bootstrap.

### Boceto de la página principal news.html
https://rawgit.com/quiquer7/Tarea---6-y-7/master/Bocetos%20del%20sitio%20web/newshtml.jpg

### Boceto de la página de noticia (news1.html, news2.html, news3.html)
https://rawgit.com/quiquer7/Tarea---6-y-7/master/Bocetos%20del%20sitio%20web/news1-2-3html.jpg

Los bocetos son muy simples, pero expresan correctamente la idea de diseño final.

La página principal carga 3 noticias. Si hacemos scroll, aparecen nuevas noticias de 3 en 3 gracias a los documentos newsjs2.json y newsjs3.json.

El archivo news.js es el que se encarga de cargar las noticias de los dos archivos .json.

Al llegar abajo, cuando no hay más noticias aparece una alert de Javascript diciendo que no hay más noticias. 

La página principal cuenta con un slider o carrusel para acceder a las principales noticias el sitio.

La publicidad en pantallas grandes aparece en la derecha de la pantalla con un tamaño de 336 px de ancho.

Si la pantalla donde se visualiza el sitio es pequeña, aparece en el centro de la parte superior, un banner publicitario de 90 px de alto que desaparece al hacer scroll para abajo.

En ningún momento aparecen los dos banners publicitarios juntos, están ajustados para salir el de 90px en pantallas pequeñas y el de 336px en pantallas grandes.

Abajo del todo en la página news.html he dejado un footer con la página Facebook del sitio web y un correo electrónico.
También hay un mensaje de Copyright y un botón para visualizar el RSS del sitio web.

Las noticias de news1.html, news2.html, news3.html, contienen una imagen, el cuerpo de la noticia y un vídeo, así como otros extras como el autor o la fecha.

Todas las páginas html contienen las etiquetas meta necesarias.

He probado la correcta visualización y funcionamiento del sitio en dos de los principales navegadores, Chrome y Firefox, tanto para PC como para dispositivos móviles.

En Chrome he tenido que instalar la extensión Suscripción a RSS para que se visualizaran los estilos css, ya que en mi ordenador se veía como texto plano sin esa extensión.
La publicidad no aparece en Chrome, cuando se carga el sitio web con RawGit. He probado con Firefox y con este si que aparece, incluso en Edge o en Opera aparece.
Utilizo Dreamweaver y Xampp para desarrollar los proyectos, y en la previsualización de la página en tiempo real, en Chrome si que aparece la publicidad, solo me pasa esto con RawGit.

Todas las imagenes están retocadas y comprimidas con Photoshop CC 2018.


## Validaciones del código

### Validación HTML
#### news.html
https://validator.w3.org/nu/?doc=https%3A%2F%2Frawgit.com%2Fquiquer7%2FTarea---6-y-7%2Fmaster%2Fnews.html

#### news1.html
https://validator.w3.org/nu/?doc=https%3A%2F%2Frawgit.com%2Fquiquer7%2FTarea---6-y-7%2Fmaster%2Fnews1.html

#### news2.html

#### news3.html


### Validación CSS
#### d.css
https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frawgit.com%2Fquiquer7%2FTarea---6-y-7%2Fmaster%2Fcss%2Fd.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=es

#### m.css
https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frawgit.com%2Fquiquer7%2FTarea---6-y-7%2Fmaster%2Fcss%2Fm.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=es

### Validación XML
#### rss.xml
https://www.xmlvalidation.com/index.php?id=1&L=0

(El enlace es al validador de XML, pero he comprobado que no tiene errores de sintaxis)


### Validación JSON

### Validación JS
Código Javascript probado y funcionando al 100%.

