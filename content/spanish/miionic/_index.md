---
title: Ionic y Vue
description: 'Portfolio Section'
---

### Aplicación para crear Recordatorios con Foto

[Probar en PlayStore](https://play.google.com/store/apps/details?id=com.pedromanuelcubo)

Aplicación para coleccionar recordatorios con su foto.

La pantalla inicial solicita el login (utiliza plugin de Firebase instalada con capacitor):

{{< figure  src="sample-project/cuatro.jpg" caption="Pantalla inicial" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Una vez completado el login, utilizando un back-end en laravel nos muestra los recordatorios que tenemos registrados hasta ese momento:

{{< figure src="sample-project/uno.jpg" caption="Pantalla principal" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

La aplicación dispone de un componente drawer donde disponemos distintos menús integrados dentro de ion-toolbar:

{{< figure src="sample-project/tres.jpg" caption="menu" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Cuando se selecciona crear recordatorio iremos a una página distinta donde podremos incluir un comentario y una foto:

{{< figure src="sample-project/dos.jpg" caption="Crear Post" alt="proyecto java" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Una vez relleno el comentario, al pulsar sobre Hacer Foto nos abrirá la aplicación de la cámara utilizando el plugin de capacitor @ionic-native/camera. Tras realizar la foto podemos entonces completar el post:

{{< figure src="sample-project/cinco.jpg" caption="Completar post" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}

Una vez completado nos muestra el conjunto de posts disponibles en ion-cards:

{{< figure src="sample-project/uno.jpg" caption="Completar recordatorio" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}

Estos ion-cards son componentes clickables abriéndonos un modal donde podemos ver la foto ampliada y donde podemos también borrar el recordatorio.

{{< figure src="sample-project/seis.jpg" caption="Modal" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}