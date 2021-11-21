---
title: "12 de Noviembre del 2021,Uso de Daily Notes, Exporta tus notas con Pandoc, Excalidraw, WYSIWYG experimental en Obsidian"
author: Snifer
---

Este Boletín venimos con un Feature, que muchos pedían  a Obsidian y es la opción de LivePreview aun en modo Beta, pero a punto de llegar para todos, ya que ahora esta solo para los Insiders. 


## Obsidian para principiantes

Mucho llegamos a leer y conocer sobre las notas diarias *Daily Notes* en Obsidian y viene la pregunta de como crear la plantilla y usarla con el Plug-in Calendar es por ello para todos los que inician compartimos el material que es realizado en el foro. 

- [How use Daily Notes]( https://forum.obsidian.md/t/how-i-use-daily-notes/3057)
- [Using Templates in Obsidian](https://thesweetsetup.com/using-templates-in-obsidian/)

Otro potencial dolor de cabeza es el cómo convertir los ficheros Markdown en otros formatos, como ser PDF, Doc o ppt, para comprender este proceso tenemos [Pandoc](https://github.com/OliverBalfour/obsidian-pandoc) que esta inegrado con un plugin en Obsidian. 

En esta charla de la Comunidad nos brindan  lo necesario para comprender el proceso.

- [Using Pandoc to write PDFs, Word documents, and slideshows in Markdown](https://www.youtube.com/watch?v=yYZiO6CVtj8)



Tengo en mente ir armando Workflows, y procesos incluso usar algunas ideas de Notion y ver la manera de tenerlo en Obsidian tratando de tener un proceso continuo, que te gustaría que se tenga, puedes describirlo en el grupo de [Telegram](https://t.me/ObsidianEs)

## Aprendizaje de Plugins 

Estuvimos viendo tanto [Dataview](https://obsidian-es.netlify.app/journals/boletin-obsidian-planifica-tu-mes-con-itinerary) como [Templater](https://obsidian-es.netlify.app/journals/boletin-2-bullet-journal-cryptsidian) en los dos boletines pasados, hoy venimos con el Plugin Excalidraw que permite realizar diagramas a mano, tipo Sketch, para ello contamos con una serie de videos creada por el mismo creador del Plug-in, tienen aquí la mejor fuente, desde la creación de mapas mentales y presentaciones a diagramas más elaborados, teniendo tu propio PKM visual. 

- [Zsolt's Visual PKM](https://www.youtube.com/channel/UCC0gns4a9fhVkGkngvSumAQ)


## Personaliza tu Obsidian con CSS

Compartimos un par de temas en esta sección los cuales tienen como objetivo ser minimalistas.

- [Typomagical for Obsidian](https://github.com/hungsu/typomagical-obsidian)  un tema ligero  que puede agradarte. 

![](https://forum.obsidian.md/uploads/default/original/3X/b/2/b2a6c60006b3f2ccea037b3639d115a54758696c.gif)

Este tema igual viene del evento [OBSIDIAN October 2021](https://publish.obsidian.md/hub/Events/Obsidian+October+2021).

- [Obsidian Mnimal](https://github.com/kepano/obsidian-minimal) su nombre lo describe  un tema que deja bastante limpio Obsidian para enfocarse en escribir, lo tienes tanto en modo Oscuro como Claro.

![](https://github.com/kepano/obsidian-minimal/raw/master/dark-complex.png)


- [Obsidian Style Settings](https://github.com/mgmeyers/obsidian-style-settings) nos permitirá configurar algunos estilos por medio de CSS directamente que vienen pre configurados.


## Plug-ins 

Los plug-ins de esta semana están más orientados a generar Backup o tener un control de versiones desde la misma herramienta con terceros. 

- [Obsidian Git](https://github.com/Clemens-E/obsidian-languagetool-plugin) nos ayuda a realizar un control de versiones y generar nuestro Backup respectivo de nuestro Vault enfocandonos, a tener el control de cambios en caso de no perder.

- [Obsidian Aut-O-Backups](https://github.com/ryanpcmcquen/obsidian-dropbox-backups) genera de forma automática cada cierto periodo de tiempo de forma periódica  todo el proceso de configuración con Dropbox tienes en la descripción del plug-in. 

- [Cryptsidian](https://github.com/triumphantomato/cryptsidian)  es el plug-in que debe de ir de cajón cuando usamos servicios de terceros evitando que terceros accedan a información sensible, en el Boletin02 especifique el uso y como trabaja este plug-in. 

Adicionalmente puedes usar cualquier otro servicio como ser Google Drive, iCloud, Drive o el que gustes. 
### Plug-in de la semana

- [Obsidian Remminder](https://github.com/uphy/obsidian-reminder) este plug-in lo uso dentro de mi workflow de GTD con Obsidian. 

Para registrar una tarea tenemos que ponerla con el formato de un Checkbox y entre parentesis la fecha seguido de la hora de forma automática sin importar las notas donde tengas  las tareas se adiciona un nuevo Panel llamado Remminder, puedes ver el ejemplo.

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin3/RemminderPlugin.png)

Además una funcionalidad que me agrada y mucho es la integración con Kanban y con las notificaciones del sistema operativo.

Para conocer un poco más del plug-in puedes acceder a la [guia](https://uphy.github.io/obsidian-reminder/guide/) oficial. 

## Modo Debug

En modo Debug, esta semana tenemos el Live Preview en Obsidian ademas de un breve demo
### Actualizaciones que vienen en Obsidian.

Muchos estaban esperando  esta opcion en Obsidian es la posibilidad de tener el ***Live Preview*** en Obsidian, es decir un **Editor integrado** que se pueda seguir mas visualmente todos los cambios que se vayan teniendo aun para los que no están acostumbrados a Markdown y desean ver cuál será el resultado de lo que van realizando al momento. 

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin3/LivePreviewObsidian.gif)


Para activarlo nos dirigimos a **Editor** después a la parte inferior **Experimental Live Preview** marcamos,  y procedemos a *reiniciar* con los comandos `Ctrl + P` **Reload App**

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin3/ExperimentalPreview.png)


**NOTA:** Actualmente esta actualización está solo disponible para los Insiders.  Paso a describir como deben de configurar para recibir este** Build** en particular.


![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin3/ConfiguracionInsiderBuild.png)

Deben considerar que con esta funcionalidad algunos plug-ins dejaran de funcionar por la actualización a `Codemirror6`,  todos los que estén con `Codemirror 5` no funcionaran correctamente, como también algunos de edición. 

Lo que estuve probando, no funciona aún en Live Preview los bloques de código, mermaid, modo VIM tampoco. 


¿El último boletín trabajamos con Cryptsidian lo utilizaste?

## NOTAS

Cualquier comentario puedes hacerlo en el grupo de [Telegram](https://t.me/ObsidianEs) haciendo uso del tag #Boletin03.