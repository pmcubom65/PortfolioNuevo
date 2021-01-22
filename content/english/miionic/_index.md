---
title: Ionic and Vue
description: 'Portfolio Section'
---

### Application for collecting reminders with a picture

[Test on PlayStore](https://play.google.com/store/apps/details?id=com.pedromanuelcubo)

Application for collecting reminders with its picture.

The first screen requires login (using Firebase plugin installed with capacitor):

{{< figure  src="sample-project/cuatro.jpg" caption="Login" alt="ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Once login is completed, using laravel back-end, a list of user's registered reminders, up to that moment, is shown:

{{< figure src="sample-project/uno.jpg" caption="Main screen" alt="ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

This application has a drawer component where menu is collapsed within ion-toolbar:

{{< figure src="sample-project/tres.jpg" caption="menu" alt="ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

When "create reminder" is selected, the user will be redirected to another page where he'll be required to write a comment with a picture.


{{< figure src="sample-project/dos.jpg" caption="Create reminder" alt="ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Once a comment is written, user can tap "make photo" button where camera application will be opened due to @ionic-native/camera capacitor plugin. After taking a picture, a new remider can be completed:

{{< figure src="sample-project/cinco.jpg" caption="Reminder completed" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}

After that, the main screen will reappear and show all user's available reminders in ion-cards:

{{< figure src="sample-project/uno.jpg" caption="Reminder Completed" alt="ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}

These ion-cards are clickable components popping up a new window with the remainder details adjoined to a delete botton to delete it. 

{{< figure src="sample-project/seis.jpg" caption="Modal" alt="ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}
