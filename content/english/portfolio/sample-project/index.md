---
title: More details
description: descripcion
work: []
techs: []
designs: []
thumbnail: sample-project/inicio2.jpg
projectUrl: https://www.sampleorganization.org

---
[Test on PlayStore](https://play.google.com/store/apps/details?id=com.pedromanuel.juegopedromanuelcubomedina)

This game consists of 2 different games. The initial menu is compounded of 2 fragments where can be selected the type of game and level of dificulty:


{{< figure class="miimagen" src="menuinicial.jpg" caption="Initial menu" alt="android"  
  >}}

In the first game, the player has to avoid the red balls and pick the rest balls so that the highest score can be made out. If the kid figure is not caught, balls will speed up.

{{< figure class="miimagen" src="inicio.jpg" caption="Game 1"  
 alt="android"  
  >}}

In the second game, the player has to get all drops to avoid drowning, every drop raises the score in 1. If a drop is not gotten, a life is lost and the water level grows.


{{< figure class="miimagen"  src="inicio2.jpg" 
 alt="Game screens"   caption="Game screens"   >}}

Once 3 lifes have been lost, an outline of the score is shown where we can play again or go to statistics.

{{< figure class="miimagen"  src="resumen.jpg" 
 alt="Outline"   caption="Outline"   >}}

In statistics, data of each game are shown from sqlite file:
{{< figure class="miimagen"  src="estadisticas.jpg" 
 alt="Statistics"   caption="Statistics"   >}}

In the overflow menu, there are options to sort statistics by score, time or date as well as records removal or edition: 

{{< figure class="miimagen"  src="orden.jpg" 
 alt="Statistics"   caption="Statistics"   >}}

That screen displays a menu to let the player change game or go to maps option:


{{< figure class="miimagen"  src="drawer.jpg" 
 alt="Statistics"   caption="Statistics"   >}}

The game change unfolds an option dialog:

 {{< figure class="miimagen"  src="elija.jpg" 
 alt="Dialog"   caption="Dialog"   >}}

The option score begins with a dialog asking for saving the last score in googlemaps or watching stored scores:
 {{< figure class="miimagen"  src="marcador.jpg" 
 alt="Score dialog"   caption="Score dialog"   >}}

If the last score is stored, a map with the new mark will pop up (a latlng object is stored in sqlite DB):
 {{< figure class="miimagen"  src="barajas.jpg" 
 alt="Map"   caption="Map"   >}}

Checking stored scores will show all marked scores up to that moment:

  {{< figure class="miimagen"  src="elmapa.jpg" 
 alt="Map"   caption="Map"   >}}

Every time a new game is ended, the game will create a new notification where the player can opt out to play again:


  {{< figure class="miimagen"  src="notify2.jpg" 
 alt="Notification"   caption="Notification"   >}}


[Code](https://www.dropbox.com/s/gtfygi2p700l9dl/AndroidGameBolitas-master.rar?dl=0)


