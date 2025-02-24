---
layout: post
title: Creando un blog en Github con Jekyll
---

En este artículo voy a explicar cómo crear un blog en Github como el que estás viendo ahora mismo utilizando Jekyll.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubyjekyll.png)
{:refdef}

### Tabla de contenidos
- [Darnos de alta en Github](#darnos-de-alta-en-github)
- [Bifurcando el repositorio de Jekyll](#bifurcando-el-repositorio-de-jekyll)
- [Cambiando el nombre al repositorio bifurcado](#cambiando-el-nombre-al-repositorio-bifurcado)
- [Modificando el fichero de configuración](#modificando-el-fichero-de-configuración)
- [Traduciendo al español](#traduciendo-al-español)
- [Escribiendo un artículo](#escribiendo-un-artículo)

# Darnos de alta en Github
Antes de empezar a crear un blog en Github con Jekyll, lo primero que tenemos que hacer es darnos de alta. Para ello, en primer lugar tenemos que dirigirnos a la [página de Github](https://github.com/){:target="_blank"} y clicar en __signup__, que está en la zona marcada con un rectángulo con un borde rojo en la siguiente imagen.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubsignup.png)
{:refdef}

A continuación nos aparecerá una nueva pantalla (imagen de abajo) donde tendremos que rellenar todos los datos que nos piden y realizar la verificación.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubsignup2.png)
{:refdef}

Una vez hayamos rellenado todos los datos, si todo ha ido bien, ya estaremos dados de alta y logueados en nuestra cuenta de Github.

# Bifurcando el repositorio de Jekyll
Ahora que ya estamos dados de alta y logueados en nuestra cuenta de Github, para crear un blog en nuestra cuenta de Github con Jekyll, lo primero que tenemos que hacer es bifurcar el repositorio de Jekyll en nuestra cuenta de Github. Para ello, vamos a ir a la [url de Jekyll](https://github.com/barryclark/jekyll-now){:target="_blank"} y vamos a clicar en el botón donde pone __Fork__, que está en la zona marcada con un rectángulo con un borde rojo en la siguiente imagen.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubfork.png)
{:refdef}

Cuando hayamos pulsado en el botón, una vez haya acabado la bifurcación, nos redirigirá al repositorio que ha bifurcado en nuestra cuenta de Github.

# Cambiando el nombre al repositorio bifurcado
El siguiente paso que tenemos que hacer es cambiar el nombre del repositorio bifurcado. Para ello, en la página a la que nos ha redirigido, pulsaremos en el botón de __Settings__ y cambiaremos el nombre del repositorio por nuestro nombre de usuario seguido por _.github.io_, que en el caso de la imagen de abajo sería __kikofdezmun.github.io__.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubrename.png)
{:refdef}

Una vez hayamos renombrado el repositorio, si ahora vamos a la url con el nombre que le hemos puesto al repositorio, que en el caso de este blog es [kikofermun.github.io](https://kikofermun.github.io){:target="_blank"}, podremos ver que ya tenemos un blog creado al que sólo le tenemos que hacer modificaciones para adaptarlo a nuestro gusto.

# Modificando el fichero de configuración
A continuación vamos a modificar algunos de nuestros datos personales que se encuentran en el fichero ___config.yml__. Para ello, tenemos que ir a nuestro repositorio, que en el caso de este blog es [https://github.com/kikofermun/kikofermun.github.io](https://github.com/kikofermun/kikofermun.github.io){:target="_blank"} y buscar el fichero ___config.yml__ (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubficheroconfig.png)
{:refdef}

Una vez lo hayamos encontrado, tenemos que clicar sobre él y, cuando nos haya redirigido al fichero, pulsar en el botón que nos permite editarlo (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubbotoneditar.png)
{:refdef}

En este fichero vamos a modificar los datos que se han modificado en este blog, que son los que se muestran en las siguientes imágenes.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubname.png)
{:refdef}

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubdescription.png)
{:refdef}

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubavatar.png)
{:refdef}

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubemail.png)
{:refdef}

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubgithub.png)
{:refdef}

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githublinkedin.png)
{:refdef}

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubtwitter.png)
{:refdef}

# Traduciendo al español
A continuación, todo lo que aparece en inglés vamos a traducirlo al español. El primer elemento que vamos a cambiar es el **About** que aparece en la parte superior derecha (imagen de abajo) por **Sobre mi**.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubabout.png)
{:refdef}

Para ello tenemos que dirigirnos a nuestro repositorio, a la carpeta **_layouts** y buscar el fichero **default.html** (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubdefault.png)
{:refdef}

Una vez lo hayamos encontrado, clicamos sobre él y pulsamos sobre el botón para editarlo (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubdefault2.png)
{:refdef}

La línea que queremos modificar es la que se muestra en la siguiente imagen.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubabout2.png)
{:refdef}

Queremos que en lugar de mostrarse **About** se muestre **Sobre mi**. Para ello, la modificación quedaría como se muestra en la siguiente imagen.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubsobremi.png)
{:refdef}

El siguiente elemento que queremos cambiar es la fecha que se muestra al final de cada artículo (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubfecha.png)
{:refdef}

Para modificar esta fecha tenemos que editar el fichero **post.html** que se encuentra en la carpeta **_layouts**. Dentro de este fichero tenemos que buscar las siguientes líneas de código (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubdate.png)
{:refdef}

Estas líneas de código las sustituiremos por las siguientes (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubfecha2.png)
{:refdef}

Una vez hecha esta modificación, la fecha se mostraría en el siguiente formato (imagen de abajo).

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubfecha3.png)
{:refdef}

# Escribiendo un artículo
Lo último que nos falta por saber es cómo escribir un artículo. Para ello simplemente hay que añadir un fichero con extensión **md** en la carpeta **_posts** por cada artículo que queramos añadir al blog. Una vez creado, hemos de clicar sobre él, clicar en el botón para poder editarlo y empezar a escribir.

{:refdef: style="text-align: center;"}
![_config.yml]({{ site.baseurl }}/images/githubpost.png)
{:refdef}

Es importante tener en cuenta que en los ficheros con extensión **md** hay que escribir utilizando el lenguaje **markdown**. Si estás interesado en apender sobre este lenguaje, visita el artículo en el que hablo sobre ésto.
