---
title: Ionic y Vue
description: 'Portfolio Section'
---

### Aplicação para criar lembretes com Foto

[Testar em PlayStore](https://play.google.com/store/apps/details?id=com.pedromanuelcubo)

Aplicação para coletar lembretes com foto.

A tela inicial pide o login (usa plugin do Firebase instalada como capacitor)

{{< figure  src="sample-project/cuatro.jpg" caption="Tela inicial" alt="proyecto ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Quando o login é completado, usando um back-end com laravel nos mostra os lembretes que temos cadastrados até esse momento:

{{< figure src="sample-project/uno.jpg" caption="Teñe principal" alt="projeto ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

A aplicação dispõe de um componente drawer onde temos distintos menus dentro do ion-toolbar:

{{< figure src="sample-project/tres.jpg" caption="menu" alt="projeto ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Quando é selecionado criar lembrete vamos na pagina distinta onde poderemos incluir o comentário com foto:

{{< figure src="sample-project/dos.jpg" caption="Criar Lembrete" alt="projeto ionic" class="animate__animated animate__fadeIn animate__delay-1s" >}}

Quando o comentário é preenchido, apertando o botão Fazer Foto nos abrirá o aplicação da camara usando o plugin capacitor @ionic-native/camera, pudendo completar o lembrete:

{{< figure src="sample-project/cinco.jpg" caption="Completar lembrete" alt="projeto ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}

Depois, nos mostrará o conjunto do lembretes disponíveis em ion-cards:

{{< figure src="sample-project/uno.jpg" caption="Completar lembrete" alt="projeto ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}

Estos ion-cards são componentes clickables abriéndo-nos o madal onde podemos ver a foto expandida e onde podemos borrar o lembrete tambén.


{{< figure src="sample-project/seis.jpg" caption="Modal" alt="projeto ionic" class="animate__animated animate__fadeIn animate__delay-1s"  >}}