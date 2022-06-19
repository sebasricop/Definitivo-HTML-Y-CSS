Frontend es la parte de un programa o dispositivo a la que un usuario puede acceder directamente. Son todas las tecnologías de diseño y desarrollo web que corren en el navegador y que se encargan de la interactividad con los usuarios.

Un programador Frontend debe saber de código que entienda el navegador (HTML, CSS y JavaScript) para poder usar algunos frameworks o librerías que expanden sus capacidades para crear cualquier tipo de interfaces de usuarios. React, Redux, Angular, Bootstrap, Foundation, LESS, Sass, Stylus y PostCSS son algunos de ellos.

Herramientas que maneja un frontend
Debido a que un frontend es el desarrollador que va a manejar las cosas del lado del cliente, las tecnologías con las que va a trabajar son:

HTML: https://devdocs.io/html/
CSS: https://devdocs.io/css/
JavaScript: https://devdocs.io/javascript/
Frameworks de CSS para frontend:
Bootstrap: https://getbootstrap.com/
Foundation CSS: https://get.foundation/
Materialize CSS: https://materializecss.com/
Los frameworks de JavaScript para frontend:

React JS: https://es.reactjs.org/
Angular JS: https://angular.io/
Vue JS: https://vuejs.org/
Preprocesadores de CSS:
Stylus: https://stylus-lang.com/
SASS: https://sass-lang.com/
Compiladores / empaquetadores de JS:
BABEL: https://babeljs.io/
Webpack: https://webpack.js.org/
Aporte creado por: Christian Tambo, Manuel Duarte.

Herramientas

Mediaqueri: Algunas ideas sobre como deberíamos implementar el diseño responsive en nuestro sitio.
Coolors: Paletas de colores.
Unsplash: Imagenes gratis (Da los créditos a los fotógrafos 😉).
FontPair: Ver cuales fuentes puedes combinar. Y obviamente Google Fonts para obtener esas fuentes.
Icons8: Iconos, vectores, música y algunos recursos más…
Documentaciones

CSS
HTML
Browserdiet: Optimizar sitios web (Perder peso en la web 😛). Recuerda que Platzi tiene también un curso de Web Performance
WCAG: Guía para mejorar la accesibilidad de nuestro sitio. Recuerda que Platzi tiene el curso de accesibilidad web.
Practica jugando

Grid Layout
Flexbox
Indispensables

Platzi: Para nunca pares de aprender 😉


---------------------------------------------------------------Anatomina de una pagina web

Container: contenedor principal
Header: cabecera de la página. Aquí usualmente encuentras el logo y el menú de navegación del sitio.
Main content: estructura principal. Por ejemplo, el feed o lista de publicaciones de una red social.
Sidebar: contenido secundario de una página, que usualmente se encuentra a los lados del contenido principal (o main).
Footer: pie de página. Esto se encuentra al fondo del sitio web, salvo en casos de sitios web donde el scroll (o navegación hacia abajo) es infinito, por ende, no tendría sentido ponerlo al fondo.

Las etiquetas en HTML nos ayudan a diferenciar en qué parte del contenido nos encontramos.

**La web se conforma de tres conceptos:

