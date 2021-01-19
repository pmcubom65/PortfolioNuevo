---
title: Firebase and Angular
description: 'Portfolio Section'
---

### Web application for tickets purchasing, user registration and Paypal payment

[Test this application](https://pedro-manuel-cubo-medina.web.app)

Web application for tickets purchasing:

In the initial screen, a list of events, sorted by date, is shown. These events have been generated using ramdom data, stored in firebase. Angular allow us to display them using RxJS.


{{< figure src="sample-project/Captura1.PNG" caption="Initial Screen" alt="angular" class="animate__animated animate__fadeIn animate__delay-1s">}}

Each event has 2 buttons. The first one is for adding an event to our purchasing cart, the second one will display details of that event adjoined to an spinner where any number of tickets can be set.

{{< figure src="sample-project/Captura2.PNG" caption="Event details" alt="angular"  class="animate__animated animate__fadeIn animate__delay-1s">}}

Event location is accessible in the top menu as well as in details event.

{{< figure src="sample-project/captura3.PNG" caption="Location event" alt="angular"  class="animate__animated animate__fadeIn animate__delay-1s" >}}

Anytime an event is purchased, the shopping cart displays a new item added. Due to NGRX, that data is shared among all web components:

{{< figure src="sample-project/Captura7.PNG" caption="Purchasing cart" alt="angular"  class="animate__animated animate__fadeIn animate__delay-1s">}}

When the purchase is confirmed, purchase details is displayed:

{{< figure src="sample-project/Captura5.PNG" caption="Purchasing cart" alt="angular"  class="animate__animated animate__fadeIn animate__delay-1s" >}}

For making final payment, this application web will require previous registration. That registration can be done through social networks credentials or application credentials:  

{{< figure src="sample-project/captura4.PNG" caption="Registration" alt="angular"  class="animate__animated animate__fadeIn animate__delay-1s" >}}

Finally, payment via paypal can be completed:

{{< figure src="sample-project/Captura6.PNG" caption="Payment" alt="angular"  class="animate__animated animate__fadeIn animate__delay-1s">}}



[Code no keys](https://www.dropbox.com/s/q0xvxol7ae7hx7a/fiestasenmurcia-master.zip?dl=0)
