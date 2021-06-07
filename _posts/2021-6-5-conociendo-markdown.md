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
- [Editores de Markdown online](#editores-de-markdown-online)
- [Poniendo texto en cursiva](#poniendo-texto-en-cursiva)
- [Poniendo texto en negrita](#poniendo-texto-en-negrita)
- [Poniendo texto en cursiva y negrita](#poniendo-texto-en-cursiva-y-negrita)
- [Añadiendo encabezados](#añadiendo-encabezados)
- [Añadiendo listas ordenadas](#añadiendo-listas-ordenadas)
- [Anidando listas ordenadas](#anidando-listas-ordenadas)
- [Añadiendo listas desordenadas](#añadiendo-listas-desordenadas)
- [Anidando listas desordenadas](#anidando-listas-desordenadas)
- [Añadiendo tablas](#añadiendo-tablas)
- [Añadiendo citas](#añadiendo-citas)
- [Creando enlaces](#creando-enlaces-automáticos)
   - [Creando enlaces en línea](#creando-enlaces-en-línea)
   - [Creando enlaces por referencia](#creando-enlaces-por-referencia)
   - [Creando enlaces automáticos](#creando-enlaces-automáticos)
   - [Creando anclas](#creando-anclas)
- [Visualizando código](#visualizando-código)
- [Utilizando bloques de código](#utilizando-bloques-de-codigo)

# Qué es Markdown
Cuando pensamos en programar una página web, el primer lenguaje en el que pensamos es en HTML. Sin embargo, existen alternativas, como por ejemplo Markdown. Markdown también es un lenguaje de marcado, como HTML, pero la diferencia es que para dar formato al texto con Markdown se necesitan menos caracteres que haciéndolo con HTML, como vamos a ver en este artículo.

# Editores de Markdown online
Para poder hacer pruebas de lo que se va a comentar a continuación, se pueden utilizar editores de Markdown online. Algunos de estos editores pueden ser los siguientes:

- [Dillinger](https://dillinger.io/){:target="_blank"}
- [StackEdit](https://stackedit.io/){:target="_blank"}
- [Editor.md](https://pandao.github.io/editor.md/){:target="_blank"}

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

![_config.yml]({{ site.baseurl }}/images/markdownlistaordenadahtml.png)

Para añadir una lista ordenada utilizando Markdown simplemente hay que añadir el número seguido de un punto y un espacio, tal y como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownlistaordenadamarkdown.png)

# Anidando listas ordenadas
Para anidar una lista ordenada con HTML se haría tal y como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownlistaordenadaanidadahtml.png)

Para anidar una lista ordenada con Markdown simplemente hay que añadir tres espacios al elemento que queremos anidar, tal y como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownlistaordenadaanidadamarkdown.png)

# Añadiendo listas desordenadas
Para añadir listas desordenadas con HTML se haría tal y como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownlistadesordenadahtml.png)

Para hacerlo con Markdown se pueden utilizar los símbolos **-**, **+** o __*__, tal y como se puede ver a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownlistadesordenadamarkdown.png)

# Anidando listas desordenadas
Para anidar una lista desordenada con HTML se haría tal y como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownlistadesordenadaanidadahtml.png)

Para hacerlo con Markdown se haría tal y como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownlistadesordenadaanidadamarkdown.png)

# Añadiendo tablas
Para crear una tabla con HTML se haría como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdowntablahtml.png)

Para crear la misma tabla con Markdown se haría como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdowntablamarkdown.png)

# Añadiendo citas
Para crear una cita hay que hacerlo con el símbolo _mayor que_ al principio de una frase, tal y como se muestra a continuación.

`> Ser o no ser, ésa es la cuestión.`

> Ser o no ser, ésa es la cuestión.

También es posible añadir una cita dentro de otra cita, tal y como se muestra a continuación.

`>> Ser o no ser, ésa es la cuestión.`

>> Ser o no ser, ésa es la cuestión.

# Creando enlaces
En Markdown existen cuatro tipos de enlaces, que son los siguientes:
- Enlaces en línea.
- Enlaces por referencia.
- Enlaces automáticos.
- Anclas

## Creando enlaces en línea
Los enlaces en línea se crean utilizando corchetes y paréntesis, donde entre los corchetes tiene que ir el texto del enlace y entre los paréntesis tiene que ir la url del enlace, tal y como se muestra a continuación.

`[Google](http://google.es)`

[Google](http://google.es)

También es posible hacer que se abra en una nueva pestaña de la siguiente forma.

`[Google](http://google.es){:target="_blank"}`

[Google](http://google.es){:target="_blank"}

## Creando enlaces por referencia
Los enlaces por referencia se crean utilizando dos corchetes, donde en un corchete irá el texto del enlace y en el otro corchete el texto de la referencia, creando previamente el enlace de referencia. Ésto se hace tal y como se muestra a continuación.

`[google]: http://google.com`

`[Google][google]`

[google]: http://google.com

[Google][google]

También es posible hacer que se abra en una nueva pestaña de la siguiente forma.

`[Google][google]{:target="_blank"}`

[Google][google]{:target="_blank"}

## Creando enlaces automáticos
Los enlaces automáticos se crean escribiendo la url entre los símbolos _menor que_ y _mayor que_, tal y como se muestra a continuación.

`<http://google.com>`

<http://google.com>

También es posible hacer que se abra en una nueva pestaña de la siguiente forma.

`<http://google.com>{:target="_blank"}`

<http://google.com>{:target="_blank"}

# Creando anclas
Las anclas se crean como los enlaces en línea pero poniendo una almohadilla y el título de la sección en lugar de la url, tal y como se puede ver a continuación.

`[Creando enlaces](#creando-enlaces)`

[Creando enlaces](#creando-enlaces)

# Visualizando código
Para visualizar código de Markdown o de otro lenguaje sin que cambie el formato de texto, se puede hacer de dos formas:

- Con texto situado entre dos caracteres de acento abierto (`texto`).
- Añadiendo cuatro espacios antes del texto.

Estos métodos para visualizar código sólo se pueden aplicar a una línea.

# Utilizando bloques de código
Existe una tercera forma de visualizar código, pero en este caso aplicándolo a varías líneas a la vez. Consiste en encerrar texto entre seis virgulillas o seis acentos abiertos, tal y como se muestra a continuación.

![_config.yml]({{ site.baseurl }}/images/markdownbloquesdecodigo.png)
