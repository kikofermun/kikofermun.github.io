En este artículo vamos a explicar qué es y cómo se utiliza el compositor de textos LaTeX.

### Tabla de contenidos
- [Qué es LaTeX](#qué-es-latex)

# Qué es LaTeX
A la hora de crear textos utilizando editores de texto como Word, LibreOffice u otros editores de textos, tenemos que pensar en el formato que le queremos dar a los títulos, el tamaño de letra, y otras características. LaTeX es un sistema de composición de textos que permite crear textos como con un editor de textos pero con un formato ya establecido para los títulos, el tamaño de letra y el resto de características.
LaTeX es una mejora o evolución de TeX, un sistema de tipografía creado por Donald E. Knuth y publicado por primera vez en 1978. El objetivo de TeX era ayudar a matemáticos, físicos e informáticos en la composición de sus textos, que habitualmente incluían nomenclatura compleja. LaTeX, creado por Leslie Lamport en 1984, emplea macros de TeX para utilizar composición tipográfica de una manera más simple que con el TeX original.

# Cómo utilizar LaTeX
Para crear documentos con LaTeX es necesario utilizar editores LaTeX. Algunos de los editores más conocidos son los siguientes:
1. [Lyx](https://www.lyx.org/){:target="_blank"}
2. [TeXmaker](https://www.xm1math.net/texmaker/){:target="_blank"}
3. [TeXstudio](https://www.texstudio.org){:target="_blank"}
4. [Gummi](https://github.com/alexandervdm/gummi){:target="_blank"}
5. [TeXpen](https://sourceforge.net/projects/texpen/){:target="_blank"}
6. [ShareLaTeX](https://www.sharelatex.com/){:target="_blank"}
7. [Overleaf](https://www.overleaf.com/project){:target="_blank"}
8. [Authorea](https://www.authorea.com/){:target="_blank"}
9. [Papeeria](https://www.papeeria.com/){:target="_blank"}

# Creando textos con LaTeX
Para crear textos con LaTeX es necesario utilizar comandos, tal y como se muestra en el siguiente ejemplo:

~~~
\documentclass{article}
% pre\'ambulo

\usepackage{lmodern}
\usepackage[T1]{fontenc}
\usepackage[spanish,activeacute]{babel}
\usepackage{mathtools}

\title{Hola Mundo}
\author{Escribe aqu\'i tu nombre}

\begin{document}
% cuerpo del documento

\maketitle

Mi primer documento en \LaTeX{}.

\end{document}
~~~

En este ejemplo podemos ver que estamos utlizando los siguientes comandos:

- \documentclass
- \usepackage
- \title
- \author
- \begin
- \maketitle
- \end

Los comandos pueden recibir dos tipos de parámetros, que son los siguientes:

- Obligatorios
- Opcionales

Los parámetros obligatorios se escriben entre llaves ({}), tal y como se puede ver en el comando **\documentclass{article}**.

Los parámetros opcionales se escriben entre corchetes ([]), tal y como se puede ver en el comando **\usepackage[spanish,activeacute]{babel}**
