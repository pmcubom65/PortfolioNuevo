---
title: Firebase y Angular
description: 'Portfolio Section'
---

### Aplicação web para comprar ingressos, cadastro de usuário e pagamento com o Paypal

[Testar aplicação](https://pedro-manuel-cubo-medina.web.app)

Aplicação web para comprar ingressos: 

Em a tela inicial se mostra um listado de eventos disponíveis ordenados por data. Estos eventos tem sido generados com dados aleátorios, armazenados em firebase. Angular deixa mostrar-os com RxJS.


{{< figure src="sample-project/Captura1.PNG" caption="Tela inicial" alt="angular" class="animate__animated animate__fadeIn animate__delay-1s">}}

Cada evento tem 2 botões. O primeiro adiciona um item em a cesta da compra. O segundo, nos mostra os detalhes do evento e deixá-nos comprar o numero do ingressos que queramos

{{< figure src="sample-project/Captura2.PNG" caption="detalhes do evento" alt="detalhes do evento"  class="animate__animated animate__fadeIn animate__delay-1s">}}

Tanto o menu top como os detalhes o evento, o usuário pode acesar o lugar do evento.

{{< figure src="sample-project/captura3.PNG" caption="lugar do evento" alt="lugar do evento"  class="animate__animated animate__fadeIn animate__delay-1s" >}}

Quando compramos um evento, esse evento é adicionado na cesta da compra. Se usa NGRX para que os dados estem compratilhados com todos os componentes:


{{< figure src="sample-project/Captura7.PNG" caption="Cesta da compra" alt="projeto angular"  class="animate__animated animate__fadeIn animate__delay-1s">}}

Quando confirma-se a compre, se acessa no detalhe da compra:

{{< figure src="sample-project/Captura5.PNG" caption="Cesta da la Compra" alt="projeto"  class="animate__animated animate__fadeIn animate__delay-1s" >}}

Para compretar o pago, o usuário tem que cadastrar no aplicação, pode-se usar redes sociais o credenciais do aplicação:
{{< figure src="sample-project/captura4.PNG" caption="Cadastro" alt="projeto angular"  class="animate__animated animate__fadeIn animate__delay-1s" >}}

Finalmente, pode-se completado o pago com o Paypal:

{{< figure src="sample-project/Captura6.PNG" caption="Pagamento com Paypal" alt="projeto angular"  class="animate__animated animate__fadeIn animate__delay-1s">}}



[Codigo](https://www.dropbox.com/s/q0xvxol7ae7hx7a/fiestasenmurcia-master.zip?dl=0)
