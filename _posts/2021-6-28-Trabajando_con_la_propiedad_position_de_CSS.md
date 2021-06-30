---
layout: post
title: Trabajando con la propiedad position de CSS
---
En este artículo vamos a intentar explicar cómo funciona la propiedad __position__ de CSS.

Cuando trabajamos con un documento HTML, tenemos la posibilidad de especificar cómo posicionar cada uno de los elementos. Ésto lo podemos conseguir utilizando la propiedad __position__ de CSS, tal y como se muestra en el _ejemplo 1_ y en [este enlace](https://codepen.io/kikofermun83/pen/BaRBXqo){:target="_blank"}.

{:refdef: style="text-align: center;"}
![]({{ site.baseurl }}/images/csspositionejemplo1.png)
{:refdef}

{:refdef: style="text-align: center;"}
_Ejemplo 1_
{:refdef}

Los valores de esta propiedad pueden ser los siguientes:

- static
- relative
- absolute
- fixed
- sticky

Cada uno de estos valores permite posicionar un elemento de diferentes formas.

# static
El valor __static__ es el valor por defecto que tiene la propiedad __position__ de un elemento HTML. Este valor permite posicionar los elementos según el flujo normal de la página; es decir, si una imagen está puesta debajo de un texto, primero se mostrará el texto y luego se mostrará la imagen, tal y como se puede ver en el _ejemplo 2_ y en [este enlace](https://codepen.io/kikofermun83/pen/jOmOEqb){:target="_blank"}.

{:refdef: style="text-align: center;"}
![]({{ site.baseurl }}/images/csspositionejemplo2.png)
{:refdef}

{:refdef: style="text-align: center;"}
_Ejemplo 2_
{:refdef}

# relative
El valor __relative__ permite que, al elemento que le apliquemos la propiedad __position__ con este valor, podamos modificarle la posición que ocuparía en el flujo normal de la página utilizando las propiedades __top__, __left__, __right__ y/o __bottom__. En el _ejemplo 2_, si a la imagen le aplicásemos la propiedad __position__ con valor __relative__ y le modificásemos la posición vertical utilizando la propiedad __top__ con valor __-10px__, lo que estaríamos haciendo es subir su posición vertical 10 píxeles de su posición original en el flujo normal de la página, tal y como se puede ver en el _ejemplo 3_ y en [este enlace](https://codepen.io/kikofermun83/pen/VwbwYzV){:target="_blank"}.

{:refdef: style="text-align: center;"}
![]({{ site.baseurl }}/images/csspositionejemplo3.png)
{:refdef}

{:refdef: style="text-align: center;"}
_Ejemplo 3_
{:refdef}

# absolute
El valor __absolute__ se diferencia del valor __relative__ en que el segundo permite especificar la posición a partir de su posición original en el flujo normal de la página, mientras que el primero permite especificar la posición según los bordes que contiene el elemento (elemento padre).
En el _ejemplo 3_ tenemos una imagen que no está contenido por ningún elemento, así que su elemento padre es el propio documento. Si a esta imagen le aplicásemos la propiedad __position__ con el valor __absolute__ y le modificásemos la posición con el valor __0px__ para las propiedades __top__ y __left__, estaríamos posicionando la imagen en la esquina superior izquierda del documento, tal y como se puede ver en el _ejemplo 4_ y en [este enlace](https://codepen.io/kikofermun83/pen/GRmgWJB){:target="_blank"}.

{:refdef: style="text-align: center;"}
![]({{ site.baseurl }}/images/csspositionejemplo4.png)
{:refdef}

{:refdef: style="text-align: center;"}
_Ejemplo 4_
{:refdef}

Si en el ejemplo anterior la imagen estuviera contenida por una etiqueta div con la propiedad __position__ con valor __relative__, el elemento padre sería esta etiqueta y por lo tanto la imagen se posicionaría en la esquina superior ixquierda del elemento padre de la imagen, que en este caso es la etiqueta _div_. En este caso, la posición sería la misma que la que ocuparía en el flujo normal de la página, tal y como puede verse en el _ejemplo 5_ y en [este enlace](https://codepen.io/kikofermun83/pen/dyWPvRm){:target="_blank"}

{:refdef: style="text-align: center;"}
![]({{ site.baseurl }}/images/csspositionejemplo5.png)
{:refdef}

{:refdef: style="text-align: center;"}
_Ejemplo 5_
{:refdef}

# fixed
El valor __fixed__ es parecido al valor __absolute__. La diferencia entre el primero y el segundo es que el segundo posiciona el elemento teniendo en cuenta la página web, mientras que el el primero posiciona el elemento teniendo en cuenta el área visible del navegador, manteniendo fijo el elemento en la posición que le hemos indicado. Si en el _ejemplo 4_ a la imagen le pusiéramos el valor __fixed__ a la propiedad __position__, al hacer scroll la imagen se mantendría siempre visible en la esquina superior izquierda del área visible del navegador, tal y como se puede ver en el _ejemplo 6_ y en [este enlace](https://codepen.io/kikofermun83/pen/mdmyWxa){:target="_blank"}.

{:refdef: style="text-align: center;"}
![]({{ site.baseurl }}/images/csspositionejemplo6.png)
{:refdef}

{:refdef: style="text-align: center;"}
_Ejemplo 5_
{:refdef}
