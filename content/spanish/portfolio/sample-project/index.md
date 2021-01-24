---
title: Ver más detalles
description: descripcion
work: []
techs: []
designs: []
thumbnail: sample-project/inicio2.jpg
projectUrl: https://www.sampleorganization.org

---

[Probar en PlayStore](https://play.google.com/store/apps/details?id=com.pedromanuel.juegopedromanuelcubomedina)

El videojuego consta de 2 minijuegos. Comienza con un menú inicial compuesto de dos fragmentos donde podemos elegir el juego y la dificultad:

{{< figure class="miimagen" src="menuinicial.jpg" caption="Menú inicial" alt="pantallas del juego"  
  >}}

El primer minijuego consiste en esquivar las bolas rojas y recojer todas las demás con el objetivo de tener el score más alto posible. Si no se captura la figura niño la velocidad de las bolas será cada vez mayor.

{{< figure class="miimagen" src="inicio.jpg" caption="Juego 1"  
 alt="pantallas del juego"  
  >}}

El segundo minijuego consiste en recoger gotas de lluvia con el objetivo de evitar ahogarse, cada gota de lluvia aumenta el score en 1. Si no se recoge una gota se pierde una vida y el nivel del agua aumenta.


{{< figure class="miimagen"  src="inicio2.jpg" 
 alt="pantallas del juego"   caption="Juego 2"   >}}

Una vez perdidas todas las vidas nos aparece un resumen del juego donde podemos jugar de nuevo o ir a las estadísticas
{{< figure class="miimagen"  src="resumen.jpg" 
 alt="pantallas del juego"   caption="Resumen"   >}}

En las estadísticas se muestran los datos de cada partida almacenados en un archivo de sqlite:
{{< figure class="miimagen"  src="estadisticas.jpg" 
 alt="pantallas del juego"   caption="Estadisticas"   >}}

En el menú overflow aparencen opciones para ordenar las estadísticas por score, tiempo o fecha así como borrar registros o editar:
{{< figure class="miimagen"  src="orden.jpg" 
 alt="pantallas del juego"   caption="Estadisticas"   >}}

Esa pantalla dispone de un menú que nos permite por ejemplo cambiar de juego o ir a la opción de mapas:

{{< figure class="miimagen"  src="drawer.jpg" 
 alt="pantallas del juego"   caption="Estadisticas"   >}}

 El cambio de juego despliega un diálogo de opciones:
 {{< figure class="miimagen"  src="elija.jpg" 
 alt="pantallas del juego"   caption="Dialogo"   >}}


La opción de marcadores comienza con un diálogo donde nos pregunta si queremos guardar el último marcador en googlemaps o ver los marcadores almacenados:
 {{< figure class="miimagen"  src="marcador.jpg" 
 alt="pantallas del juego"   caption="Dialogo Marcadores"   >}}

 Si lo almacenamos, aparecerá el mapa con el marcador almacenado (se guarda un objeto latlng en la base de datos sqlite):
 {{< figure class="miimagen"  src="barajas.jpg" 
 alt="pantallas del juego"   caption="Mapa"   >}}

 Al consultar los marcadores almacenados, mostrará todos los marcadores que tengamos en la base de datos:
  {{< figure class="miimagen"  src="elmapa.jpg" 
 alt="pantallas del juego"   caption="Mapa"   >}}

 Cada vez que juguemos, la aplicación genera una notificación que nos permite volver a jugar:

  {{< figure class="miimagen"  src="notify2.jpg" 
 alt="pantallas del juego"   caption="Notificación"   >}}





