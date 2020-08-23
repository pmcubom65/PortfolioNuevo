---
title: Firebase y Angular
description: 'Portfolio Section'
---

### Aplicación web de compra de entradas, registro del usuario y pago por Paypal

[Probar la aplicación](https://pedro-manuel-cubo-medina.web.app)


Aplicación web de compra de entradas para contratar eventos: 

En la pantalla inicial se presenta un listado de los eventos disponibles ordenados por fecha. Estos eventos han sido generados con datos aleatorios, almacenados en firebase. Angular nos permite mostrarlos mediante RxJS.

{{< figure src="sample-project/Captura1.PNG" caption="Pantalla principal" alt="proyecto angular" >}}

Cada evento tiene 2 botones. El primero comprar nos añade el articulo en la cesta de la compra. El segundo detalles nos muestra los detalles del evento y nos permite comprar el número de entradas que queramos.

{{< figure src="sample-project/Captura2.PNG" caption="Detalles del evento" alt="proyecto angular" >}}

Tanto en el menú superior como en los detalles del evento, podemos acceder a los detalles del lugar del evento.

{{< figure src="sample-project/captura3.PNG" caption="Pantalla detalle lugar del evento" alt="proyecto angular" >}}

Cada vez que compramos un evento, se añade a la cesta de la compra. Se utiliza NGRX para que los datos estén compartidos por todos los componentes:

{{< figure src="sample-project/Captura7.PNG" caption="Cesta de la compra" alt="proyecto angular" >}}

Al seleccionar confirmar compra, accedemos al detalle de la compra:

{{< figure src="sample-project/Captura5.PNG" caption="Cesta de la Compra" alt="proyecto angular" >}}

Para efectuar el pago, hay que registrase en la aplicación, se puede utilizar redes sociales o credenciales de la aplicación:
{{< figure src="sample-project/captura4.PNG" caption="Registro" alt="proyecto angular" >}}

Finalmente, podemos completar el pago por Paypal:

{{< figure src="sample-project/Captura6.PNG" caption="Pago por Paypal" alt="proyecto angular" >}}



[Código sin claves](https://github.com/pmcubom65/fiestasenmurcia.git)