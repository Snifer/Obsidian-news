---
title: "Diario Intersticial"
tags: QuickADD Templater  
categories: BulletJournal
comments: true
author: Marilyn
---

# Diario Intersticial

Este período pandémico me ha llevado a buscar estrategias para optimizar mi forma de trabajar, ordenar mis pensamientos y la realización de tareas cotidianas pues el trabajo en casa es propicio para distraernos y procrastinar. En esa búsqueda de estrategias para el mejoramiento de la realización de las actividades cotidianas y de gestión del conocimiento me encontré con maravillosos grupos en Telegram como el de Zettelkasten, Gestión del Conocimiento Personal y Obsidian Español, empecé a implementar el Método Zettelkasten en Obsidian y me encontré con esta poderosa herramienta en la que puedo gestionar también mis tareas, organizar mi día y tomar notas (que es su esencia).

En medio de tanta actividad encontré que las distracciones no me permitían avanzar en todas las actividades planeadas, así que empecé a implementar estrategias de Gestión del Tiempo y entre ellas está el Bloqueo de Tiempo con la herramienta Pomodoro (Dividir el día en períodos de tiempo para realizar mis actividades combinado con tiempo programado de pausa) y todo iba muy bien, períodos de trabajo "profundo" realmente productivos, pero entre un período de trabajo "profundo" y otro resulta difícil volver a enfocarse en la nueva tarea. Y es precisamente allí donde encontré la utilidad del **Diario Intersticial** que consiste en llevar un registro de tus actividades y añadir entradas de lo que vas pensando entre una actividad y otra, es una combinación de registro de tareas, seguimiento de tiempo y un ejercicio de conciencia plena en la actividad que ejecutas, con el objetivo de enfocarte en la nueva tarea.

De esta manera que les comparto como ejecuto este diario en mi espacio de trabajo en Obsidian.

- A diario utilizo el plugin de Notas diarias en el cual tengo ya formateada las actividades del día ( esto se puede configurar como mejor nos funcione, en mi caso tengo una plantilla con: tres prioridades, mi día perfecto, cita diaria aleatoria y al final del día tres gratitudes y que puedo mejorar) Este ejercicio me permite tener la planeación del día y el balance del mismo y honestamente en cuarentena diferenciar un día de otro.  En esta misma nota diaria al final de lo que ya está prediseñado en la plantilla escribo las entradas del diario intersticial.

Para esto necesité a @Snifer y los plugins:
- Templater
- QuickADD

  

 ##  Configuración de QuickADD:

En la opción de configuración de QuickADD. 

1. Registrar el nombre que se le va a asignar (DI: Diario Intersticial) o un emoji. 
2. Capture 
3. Add Choice

**Luego:**

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/InitialConfigure.png)

1. Rueda de settings. 
2. Marcar Capture to Active File. 
3. Registrar el siguiente código, marcando Capture Format. 

```
<% tp.date.now() %> <% tp.date.now("HH:mm") %>
```

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/QuickADDCapture.png)

**Debe quedar del siguiente modo:**


![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/ConfigureQuickADDTemplater.png)

Finalmente para terminar la configuración en QuickADD.

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/ConfigureShortCut.png)

Marcar el Rayo con el QuickADD que se acaba de configurar.


#### Automatización del proceso.

Ya configurado el QuickADD para poder realizar las entradas con la fecha y hora automáticamente, vamos a configurar el Atajo (Hotkey).

1. Vamos a Atajos o Hotkeys (depende la configuración de idioma) en la configuración de Obsidian.
2. Buscar el nombre de tu QuickADD en este ejemplo 📓

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/boletin4/ConfigureHotKeys.png)

2. Marcar ese icono o nombre asignado, se pondrá de color Azul. 
3. El atajo/hotkey tecla rápida que desee configurar. Por ejemplo: Ctrl + t 

¡ Y listo!

Ya podemos llevar nuestro diario intersticial.

Recuerda,  `Ctrl + T` ( Día y hora) y la entrada con tus pensamientos, la idea es escribir lo que tienes "dándote vuelta" en la cabeza para volver a la tarea que estabas ejecutando.


Espero te sea de utilidad esta guía y puedas empezar la práctica de llevar un Diario Intersticial.