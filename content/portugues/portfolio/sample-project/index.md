---
title: Vêr mais detalhes
description: descripcion
work: []
techs: []
designs: []
thumbnail: sample-project/inicio2.jpg
projectUrl: https://www.sampleorganization.org

---
[Testar em PlayStore](https://play.google.com/store/apps/details?id=com.pedromanuel.juegopedromanuelcubomedina)

O jogo consta de 2 jogos. Começa com o menú inicial composto de 2 fragmentos onde podemos escolher o jogo e a dificuldade:

{{< figure class="miimagen" src="menuinicial.jpg" caption="Menú inicial" alt="pantallas do jogo"  
  >}}

O primeiro jogo consiste em esquivar as bolas vermelhas e pegar todas as outras para ter o score mais alto possible. Sim não se pega a figura menino a velocidade das bolas serão maior.

{{< figure class="miimagen" src="inicio.jpg" caption="Jogo 1"  
 alt="telas do jogo"  
  >}}

O segundo jogo consiste em pegar gotas de chuva com o objetivo de evitar se afogar, cada gota de chuva aumenta o score em 1. Sim não se pega uma gota se perde uma vida e o nivel da agua aumenta.


{{< figure class="miimagen"  src="inicio2.jpg" 
 alt="telas do jogo"   caption="Jogo 2"   >}}

Quando todas as vidas são perdidas, aparece um resumo do jogo onde podemos jogar de novo o ir para as estatisticas.

{{< figure class="miimagen"  src="resumen.jpg" 
 alt="telas do jogo"   caption="Resumo"   >}}

Nas estatisticas mostram os dados de cada jogo armazenados no archivo sqlite:
{{< figure class="miimagen"  src="estadisticas.jpg" 
  alt="telas do jogo"   caption="estatisticas"   >}}

No menú overflow tem opciões para ordenar as estatisticas por score, tempo o data e borrar registros o editar:
{{< figure class="miimagen"  src="orden.jpg" 
   alt="telas do jogo"   caption="estatisticas"   >}}

Essa pantalla dispõe do menú que nos permite mudar o jogo o ir a opção da mapas:

{{< figure class="miimagen"  src="drawer.jpg" 
 alt="telas do jogo"   caption="estatisticas"   >}}

A mudança do jogo cria um dialogo do opciões:
 {{< figure class="miimagen"  src="elija.jpg" 
 alt="telas do jogo" caption="Dialogo"   >}}

A opção do scores começa com um dialogo onde pergunta sim queremos manter no ultimo score em googlemaps o vêr os ultimos scores armazenados:

 {{< figure class="miimagen"  src="marcador.jpg" 
 alt="telas do jogo"   caption="Dialogo"   >}}

Sim é armazenado, na mapa com o marcador armazenado vai aparecer (o objeto latlng na base de dados sqlite):

 {{< figure class="miimagen"  src="barajas.jpg" 
 alt="telas do jogo"   caption="Mapa"   >}}

A verificação os scores armazenados, mostrarão todos os scores que vamos ter na base de dados:

  {{< figure class="miimagen"  src="elmapa.jpg" 
alt="telas do jogo"  caption="Mapa"   >}}

Quando jogamos, a aplicação cria uma notifação que nos permita voltar o jogo

  {{< figure class="miimagen"  src="notify2.jpg" 
 alt="telas do jogo"   caption="notifação"   >}}


[Codigo](https://www.dropbox.com/s/gtfygi2p700l9dl/AndroidGameBolitas-master.rar?dl=0)


