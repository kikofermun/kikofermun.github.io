---
layout: post
title: Conociendo Markdown
---

En este artículo voy a explicar qué es Markdown y cómo utilizar este lenguaje para dar formato al texto.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/markdown.png)
{:refdef}

### Tabla de contenidos
- [Qué es Markdown](#qué-es-markdown)
- [Poniendo texto en cursiva](#poniendo-texto-en-cursiva)
- [Poniendo texto en negrita](#poniendo-texto-en-negrita)
- [Poniendo texto en cursiva y negrita](#poniendo-texto-en-cursiva-y-negrita)
- [Añadiendo encabezados](#añadiendo-encabezados)
- [Añadiendo listas ordenadas](#añadiendo-listas-ordenadas)
- [Anidando listas ordenadas](#anidando-listas-ordenadas)
- [Añadiendo listas desordenadas](#añadiendo-listas-desordenadas)
- [Anidando listas desordenadas](#anidando-listas-desordenadas)
- [Citas](#citas)

# Qué es Markdown
Cuando pensamos en programar una página web, el primer lenguaje en el que pensamos es en HTML. Sin embargo, existen alternativas, como por ejemplo Markdown. Markdown también es un lenguaje de marcado, como HTML, pero la diferencia es que para dar formato al texto con Markdown se necesitan menos caracteres que haciéndolo con HTML, como vamos a ver en las siguientes tablas.

# Poniendo texto en cursiva
{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/markdowncursiva.png)
{:refdef}

# Poniendo texto en negrita
{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/markdownnegrita.png)
{:refdef}

# Poniendo texto en cursiva y negrita
{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/markdowncursivaynegrita.png)
{:refdef}

# Añadiendo encabezados
{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/markdownencabezados.png)
{:refdef}

# Añadiendo listas ordenadas
Para añadir listas ordenadas con HTML se haría como se muestra a continuación.

~~~ html
<ol>
  <li>
    Elemento 1
  </li>
  <li>
    Elemento 2
  </li>
  <li>
    Elemento 3
  </li>
</ol>
```

Para añadir una lista ordenada utilizando Markdown simplemente hay que añadir el número seguido de un punto y un espacio, tal y como se muestra a continuación.

~~~ markdown
1. Elemento 1
2. Elemento 2
3. Elemento 3
~~~

# Anidando listas ordenadas
Para anidar una lista ordenada con HTML se haría tal y como se muestra a continuación.

~~~ html
<ol>
  <li>
    Elemento 1
    <ol>
      <li>
        Elemento 1.1
      </li>
      <li>
        Elemento 1.2
      </li>
    </ol>
  </li>
  <li>
    Elemento 2
  </li>
  <li>
    Elemento 3
  </li>
</ol>
~~~

Para anidar una lista ordenada con Markdown simplemente hay que añadir tres espacios al elemento que queremos anidar, tal y como se muestra a continuación.

~~~ markdown
1. Elemento 1
   1.1. Elemento 1.1
   1.2. Elemento 1.2
3. Elemento 2
4. Elemento 3
~~~

# Añadiendo listas desordenadas
Para añadir listas desordenadas con HTML se haría tal y como se muestra a continuación.

~~~ html
<ul>
  <li>
    Elemento 1
  </li>
  <li>
    Elemento 2
  </li>
  <li>
    Elemento 3
  </li>
</ul>
~~~

Para hacerlo con Markdown se pueden utilizar los símbolos **-**, **+** o *****, tal y como se puede ver a continuación.

~~~ markdown
- Elemento 1
+ Elemento 2
* Elemento 3
~~~

# Anidando listas desordenadas
Para anidar una lista desordenada con HTML se haría tal y como se muestra a continuación.

~~~ html
<ul>
  <li>
    Elemento 1
    <ul>
      <li>
        Elemento 1
      </li>
      <li>
        Elemento 2
      </li>
    </ul>
  </li>
  <li>
    Elemento 2
  </li>
  <li>
    Elemento 3
  </li>
</ul>
~~~

Para hacerlo con Markdown se haría tal y como se muestra a continuación.

~~~ markdown
- Elemento 1
   - Elemento 1
   + Elemento 2
+ Elemento 2
* Elemento 3
~~~

# Añadiendo tablas
Para crear una tabla con HTML se haría como se muestra a continuación.

~~~ html
<table>
  <tr>
    <th>
       Cabecera 1
    </th>
    <th>
       Cabecera 2
    </th>
  </tr>
  <tr>
    <td>
      Fila 1 Columna 1
    </td>
    <td>
      Fila 1 Columna 2
    </td>
  </tr>
  <tr>
    <td>
      Fila 2 Columna 1
    </td>
    <td>
      Fila 2 Columna 2
    </td>
  </tr>
</table>
~~~

Para crear la misma tabla con Markdown se haría como se muestra a continuación.

~~~ markdown
|Cabecera 1|Cabecera 2|
|-|-|
|Fila 1 Columna 1|Fila 1 Columna 2|
|Fila 2 Columna 1|Fila 2 Columna 2|
~~~

# Citas
Para crear una cita hay que hacerlo con el símbolo _mayor que_ al principio de una frase, tal y como se muestra a continuación.

~~~ markdown
> Ser o no ser, ésa es la cuestión.
~~~

También es posible añadir una cita dentro de otra cita, tal y como se muestra a continuación.

~~~ markdown
>> Ser o no ser, ésa es la cuestión.
~~~
