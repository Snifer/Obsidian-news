---
title: "19 de Noviembre del 2021,Diario Intersticial, conoce QuickADD, generando "
author: Snifer
---

El cuarto Boletín de Obsidian en Español que traemos, un poco tarde por cuestiones personales, pero como cada Semana compartimos contenido y material de la herramienta que usamos de alguna manera en nuestro día a día o tenemos como un uso temporal.



### Que es un Diario Intersticial 

Marilyn integrande del grupo de Telegram nos comparte que es un Diario Intersticial y cual es el uso que podemos darle, para mejorar nuestra productividad. 

La necesidad de automatizar el registro estuvimos resolviéndolo en el grupo. 

## Obsidian para principiantes

Este Boletin les damos material para los que usan Obsidian desde Mobile especificamente desde iOS.

-   [Daily Notes Shortcut V1 1.2k](https://www.icloud.com/shortcuts/8a62a83b13f14aeb85ad021dcc1793d6) - [@ryanjamurphy](https://forum.obsidian.md/u/ryanjamurphy)
-   [Daily Notes Shortcut V2.1 934](https://www.icloud.com/shortcuts/d441152cb2604cb6916ffa892b55d24e) (requires NL Dates plugin) - [@ryanjamurphy](https://forum.obsidian.md/u/ryanjamurphy)
-   [Obsidian URL 921](https://www.icloud.com/shortcuts/fde1a82c7efa449192b3b97220cffebc) - [@ryanjamurphy](https://forum.obsidian.md/u/ryanjamurphy)
-   [Note Bookmark 713](https://www.icloud.com/shortcuts/8b36378ac7cf460abebaab30eea0f03f) - [@ryanjamurphy](https://forum.obsidian.md/u/ryanjamurphy)
-   [Append from Airmail 207](https://www.icloud.com/shortcuts/2f67013e50f34a1ba5a2ee4c879bb770) (requires Advanced URI plugin) - [@ryanjamurphy](https://forum.obsidian.md/u/ryanjamurphy)

Pueden acceder a más información e ideas que comparte la comunidad en él [Foro](https://forum.obsidian.md/t/ios-shortcuts-share-your-ideas/)

### Life Management Obsidian 

En el siguiente video podrás conocer un flujo para Life Disciplines Projects, el cual nos brinda como ir realizando el registro de procesos dias en Obsidian.  

[Life Management Within Obsidian](https://www.youtube.com/watch?v=iMbIGmfUeUA)

- [00:00](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=0s) Preface
- [00:18](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=18s) Intro to Video 
- [00:49](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=49s) Intro to Obsidian 
- [03:04](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=184s) Obsidian Organization
-  [06:23](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=383s) Obsidian Workflow
-  [09:19](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=559s) Obsidian Alignment 
-  [09:00](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=540s) A More Realized Example 
-  [10:16](https://www.youtube.com/watch?v=iMbIGmfUeUA&t=616s) Closing Thoughts

> Tengo en mente ir armando Workflows, y procesos incluso usar algunas ideas de Notion y ver la manera de tenerlo en Obsidian tratando de tener un proceso continuo, que te gustaría que se tenga, puedes describirlo en el grupo de [Telegram](https://t.me/ObsidianEs)

## Aprendizaje de Plugins 

Estuvimos viendo tanto [Dataview](https://obsidian-es.netlify.app/journals/boletin-obsidian-planifica-tu-mes-con-itinerary) como [Templater](https://obsidian-es.netlify.app/journals/boletin-2-bullet-journal-cryptsidian) y [Excalidraw](). 

Esta semana veremos otro plugin que nos permite automatizar algunas tares el cual es QuickADD. 

[How to use QuickADD for Obsidian](https://www.youtube.com/watch?v=gYK3VDQsZJo)

Esta semana que paso en el grupo de [Telegram](https://t.me/ObsidianEs) estuvimos automatizando un proceso con QuickADD, y este pueden verlo en el material que es compartido [[2021-11-19-diario-intersticial]]

## Personaliza tu Obsidian con CSS

Dependiendo del tema que estés usando los Tags se ven en general de un solo color uniforme, pero según tu necesidad o requerimiento en particular puedes customizar estos tags y tenerlos, para ello puedes usar el siguiente snippet y  tenerlo en tus ficheros CSS. 

``` CSS
/* ====== Tag Pills ======== */
.tag:not(.token) {
	background-color: var(--text-accent);
	border: none;
	color: white;
	font-size: 11px;
	padding: 1px 8px;
	text-align: center;
	text-decoration: none;
	display: inline-block;
	margin: 0px 0px;
	cursor: pointer;
	border-radius: 14px;
}
.tag:not(.token):hover {
	color: white;
	background-color: var(--text-accent-hover);
}
.tag[href^="#obsidian"] {
	background-color: #4d3ca6;
}
.tag[href^="#important"] {
	background-color: red;
}
.tag[href^="#complete"] {
	background-color: green;
}
.tag[href^="#inprogress"] {
	background-color: orange;
}
```

Puedes ir agregando diferentes valores adicionando el Color respectivo. 

Fuente: [Uzerper](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/72?u=snifer)
## Plug-ins 

Los plug-ins de esta semana están más orientados a generar Backup o tener un control de versiones desde la misma herramienta con terceros. 

- [Obsidian RSS](https://github.com/joethei/obsidian-rss) extendemos la funcionalidad por defecto de Obsidian contando con un lector de RSS, en lo personal esta funcionalidad puede servir para seguir algunos portales o sitios en particular. 
- [Obsidian Cloudinary](https://github.com/jordanhandy/obsidian-cloudinary-uploader) podras subir a Cloudinary tus capturas de pantalla directamente. 
- [Obsidian imgur](https://github.com/gavvvr/obsidian-imgur-plugin )el servicio de imgur es uno de los más usados actualmente, con este plug-in te permite subir la imagen con un cuanta o de forma anónima, como también los gifs. 
- [Language Translator](https://github.com/twentytwokhz/language-translator) estuvimos en un boletín anterior con el corrector ortográfico, hoy compartimos este traductor de texto en línea, ***recuerda*** como siempre con este tipo de servicios que consultan a terceros tu información es compartida por lo cual usa bajo tu propia responsabilidad. 

### Plug-in de la semana

 [Customizable Page Header](https://github.com/kometenstaub/customizable-page-header-buttons), nos permite adicionar un icono en las notas de Obsidian específicamente en la cabecera, orientado para incrementar la funcionalidad en Mobile,  puesto que estamos algo limitados con los atajos por la propia funcionalidad de la aplicación. 
 
 
#### Configuración e instalación 

Después de instalarlo  por medio de Community Plugins, nos dirigimos al plug-in y veremos que esta desactivado el Botón que limita la funcionalidad solo para Mobile. 


![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/SettingsCustomHeaderPlugin.png)

Al seleccionar Add command  nos muestra la ventana para identificar y seleccionar cuál es el comando que deseamos crear el Shortcut.

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/ButtonQuickADD.png)

 Como prueba de concepto para la realización del Boletín, utilizamos **QuickADD** que realiza la tarea de registrar en mi GTD Personal, en el apartado de ##Inbox, específicamente sobre la nota de Kanban. 
 


![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/Ejemplo_QuickADD.png)

Una vez realices el cambio y adición tendrás al lado del botón de editar el nuevo atajo que has creado, en mi caso llevo por QuickADD para adicionar algo nuevo en mi Inbox y tenerlo en el worflow. 


![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/ResultadoCustomHeader.png)

> Esta configuración es solo un ejemplo, como llegues a realizarlo depende de tus necesidades.

## Obsidian Update

Respecto a LivePreview que contábamos en el anterior boletín estuvieron solucionando algunas funciones y errores que mencione, pronto tendrán para todos los usuarios el acceso a esta funcionalidad. 

## NOTAS

Cualquier comentario puedes hacerlo en el grupo de [Telegram](https://t.me/ObsidianEs) haciendo uso del tag #Boletin04.


