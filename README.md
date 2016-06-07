# HTML5-CSS3
##Semantica de HTML(el marcado y su significado)
* HTML no define como debería aparecer el contenido en el navegador. Esto le toca a las Hojas de Estilos en Cascada(CSS).


* La razón por la cual aparece con cierto formato aunque no tenga alguna hoja de estilo es debido a que cada navegador tiene un archivo de css la cual indica como se deberían de mostrar cada uno de los elementos de manera predeterminada. En dado caso de que se cree una hoja de estilos propias esta podrá sobrescribir estos estilos predeterminados.


* Donde podemos notar de manera clara lo que al anterior punto se refiere seria necesario crear elementos desde h1 al h6 ademas de 2 párrafos y por ultimo un texto dentro de la etiqueta em, debido a que notaras que el la hoja de estilo predeterminada de un navegador renderiza cada etiqueta de manera diferente.

### Nivel bloque o nivel en línea
* Nivel bloque (Block level ) era el nombre que se tenia para aquellos elementos de HTML los cuales se mostraban en su propia linea lo cuales por default se nota como un si fuese un salto de linea entre los elementos en este caso podemos ver los H1 y H2 los cuales están en diferente linea siendo que en ambos les sobra un espacio.

* En linea (Inline) estos son los elementos que se muestra de manera que están dentro de la linea ejemplo observamos que si ubicamos texto dentro de una etiqueta `<em>``</em> ` y este elemento lo escribimos dentro de un elemento `<p>` `</p>` entonces el elemento em ocupara el espacio que requieren las palabras dentro y no aparecerá un salto de linea

   ` <p>`

        Texto del parrafo blablablablabla

        <em> dentro de em </em>

        continuación de texto dentro del elemento p

    `</p>`

En HTML5 los elementos **inline** ahora son nombrados "phrasing content" contenido de fraseo, los cuales son principalmente encontrados dentro de párrafos.


### HTML5 enfoque a la semántica

HTML5 elimina algunos elementos de presentación y re-define otros para que solamente tuvieran **valor semántico**.

Algunos nuevos elementos de HTML5 son **header**, **footer**, **nav**, **article** and **section**.

El objetivo de usar HTML5 es usar todos los elementos aunque sean elementos que se han observado desde antes solo teniendo en cuenta el seleccionar los elementos que mejor describen el significado de el contenido sin considerar la presentación.

De vez en cuando, estarás pensando que una pieza de contenido podría ser marcada en mas de una manera posible, y esta bien. No siempre es una correcta manera o una mala.

HTML5 no provee todos los tipos de elementos existentes pero si abarca la mayoría.

### Por que la semántica importa?

* Mejora la accesibilidad y la inter-operabilidad
* Mejora la optimizacion de busqueda. Search Engine Optimization(SEO).
* Tipicamente codigo mas ligero y paginas mas rapidas.
* Mejor codigo de mantenimiento y estilo.

"El poder de la Web se encuentra en la universalidad. Acceso por todos sin considerar la des-habilidad es un aspecto  esencial."
-"Tim Berners-Lee".Translation created by Alexis Jiménez.
