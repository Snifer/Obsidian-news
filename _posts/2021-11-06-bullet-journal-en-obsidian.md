---
title: "Crea tu Bullet Journal con Obsidian"
tags: BuJo 
categories: BulletJournal
comments: true
author: Lormes16 Laura
---


Desde que comencé a usar Obsidian para gestionar todas mis notas me di cuenta de que podía ser una buena herramienta para llevar un Bullet Journal digital. Este método de organización está concebido para llevarlo en papel, pero lo cierto es que algunas personas prefieren llevarlo en digital. 

Aunque yo no voy a dejar mi libreta, no pude dejar de pensar en ello y me puse manos a la obra creando una bóveda para un BuJo. En este artículo quiero compartir la manera más sencilla que yo he encontrado para llevarlo con esta herramienta.

Para ello vamos a necesitar algunos plugin externos y tener activado dentro de los plug-in principales, Template o Plantillas. 

Dentro de los plugin externos he decidido usar los siguientes:
- *Calendar*
- *Periodic notes*
- *Task*
- *Advanced tables*
- *Dataview*

Por otro lado hemos de crear una serie de plantillas:
- *Registro de Futuros*
- *Registro mensual*
- *Registro semanal*
- *Registro diario*
- *Colección*

Aunque no es parte del método he agregado también un registro semanal. Y Ahora que ya lo tenemos todo, comencemos a montar nuestro Bullet Journal. 

Con el plugin **Calendar**, aparte de tener un calendario en Obsidian podemos crear y gestionar nuestro registro diario de forma más visual. Pero si lo unimos al plug-in **Periodic notes** podremos gestionar todos nuestros registros, no solamente el diario. Solo hemos de indicarle que plantilla ha de utilizar en cada caso y en que carpeta queremos que los guarde.  

![[DailyNOtes.jpg]]

![[MontlyNotes.jpg]]

 Ya solo nos queda añadir un atajo de teclado para cada uno de esos registros. En mi caso les he puesto:
 
    
 
 | Atajo   | Registro |
 | ------- | -------- |
 | Alt + d | Diario   |
 | Alt + w | Semanal  |
 | Alt + m | Mensual  |
 | Alt + y | Anual    |

 
Además el registro dirio y semanal podremos también crearlos desde el calendario haciendo click en el día o semana correspondiente.

![[calendarPlugin.jpg]]



Veamos ahora los dos plugin siguientes, **Task** y **Advanced tables**

Con **Task**, podremos dentro de una nota crear y modificar las tareas de forma fácil. Aparte de generar listas de tareas y gestionarlas como mejor deseemos. Puedes mirar la documentación del plugin [aquí](https://schemar.github.io/obsidian-tasks/)

![[CreateEditTask.jpg]]

Con **Advanced tables**, podremos generar una tabla rápidamente y además tendremos una paleta de comandos para modificarla. 

![[AdvanceTables.jpg]]

Y con esto tendríamos la estructura del Bullet Journal más dos plugin que nos ayudarna con las tareas y tablas.  Con lo que nos faltaría el *Índice* para poder acceder al contenido que vayamos creando. Este no será igual que el que llevamos en papel y lo he pensado de la siguiente manera: 

![[Template.jpg]]

Es más parecido a un MOC que a un índice.  Desde aquí enlazaremos con:

- El registro de futuros que hayamos creado con Periodic Notes. 
- La nota mensual principal que enlaza a todos los meses.
- La nota colecciones que enlazará con todas las colecciones que hagamos. 
- El atajo de teclado para crear el registro diario. 

Tanto la nota mensual como la de colecciones estarán automatizadas y se iran actualizando sin que tengamos que hacerlo de forma manual. Y aquí es donde entra el plug-in **Dataview**.
Con esteplug-inn se pueden realizar muchas cosas, listas, tablas... y poder jugar con la meta datos que hemos agregado en nuestras notas. 

En esta ocasión lo usaremos para obtener una lista de meses y una lista de colecciones. 
El código sería de esta manera:

```
```dataview
list from "REGISTRO MENSUAL" and #mes 
sort file.time asc
```


```
```dataview
list from "NOTAS PERMANENTES" and #colección 
where file.name != "Colecciones"
sort file.name asc
```

En nuestra plantilla de registro mensual tendríamos que añadir la etiqueta #mes
y en la de colección la etiqueta #colección
 
Pues ya tenemos nuestro Bullet Journal listo para utilizarlo. Se puede dar un paso más y automatizar por ejemplo las tareas pendientes de días anteriores, o disponer plantillas más avanzadas con las que poder hacer más cosas, Y utilizar algunos plug-in más que son realmente interesantes. Pero eso ya lo veremos en otro artículo. El objetivo es crear un Bullet Journal sencillo y fácil en Obsidian, Y eso ya lo tenemos. 

Como extra dejo estos dos plug-in para que los prueben:
- *LanguageTool Integration*, que no es más que un corrector ortográfico
- *Natural Language Dates*, con el que podemos indicar las fechas de otra manera, pero siempre en inglés (tomorrow, this week, 5 days ago...)

Si te ha parecido interesante la estructura que he montado para un Bullet Journal, te animo a que intentes ponerlo en práctica. 