CSS:

Cascading Style Sheets : Docuemento con estilo en forma de cascada 

Como inicio mi proyecto con CSS:

Primera forma para vincular el css => 

    <link rel="stylesheet" href="style.css" />    <!--REFERENCIAR CSS, ETIQUETA PARA VINCULAR CSS-->

    Es la mejor forma, es buena practica 

Segunda forma para vincular el CSS =>

    Con la etiqueta Style <style></style> = No es la forma mas adecuada, no es buena Practica, la ponen adentro del head, se utiliza cuando son pocos estilos dentro de la pagina

    <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Clase CSS</title>
    <link rel="stylesheet" href="style.css" />
    <!--REFERENCIAR CSS, ETIQUETA PARA VINCULAR CSS-->
  </head>
  <style>
    p {
      color: yellowgreen;
      font-size: 40px;
    }
  </style>
  <body>
    <main>
      <p>SOY UN TEXTO</p>
    </main>
  </body>
</html>

Tercera forma =>

    Es como atributo directamente en la etiqueta de HTML 

    Dentro del main por ejemplo;

    <main>
        <p style="color: red;">SOY UN TEXTO</p>
    </main>

    Esto se llama estilo enbebido, es inyectarle un estilo al atributo 

    No es buena practica para aplicar el CSS, se debe evitar al maximo

-----------------------

Como llamar las etiquetas o ciertas etiquetas para agregarle los estilos, tenemos tres opciones 

    1. Por el elemento => Quiere decir por la etiqueta a la cual se le agrega estilo particular 
    2. Por la clase => Llegamos a la etiqueta que queremos seleccionar y le agregamos el atributo que se llama class y le ponemos  nombre a esta clase
    3. Por ID => A diferencia del parrafo que empieza con un punto , este empieza con un numeral #

/*Selector por elemento de HTML*/
p {
    color: yellowgreen;
    font-size: 40px;
  }

  /* Class => Selector por clase */
  .parrafo {
      color: blue;
  }

  /* ID  => Selector por ID*/
  #texto {
      color: red;
      font-size: 24px;
  }

  --------------------Pseudo clases y pseudo elementos
A que le vamos a agregar estilos una vez que tengamos nuestra etiqueta

---------------****Metodo para utilizar clases llamado BEN => COMO NOMBRAR MIS CLASES QUE PODAMOS ESCALAR BIEN NUESTROS NOMBRES SIN TENER PROBLEMAS

https://en.bem.info/methodology/faq/#why-bem

Pseudo Classes : class => Define el estilo de un estado especial de un elemento
pseudo elementos :: element => Define el estilo de una parte especifica de un elemento.

-----------------ANATOMIA DE UNA REGLA EN CSS

Selector = P {
  color: => propiedad red; => valor  == declaracion 
}

----------------------
Utilizar tanto id en CSS
Utilizar el !important
Utilizar la etiqueta <style> dentro del archivo html
Utilizar el atributo style dentro de las etiquetas html
Utilizar div para contener todo ignorando los header, nav, section, article, etc.
No utilizar la etiqueta <form> para hacer formularios
Utilizar las etiquetas <select> y <option> para hacer selectores o menús desplegables.
No nombrar el primer archivo html del proyecto como index.html
No tener archivos .css para cada pantalla de un proyecto.
Tener todo el css junto en un solo archivo.
No ponerle el atributo alt a una imagen
Poner imágenes dentro de <div> en vez de <figure>
Utilizar textos solo en mayúscula en HTML, en vez de utilizar el atributo de CSS, text-transform, con el valor uppercase. Ya que al hacer esto pareciera que estuvieras gritando.
Poner videos que se reproduzcan solos.
No optimizar las imágenes.
No tener cuidado de cual es el formato ideal para las imágenes y su respectivo peso.
No tener cuidado con la respectiva semántica de HTML, y con la sintaxis adecuada para CSS.
No cerrar las etiquetas que se cierran en sí mismas como <br/>
No comentar partes esenciales de tu código.
No poner la etiqueta <meta name=”robots” content=”index,follow”> en tu proyecto para que los navegadores los puedan ubicar mejor.
No usar la etiqueta <meta name=”viewpor” content=”width=device-width, initial-scale=1.0”> para hacer tu proyecto responsive.
No poner el atributo autocomplete=”valor” en los campos de tu formulario para hacerle la vida más fácil al usuario
No usar el atributo required en los campos obligatorios de tu formulario como una primera capa de seguridad

------------------------Combinadores: Adjacent Siblings (combinators)


--------------MEDIDAS

medida absoluta: el valor de este no cambia y siempre sera el mismo asi la pagina cambie su tamaño, las medidas absolutas son:
.
mm = milimetros
cm = centimetros
in = pulgada
pc = picas
px = pixel
.

las medidas relativas: estas medidas heredan el tamaño o se basan en algun tamaño que se alla seleccionado y el valor ira cambiando segun si la pagina cambia de tamaño, las medidas relativas son :
.
%
em
rem

Medida em:


