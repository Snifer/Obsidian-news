---
title: "Sincronizar Obsidian con Drive y Android y no morir en el intento"
tags: Sync GoogleDrive Windows Linux Mac  
categories: Sync
comments: true
author: DoctorCancel
---


# Sincronizar Obsidian con Drive y Android  ...y no morir en el intento por DoctorCancel

## Crear la cuenta de Gmail y descargar Drive
- Creamos una cuenta de correo de Gmail (si no tenemos una ya, aunque es recomendable una nueva). 

- El procseo de instalación, configuración y sincronización entre Drive de escritorio y la nube, **es el mismo para MacOS y Windows.**

- Descargamos Google Drive para ordenador en la siguente dirección:

	>https://www.google.com/intl/es_es/drive/download/
	
## Instalar y ejecutar
-Instalamos la aplicación (sin mayor complicación). Sobra decir que para llevar a cabo la configuración, hay que estar conectado a Internet.

- Una vez descargado, accedemos a la aplicación  desde el menú de iconos ocultos (junto al reloj)

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura1.png)

- Lo abrimos. Por defecto no debe aparecer ninguna cuenta asociada

- Para configurar nuestra cuenta, clicamos sobre el engranaje dentado, y seleccionamos la opción "preferencias".



![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura2.png)

- Nos abrirá el panel principal de Drive

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura3.png)


## Sincronizar desde Windows / Mac
- Ahora clicaremos soble el icono de la cuenta de Gmail, justo arriba a la derecha. 


Si no tuvieramos ninguna cuenta asociada, pulsariamos sobre "añadir otra cuenta". Este proceso es exactamente igual a cuando añadimos una nueva cuenta a la lista de para acceder a los servicios de Drive.

- Este paso nos redireccionará a la página de Drive para seleccionar la cuenta que queremos usar.

- En el momento que hayamos creado la nueva cuenta en la aplicaión, Drive nos creará una nueva unidad de disco duro del mismo tamaño que la  de Drive (15GB). Podemos cambiar su configuración en la rueda dentada junto al icono.

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura4.png)
- De esta manera, ahora sólo hay que arrastra la carpeta vault de obsidian dentro de la nueva unidad que se ha creado con el nombre de la cuenta de correo, y esperar que todos los archivos del vault se sincronicen con Drive. La primera vez, lleva su tiempo en función del tamaño de la vault. 

- Así, a partir de ahora, se trabajará directamente sobre el vault que se encuentra en la unidad virtual que Drive ha creado. Para ello, habrá que cambiar la configuración de Obsidian, para que trabaje sobre esta nueva vault

- Se pueden añadir más de una carpeta/vault a la cuenta (para poder tener varias vault en una sola cuenta/unidad de disco, o crear una cuenta/unidad de disco por vault). Esta carpeta se sincroniza con la de Drive en la nube en tiempo real y en segundo plano, sin necesidad de hacer nada.

- Es consejable realizar copias de seguridad periodicas en el ordenador (sobre todo la primera vez). Si se van a hacer en archivo comprimido, tener en cuanta que a veces genera conflicto el nombre de las notas (si tiene paréntesis, acentos, o algunos simbolos). He detectado este problema con el compresor por defecto de Windows (que novedad...), sin embargo, usando 7zip no genera ningún problema al respecto. En principio no debe haber problemas, pero por mi parte, ninguna precaución es poca.

## Sincronizar desde Android
- Existe varios programas en la Play Store para sincronizar carpetas. 
En este caso, usaremos **Autosync for Google Drive**

>https://play.google.com/store/apps/details?id=com.ttxapps.drivesync&hl=es&gl=US


![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura5.png)

- Con la cuenta gratuita se puede sincronizar una carpeta/cuenta de correo (y todo lo que haya en su interior). Lo que significa que se pueden tener varias vault dentro de la misma cuenta / directorio de Dirve
 Si se quiere usar más de una cuenta de Gmail, hay que pasar por caja.
- Descargamos e instalamos la App sin más.
- Antes de configurar la sincronización, debemos crear la carpeta que contendrá la Vault en el dispositivo. Dicha carpeta es la que se sincronizará. Este paso se puede llevar a cabo indistinamente de si ya tenemos instalado Obsidian en el dispositivo.

- Ejecutamos la aplicación DriveSync Ultimate. 
- La aplicación consta de tres pantallas. 
	- **ESTADO**:
	
![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura6.png)
	
Es la pantalla que nos va a mostrar la informacion de los procesos de sincronización ( archivos subidos, bajados, modificados, entre otros).

- **HISTORIAL DE SINCRONIZACIÓN**:
		- Es la pantalla que nos va a mostrar todas las acciones que se han ejecutado (un log).

	- **CARPETAS SINCRONIZADAS:**

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura7.png)

