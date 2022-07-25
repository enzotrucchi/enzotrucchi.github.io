---
layout: post
title: Un nuevo look, un viejo look
---

<h2> Renovación de mi web con Jekyll y GitHub Pages </h2>

Como cualquier renovación, la de mi web personal viene de la mano de una (o varias) necesidades.

Aquí mi lluvía de ideas/necesidades, sin ningún orden de importancia:
- No quería utilizar [WordPress](https://wordpress.com/es/) -otra vez-: No tengo nada en su contra, me parece que, bien utilizada, es una herramienta super sencilla y práctica. Ojo, tiene sus particularidades: Plugins, Base de datos, cositas que no son dificiles de utilizar ni configurar, pero hay que tener ganas.
- No quería quedarme en **HTML/CSS**. Me gusta, me gusta.. Mi sitio anterior (+ algunos construídos en los últimos años) estaba desarrollado siguiendo una plantilla HTML/CSS, pero quería probar algo distinto. Además, cansa un poco la "*lucha*" por tener sitios super estéticos y siguiendo las tendencias de diseño en donde cada año se actualiza un border, un rounded, la forma de presentación de un elemento y demás.
En este caso estaba buscando algo **más minimalista, más práctico, más enfocado al contenido puro**. Lo demás, gracias por ahora.
- Hablando de contenido: Quería que fuese una gran parte de contenido de código, por lo que debía ser fácil utilizar [markdown](https://www.markdownguide.org/) y que el código quede entendible. La otra opción, usar imagenes de algún servicio como [Carbon](https://carbon.now.sh/), pero al momento de copiar/pegar el código (y tambien leerlo), al usuario se le termina haciendo dificil desde una imagen. Vamos a por el buen markdown.
- Dedicarle el menor tiempo posible (y a eso restale unos minutos) al armado de base de datos, configuración de backups, configuración plugins, etc.


## 🔎 Primer intento: Publicando algunas entradas en el Blog [Dev](https://dev.to/enzotrucchi)
Arranqué posteando algunas entradas de prueba en Dev. Si bien soy usuario del Blog desde hace un par de años, está bueno también probar el otro lado. Mi experiencia hasta ahora: Excelente.
- Facilidad para escribir entradas (si bien por lo general uso un editor de Markdown y después copio/pego el contenido).
- Guías de otros usuarios
- Permite crear series de entradas relacionadas.
- Provee un dashboard bastante completo.
- Tiene una gran base de usuarios (si bien la mayoría de habla Inglesa, también hay contenido en español, cómo el mío).

Primera prueba cumplida. DEV.to es genial y voy a seguir utilizandolo en el futuro.
Además, podría servirte [esta](https://dev.to/davidmm1707/should-you-use-medium-or-dev-to-2g1d) comparativa entre DEV y MEDIUM (otra plataforma de Blog muy conocida en el ambiente tech).



## 🔎 Segundo intento: Jekyll + GitHub Pages
Mi segundo intento viene de la mano de [Github Pages](https://pages.github.com/)
En la misma web que linkeo, podes ver que se hace mención a Jekyll como herramienta de Blogging. Por lo tanto no hace falta una explicación tan larga. Alcanza con ver el vídeo introductorio.

En mi caso ya tenía dominio comprado (enzotrucchi.com), pero si ese no fuera el caso, se podría alojar de manera gratuita de la siguiente forma: [username.github.io](enzotrucchi.com)
Las buenas noticias, además de que es gratuito el hospedaje, no paran:

 - Se puede utilizar markdown
 - Hay plantillas de Jekyll por montones, de estilo minimalista, old school o lo que se te ocurra.
 - Se puede hacer live reload si utilizamos Jekyll en local (versiones nuevas nativo, si no se puede bypassear)
 - Está preparado y optimizado para el despligue en GitHub pages: Sólo con un push a la rama indicada, el despliegue con los cambios es automático y se refleja en la web.
 - Se puede utilizar un dominio propio y se configura literalmente en 5 minutos.
 - Permite https
 - Si bien no tiene un gestor de contenido tipo CMS como Wordpress, es fácil crear entradas desde el editor o directamente desde GitHub.

A todo esto, obviamente ya tenemos dos ganadores: Web personal en GitHub pages, Blog de replicación de contenidos: DEV

## 🔎 Tercer intento: Jekyll + GitHub Pages + Jekyll Now
Y si faltaba algo más:
Buscando info y repos de Jekyll, me encontré con la genialidad de [Jekyll Now](https://github.com/barryclark/jekyll-now), quien a partír de un simple Fork, nos deja nuestro blog estilizado de forma minimalista y un diseño que algunos considerarán antiguo pero digamoslé mejor Old School.

En palabras de su creador:
**Jekyll Now** makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup.

Acá podes ver como quedó el repo: https://github.com/enzotrucchi/enzotrucchi.github.io
Y acá [ingresá a mi web](https://enzotrucchi.com)

-----------------
Espero te sirva el post! Recordá que para cada necesidad, hay una o varias soluciones diferentes!

  <img width="50%" style="width:50%" src="https://media.giphy.com/media/peAFQfg7Ol6IE/giphy.gif">

&nbsp;
&nbsp;
[![Invitame un café en cafecito.app](https://cdn.cafecito.app/imgs/buttons/button_6.svg)](https://cafecito.app/enzotrucchi)