URL: Uniform Resource Locator. El identificador único del sitio en el navegador (por ejemplo: https://platzi.com).
HTTP: Protocolo de transferencia de hipertexto. Es el estándar que se utiliza para enviar datos a través de paquetes entre el cliente y el servidor.
HTML: es el código que se emplea para estructurar el contenido de tu web, y darle sentido y propósito.
HTML son siglas que corresponden a Hyper Text Markup Language (Lenguaje de Marcado de Hipertexto).

Hyper Text significa que el texto tiene interactividad, conexión con otros documentos.
Markup significa que le pone etiquetas a los elementos. Por eso también se le conoce como un lenguaje de etiquetas.
HTML es un lenguaje interpretado. Además, HTML es un estándar, así que no importa desde qué navegador o dispositivo se ejecute, el código sigue siendo el mismo en cualquier sitio.

*****--------------------------------------------------------Index y su estructura básica: head

la etiqueta de head y body son contenedores hermanos

HEAD: aca van todas las dependencias, es el cerebro
Body: va lo que se ve en la pagina

<!DOCTYPE html>
<html lang="es"> //Etiqueta padre HTML
    <head>
        <meta charset="UTF-8" /> //Para ver caracteres especiales en la pagina 
        <meta name="description" content="Pagina te mostrara fotos de animales" /> //Muestra descripcion de la pagina
        <meta name="robots" content="index,follow" /> //Sirve para realizar busquedas especificas, autoriza nuestra pagina
        <title>Es mi pagina</title> //titulo de la pestaña
        <meta name="viewport" content="width=device-width, inictial-scale=1.0" /> //Meta para ayudar a escalar texto e imagenes, este es pra dispositivo mobile
        <link rel="stylesheet" href="./style.css" /> //Nos lleva la hoja de estilos
    </head> 
    <body>


    </body>


</html>

*------------------------------------------------------index y su estructura basica body***********

**body es la etiqueta que identifica la parte visible de nuestro sitio web. Dentro del body, se añadirán las etiquetas para marcar los elementos visuales del sitio web, como logotipo, menús de navegación, contenido principal, entre otrs. Es muy importante usar HTML semántico y no llenar todo de <div> para que nuestro sitio sea mejor interpretado por el navegador y, por lo tanto, más accesible.

Etiquetas del cuerpo del documento (body):
article: diferencia partes del contenido que pueden vivir por sí mismas.
nav: para hacer menús de navegación.
aside: contenido menos relevante, como publicidad, etc.
section: sirve para diferenciar las secciones principales del contenido.
header: cabecera del documento.
footer: pie de página del documento.
h1 - h6: títulos de nuestro sitio web.
table: tablas de contenidos, similar a la estructura de las hojas de calculo.
ul y ol: listas de items.
div: cualquier división para organizar el contenido.
h1 a h6: son etiquetas para indicar títulos con un estilo que destaca del resto.
article: es la parte de nuestro contenido que puede vivir por sí mismo. Pueden haber tantos artícle como proyectos o eventos tenga nuestro portafolio.
p: define el texto de un párrafo.
small: aplica una apariencia de texto reducido en tamaño.
strong: aplica al texto un formato de negritas.
a: corresponde a un ancla o enlace a una url interna o externa del documento.
img: con esta etiqueta podemos enlazar imágenes en el documento.
figure: le da un contexto semántico a las imágenes.

 <body>

    <header> <!--Sección superior de nuestro website--> 

      <nav></nav> <!--Sección de navegación de nuestro website, siempre dentro del header-->

    </header>

    <main> <!--Main es el contenido central de nuestro website, "la parte del medio"-->

      <section> 
        <!--Nuestro website puede estar divido por secciones, por ejemplo platzi tiene 3: El navegador de cursos y rutas, el feed y nuestras rutas de aprendizaje-->

        <article>
          <!--Contenido independiente de la página. Es reutilizable-->
        </article>

      </section>

      <ul> <!--Lista desordenada: Sin numerar-->

        <li><!--Item List. Elementos de la lista--></li>

      </ul>

      <ol></ol> <!--Lista ordenada: Numerada-->
      
    </main>

    <footer> <!--Sección final de nuestro website-->

    </footer>

    <p>Soy un texto</p> <!--Párrafo, texto-->

    <h1>Soy un titulo</h1> 
    <!--Títulos, muestran el texto más grande y con negrilla. Existen desde el h1 al h6-->

    <a href="#">Soy un link</a>
    <!--Enlaces/links que nos permitirán movernos entre páginas.-->

  </body>

  -----------------------------Anatomía de una etiqueta de HTML

Una etiqueta HTML puede tener tantos atributos como desees, y cada atributo tiene su propia función. En el siguiente ejemplo, veremos la forma en la que se compone una etiqueta HTML:


No todas las etiquetas llevan una etiqueta de cierre. Las que llevan un cierre son aquellas que albergan un contenido que nos dice a dónde nos va a llevar (nombre de la página, nombre del link).
Lo que va dentro de la etiqueta de apertura es un atributo (nombre del atributo = href y el valor del atributo es la url).
El contenido + la etiqueta = Elemento
Aporte creado por: Rudy Minaya, Andrea Otalora.


------------------------------ETIQUETAS MULTIMEDIA
Formatos de imagenes que Existen

Tenemos 2 tipos de imagenes Lossy y Lossless

Las imágenes representan una pieza fundamental al momento de mostrar contenido para web. Aquí conoceremos los principales tipos de imágenes web y sus formatos.

Tipos de imágenes para web
Lossless (sin pérdida):
Capturan todos los datos del archivo original.
No se pierde nada del archivo original.
Puede comprimirse, pero podrá reconstruir su imagen al estado original

Lossy (con pérdida):
Se aproximan a su imagen original.
Podría reducir la cantidad de colores en su imagen o analizar la imagen en busca de datos innecesarios.
Por consiguiente puede reducir su tamaño, lo que mejora el tiempo de carga de la página, pero pierde su calidad.
Los archivos tipo lossy son mucho más livianos que los archivos tipo lossless, por lo que son ideales para usar en sitios en donde el tamaño del archivo y la velocidad de descarga son importantes.

Formatos de imagen para web
GIF (Graphics Interchange Format): Formato de imagen sin pérdida, no se puede comprimir
PNG 8 (Portable Network Graphics): Formato de imagen sin pérdida, uso de colores de 256, se utiliza para logotipos e iconos para la página.
PNG 24 (Portable Network Graphics): Formato de imagen sin pérdida, utilización de colores ilimitados, alta calidad, si intentamos comprimir no ayudará demasiado por la gran cantidad de colores.
JPG / JPEG (Photographic Experts Group): Formato de imagen con pérdida, perdemos calidad a la hora de comprimirlas, pero llegan a ser óptimas para la carga en la página web.
SVG - Vector (Scalable Vector Graphics): Formato de imagen muy ligero sin pérdida, con svg no perdemos calidad, ya que está compuesta por vectores.
WebP: Es un formato gráfico en forma de contenedor que sustenta tanto compresión con pérdida como sin ella. ​​Fue desarrollado por Google.
Aporte creado por: Luz Urrego, Christian Tambo, Luis Ducuara

---------------------OPTMIZADO DE IMAGENES
https://tinypng.com/
este se recomienda con imagenes JPG, es muy bueno para eso.

https://www.verexif.com/

Sirve para traer todas las imagenes que se traen de las camaras y quitar los metadatos.

No dejar imagenes con 3megas o mas de 3 megas , siempre optimizarlas.

****--------ETIQUETA img
El elemento HTML <img> incrusta una imagen dentro de un documento. A continuación, veremos cómo funciona.

La etiqueta <img> va siempre dentro del contenedor <body>, pues es un elemento visible.

Funcionamiento de la etiqueta alt:
<img src=“ubicación de la imagen” alt=“descripción de la imagen”>

Con esta misma estructura, podemos utilizar el siguiente ejemplo de un estudiante cansado:

<img src=“https://www.ipp.edu.pe/blog/wp-content/uploads/2020/05/shutterstock_1489158410.jpg” alt=“estudiante cansado”>

Al añadir el código que acabamos de crear a un documento, la imagen que se mostrará en el navegador es la siguiente:

Atributos de la etiqueta img
La etiqueta img cuenta con dos atributos, el atributo “src” y el segundo atributo es “alt”. Ambos son importantes.

El atributo de “src” es para mostrar en dónde se encuentra la imagen que vamos a incrustar. Las imágenes se pueden obtener de alguna carpeta o una URL que obtengamos de internet.

En caso de que el nombre de tu imagen lleve algún espacio, deberás sustituir ese espacio con un guion o guion medio. Caso contrario, el navegador no podrá reconocer la ubicación.
alt sirve para agregar una descripción a nuestra imagen. Esto es útil por cuestiones de SEO y también para accesibilidad (por ejemplo para personas con visión reducida).

<img/>, a diferencia de la gran mayoría de las demás etiquetas de HMTL, no necesita una etiqueta de cierre.

Recursos imagenes

https://www.pexels.com/es-es/
https://unsplash.com/

-----------ETIQUETA FIGURE ----ETIQUETA PARA INSERTAR PIE DE PAGINA EN LAS IMAGENES

Figure <figure><img /> </figure> es una etiqueta que permite almacenar una imagen en su interior. Es una mejor práctica comparada con usar solamente un contenedor div. Como complemento al contenedor figure, se utiliza la etiqueta figcaption <figcaption></figcaption>, que permite darle una pequeña descripción a la imagen, como el autor, fuente o algo por el estilo, que se mostrará usualmente abajo de la imagen.

Figcaption se diferencia del atributo Alt porque esta última muestra su descripción en texto en el navegador solamente al pasar el mouse por encima de la imagen (de ahí su utilidad para personas con discapacidad visual).

Es importante considerar que la etiqueta figure no es únicamente para imágenes:
El elemento HTML <figure> representa contenido independiente, a menudo con un título. Por lo general, se trata de una imagen, una ilustración, un diagrama, un fragmento de código, o un esquema al que se hace referencia en el texto principal, pero que se puede mover a otra página o a un apéndice sin que afecte al flujo principal.

<figure>
          <img
            src="./pics/tinified/small.jpg"
            alt="Es una imagen de un perrito"
          />
          <figcaption>Es una imagen de un perrito</figcaption>  
</figure>

-----------ETIQUETA VIDEO ----
para que aparezcan los controles tenemos dos atributos controls 

preload="" Nos ayuda a que le video se pueda empezar a renderizar cuando la pagina se crea en el navegador. es siempre recomendado ponerlo 

   <main>
        <section>
            <video src="./Presentacion.mp4" controls preload="auto"></video>      <!--etiqueta video--> 
        </section>                                                 <!--controls = atributo para habilitar controles en el video Preload = --> 
    </main>

    Existe una parte mas que son cuando tienes un video largo, quieres poner el video a reproducir en timempo especifico, se pone en la parte de source,
    es una extension que sirve para darle parametros de tiempo al video

    <video src="./Presentacion.mp4#t=10,60"  

    #t = es para determinar el tiempo y despues del igual 10 segundos es donde inicia el video y 60 segundos donde termina

    Etiqueta source 
    sirve para manejar diferentes formatos de video.

    ------------------------**************FORMULARIOS****************---------------------------

    ETIQUETA FORM E INPUT*********************

    "
    EL MEJOR FORMULARIO,
    ES CUANDO NO LO HAY 
    "
    ATT: EL USUARIO

forma no recomendada

</head>
<body>
    <main>
        <div>
            <input type="text">
        </div>
    </main>
</body>
</html>


Forma ideal para hacer formularios

 <form action="">
      <label for="nombre">
        <span>Cual es tu nombre?</span>
        <!--span = etiqueta para crear texto dentro del input-->
        <input type="text" id="nombre" placeholder="Tu nombre" />
        <!--atributo placeholder = para agregar visual dentro del input-->
      </label>
      <label for="inicio-platzi">
        <span>Que dia inicio en Platzi?</span>
        <!--span = etiqueta para crear texto dentro del input-->
        <input type="date" id="inicio-platzi" />
      </label>
      <label for="horario">
        <span>En que horario estudias?</span>
        <!--span = etiqueta para crear texto dentro del input-->
        <input type="time" id="horario" />
      </label>
    </form>

recordar = El for del label debe ser siempre igual al id del form
type = date para mostrar formato fecha
type = text para ingresar texto
type = time para ingresar horas

https://developer.mozilla.org/es/docs/Web/HTML/Elemento/input

comentar en visual code ctrl + k => ctrl + c

reemplazar palabra en visual code ctrl + f

Valores autocomplete:

- “off”:
El navegador no puede ingresar o seleccionar automáticamente un valor para este campo. Es posible que el documento o la aplicación proporcione su propia función de autocompletar, o que los problemas de seguridad requieran que el valor del campo no se ingrese automáticamente.

- “on”:
El navegador puede completar automáticamente la entrada. No se proporciona ninguna orientación sobre el tipo de datos que se esperan en el campo, por lo que el navegador puede usar su propio criterio.

- “name”:

El campo espera que el valor sea el nombre completo de una persona. Generalmente se prefiere usar “nombre” en lugar de dividir el nombre en sus componentes porque evita tratar con la amplia diversidad de nombres humanos y cómo están estructurados; sin embargo, puede usar los siguientes valores de autocompletar si necesita dividir el nombre en sus componentes:

"honorific-prefix"
Prefijo tipo “Mrs.”, “Mr.”, “Miss”, “Ms.”, “Dr.”, or “Mlle.”.

"given-name"
Primer nombre (first name)

"additional-name"
Segundo nombre (middle name)

"family-name"
Apellido (last name)

"honorific-suffix"
Sufijo tipo “Jr.”, “B.Sc.”, “PhD.”, “MBASW”, or “IV”.

"nickname"
Un apodo.

- "email"
Dirección de correo electrónico

- “username”:
Nombre de usuario

- “new-password”:
Una nueva contraseña. Al crear una nueva cuenta o cambiar contraseñas, este es el campo “Ingrese su nueva contraseña”, a diferencia de cualquier campo “Ingrese su contraseña actual” que pueda estar presente. Esto puede ser utilizado por el navegador tanto para evitar ingresar accidentalmente una contraseña existente como para ofrecer ayuda para crear una contraseña segura.

- “current-password”:
La contraseña actual del usuario.

-“organization-title”:
Un puesto de trabajo, o el título que tiene una persona dentro de una organización, como “Escritor técnico senior”, “Presidente” o “Líder asistente de tropa”.

- “organization”:
El nombre de una empresa u organización, como “Acme Widget Company” o “Girl Scouts of America”.

- “street-address”:
Una dirección postal. Puede ser varias líneas de texto y debe identificar completamente la ubicación de la dirección dentro de su segundo nivel administrativo (generalmente una ciudad o pueblo), pero no debe incluir el nombre de la ciudad, el código postal o el nombre del país.

- “address-line1”, “address-line2”, “address-line3”:
Cada línea individual de la dirección postal. Estos solo deberían estar presentes si la “dirección postal” también está presente.

- “address-level4”:
El nivel administrativo más detallado, en direcciones que tienen cuatro niveles.

- “address-level3”:
El tercer nivel administrativo, en domicilios con al menos tres niveles administrativos.

- “address-level2”:
El segundo nivel administrativo, en domicilios con al menos dos de ellos. En países con dos niveles administrativos, normalmente sería la ciudad, pueblo, aldea u otra localidad en la que se encuentra la dirección.

- “address-level1”:
El primer nivel administrativo en la dirección. Esta suele ser la provincia en la que se encuentra la dirección. En los Estados Unidos, este sería el estado. En Suiza, el cantón. En el Reino Unido, la ciudad postal.

- “country”:
Código de país

- “country-name”:
Nombre del país

- “postal-code”:
Código postal o ZIP

- “cc-name”:
El nombre completo tal como está impreso o asociado con un instrumento de pago, como una tarjeta de crédito. Por lo general, se prefiere utilizar un campo de nombre completo en lugar de dividir el nombre en pedazos.

- “cc-given-name”:
Nombre (first name) en un instrumento de pago como una tarjeta de crédito.

- “cc-additional-name”:
Un segundo nombre (middle name) como se indica en un instrumento de pago o tarjeta de crédito.

- “cc-family-name”:
Un apellido, tal como figura en una tarjeta de crédito.

- “cc-number”:
Un número de tarjeta de crédito u otro número que identifique un método de pago, como un número de cuenta.

- “cc-exp”:
Una fecha de vencimiento del método de pago, generalmente en el formato “MM / YY” o “MM / YYYY”.

- “cc-exp-month”:
El mes en el que vence el método de pago

- “cc-exp-year”:
El año en el que vence el método de pago

- “cc-csc”:
El código de seguridad del instrumento de pago; en las tarjetas de crédito, este es el número de verificación de 3 dígitos que se encuentra en el reverso de la tarjeta.

- “cc-type”:
El tipo de instrumento de pago (como “Visa” o “Master Card”).

- “transaction-currency”:
La moneda en la que se realizará la transacción.

- “transaction-amount”:
La cantidad, dada en la moneda especificada por “transacción-moneda”, de la transacción, para un formulario de pago.

- “language”:
Un idioma preferido, dado como una etiqueta de idioma BCP 47 válida.

- “bday”:
Una fecha de nacimiento, como una fecha completa.

- “bday-day”:
El día del mes de una fecha de nacimiento.

- “bday-month”:
El mes de una fecha de nacimiento.

- “bday-year”:
El año de una fecha de nacimiento.
**
- “sex”:
Una identidad de género (como “Mujer”, “Fa’afafine”, “Hombre”), como texto de forma libre sin nuevas líneas

- “tel”:
Un número de teléfono completo, incluido el código del país. Si necesita dividir el número de teléfono en sus componentes, puede usar estos valores para esos campos:

“tel-country-code”:
El código de país, como “1” para Estados Unidos, Canadá y otras áreas de América del Norte y partes del Caribe.

"tel-national"
El número de teléfono completo sin el componente de código de país, incluido un prefijo interno del país. Para el número de teléfono “1-855-555-6502”, el valor de este campo sería “855-555-6502”

“tel-area-code”:
El código de área, con cualquier prefijo interno del país aplicado si corresponde.

“tel-local”:
El número de teléfono sin el código de país o área. Esto se puede dividir en dos partes, para los números de teléfono que tienen un número de intercambio y luego un número dentro del intercambio. Para el número de teléfono “555-6502”, utilice “tel-local-prefix” para “555” y “tel-local-suffix” para “6502”.

“tel-extension”:
Un código de extensión de teléfono dentro del número de teléfono, como un número de habitación o suite en un hotel o una extensión de oficina en una empresa.

- “impp”:
Una URL para un punto final de protocolo de mensajería instantánea, como “xmpp: username@example.net”.

- “url”:
Una URL, como una página de inicio o la dirección del sitio web de la empresa, según corresponda, dado el contexto de los otros campos del formulario.

- “photo”:
La URL de una imagen que representa a la persona, la empresa o la información de contacto proporcionada en los otros campos del formulario.

-----------------***ETIQUETA FORM E INPUT

https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete


button - lo podemos utlizar para cualquier boton que deseemos utilizar en el proyecto 

submit - lo podemos utilizar para los formularios 