- Esta es, obviamente, la parte más importante, ya que es donde vamos a configurar las sincronizaciones.
	
	Antes de crear el perfil de sincronización, debemos asociar la app a la cuenta de Gmail que usamos para Drive. Para ello, pulsamos en los tres puntos verticales, arriba a la derecha, y seleccionamos "Ajustes".
	
	- Dentro de Ajustes, seleccionamos la primera opción "Cuentas de Google Drive", y "añadir cuenta" en la siguiente ventana. Ahí tendremos la cuenta (o cuentas) de Gmail que tengamos dadas de alta en el dispositivo, para seleccionar. (Es posible que nos pida loguearnos en esa cuenta, para guardar los permisos).
	- Volvemos ahora a la página principal de la aplicación.
	- **Configurar la sincronización**: 
		-Para añadir una sincronización, pulsamos el símbolo "+" de abajo a la derecha.
		Aquí nos encontraremos los siguientes campos a configurar:
		

![](https://raw.githubusercontent.com/Snifer/Obsidian-news/main/imagenes/googleDriveSync/Captura8.png)

- **Nombre de emparejamiento de carpetas**: 
		- Asignamos un nombre para poder identificar esta acción si tenemos más de una cuenta, o perfil de sincronización
	- **Carpeta remota en Google Drive**:  
		- Presionamos el icono, y nos mostrará  el indice Drive. 
		- Si presionamos en la opción "Mis archivos", veremos la carpeta sincronizada desde el ordenador (con el mismo nombre) que está en Drive. 
		- Pulsamos sobre la carpeta. Nos abrirá el contenido de dicha carpeta.  
		- Si pulsamos sobre "Seleccionar" (abajo a la derecha), enlazaremos la carpta completa. Si solo queremos sincronizar una carpeta en concreto, entramos en ella y pulsamos en "Seleccionar". 
		- De esta manera habremos enlazado la app con Drive.
	- **Carpeta local en el dispositivo**: 
		- Pulsamos sobre la opción, y navegamos hasta la carpeta que hemos creado en el dispositivo. 
		- Una vez dentro de dicha carpeta, pulsamos "seleccionar". Ahora ya tendremos sincronizada la carpeta local con la de Drive.
	- **Método de sincronización**:
		-  Aquí podemos configurar como queremos que se realice la sincronización ( si queremos que sea en doble sentido, lo que garantiza que tengamos lo mismo en todos los dispositivos, si sólo queremos subir, sólo bajar, etc...).
	- Puede darse el caso que un archivo se duplique a la hora de sincronizar. Es ese caso, Drive lo guarda con un aviso y la fecha de la sincronización. 
	
	Las siguientes opciones permiten excluir los archivos ocultos (si está activado, no copiará los archivos de configuración de Obsidian, como por ejemplo los estilos...)
	- Luego habilitamos la opción de " Emparejamento de carpeta habilitado."
	- Presionamos "Guardar" en la parte superiro derecha, para guardar la configuración.
	- Si volvemos ahora a la pantalla "Carpetas Sincronizadas", veremos el nuevo perfil de sincronización en la lista. Si tenemos varios perfiles, se irán añadiendo aquí a modo de lista. 
	- En la parte inferior de la tarjeta del perfil de sincronización, debemos habilitar el modo de sincronización que escogimos al crear el perfil. Esto es muy útil cuando tenemos varias cuentas de Gmail, o varios perfiles de sincronización, ya que nos permite escoger que cuentas queremos que se sincronicen en un momento dado. Si deshabilitamos la opción de sincronización del perfil, esta tarea no se ejecutará y esa cuenta no se sincronizará.
	- Si pulsamos ahora sobre el icono de sincronizar (las flechas circulares arriba a la derecha), comenzará el proceso de sincronización. Podemos ver el estado del proceso en la ventana "ESTADO".
	- En ajustes podremos parametrizar más opciones de la sincronización, asi como habilitar la sincronización automática.
	- Ahora, podemos acceder a la nueva vault en el dispositivo, si ya la hemos direccionado desde Obsidina en el dispositivo móvil, con la opción "Open folder as vault".

A partir de este momento, los datos de Obsidian ya estarán sincronizados entre el ordenador de escritorio y el dispositivo móvil. La ventaja es que se podrá acceder a toda la información sin tener conexión a Internet (lo que es una gran ventaja, y suponía un inconveniente en otros programas), ya que se trabaja con la copia en local.  Por otro lado, siempre tendremos una copia en Drive, lo que garantiza que Google tendrá acceso a toda nuestra información, y podrá generar en perfil de nosotros para ofrecerlo, interesadamente, a terceros (aunque ellos digan que no). 

Existen opciones para otros servicios en nube (como Dropbox), pero esa, ya es otra historia.