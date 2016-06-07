# HTML5-CSS3
## Elementos

Son aquellas etiquetas que describen las diferentes partes de la pagina Web.
Existen elementos que vacíos y otros que no.

### Elementos vacíos

Son aquellos elementos que se describen como el siguiente

      `<img />`

Este tipo de elementos no contienen texto.

### Elementos no vacíos

Son aquellos elementos que contienen texto los cuales tienen una etiqueta de aapretura y otra de cerradura.

Se describen como el siguiente.

       `<em> Aqui puede ir texto </em>`

Note que en la **etiqueta de apertura** se escribe primero el símbolo menor que seguido de el nombre de la etiqueta y por ultimo el símbolo de mayor que. La **etiqueta de cerradura** en cambio consta de una diagonal después de el menor que. <**/**em>


## Atributos y Valores de Marcado

Los atributos contienen información acerca del contenido en el documento. El valor del atributo en HTML5 podría ser encerrado en comillas dobles, y así se seguirá viendo durante el curso.

`<a href="http://www.google.com"> Texto del link que te dirige a google.com</a>`

en este caso. `<a` **href**="_http_"`>` lo marcado en negritas es el atributo  y el texto en italicas que se encuentra dentro de las comillas dobles se refiere al valor de dicho atributo.

## Padres e hijos

Si un elemento contiene otro elemento dentro a este segundo se le llama hijo y al primero se le llama padre.

Supongamos el siguiente ejemplo:

    `<a href="">

        <img src="" alt="">

     </a>`

el elemento a es el padre, y el elemento img es el hijo del elemento a.

En el siguiente ejemplo notaras que los elementos no están anidados correctamente.
  `<a href="">

        <p>

       </a>

    </p>`

Debes de tener cuidado de anidarlos correctamente.
