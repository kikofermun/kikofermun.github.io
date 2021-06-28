---
layout: post
title: Trabajando con la propiedad position de CSS
---
En este artículo vamos a intentar entender cómo funciona la propiedad __position__ de CSS.

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
El valor __static__ es el valor por defecto que tiene la propiedad __position__ de un elemento HTML. Este valor permite posicionar a los elementos según el flujo normal de la página; es decir, si una imagen está puesta debajo de un texto, primero se mostrará el texto y luego se mostrará la imagen, tal y como se puede ver en el _ejemplo 2_ y en [este enlace](https://codepen.io/kikofermun83/pen/jOmOEqb){:target="_blank"}.

{:refdef: style="text-align: center;"}
![]({{ site.baseurl }}/images/csspositionejemplo2.png)
{:refdef}
