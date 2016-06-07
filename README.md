# HTML5-CSS3
## Contenido de Texto de una pagina Web

Cuando el navegador renderiza HTML este colapsa espacios o tabulaciones extras en una sola linea resolviéndolo como un soloo espacio ademas de ignorar los saltos de linea.

Vamos a hacer un mini ejemplo:

   `<p>`

        Notas que

        si tengo saltos de linea no se muestran en

        el navegador web.

  `</p>`

Si agregamos esto en un documento con la extensión .html y lo abrimos en algún navegador web notaras que sucede.

## Etiqueta HEAD

Es una practica estandar codificar las paginas con el set de caracteres UTF-8 el cual permite utilizar todos los caracteres  American Standard Code for Information Interchange(ASCII).

`<head>`

    <meta charset="UTF-8">

    <title>Document</title>

`</head>`

## Referencia de entidades de caracteres en HTML4

Aun se siguen utilizando en HTML5 entidades de caracteres que se usaban en HTML4

Como es el simbolo de copyright o caracteres especiales

Ejemplo:

`&szlig;` el cual es el siguiente caracter ß

`&copy;` el cual es el siguiente caracter ©

`&eacute;` el cual es el siguiente caracter é

Aqui agrego el footer de nuestra pagina

`   <footer>`

        &copy Alexis Miguel Jim&eacutenez Olivares <br/>

        &copy Alexis Miguel Jiménez Olivares

`    </footer>`
