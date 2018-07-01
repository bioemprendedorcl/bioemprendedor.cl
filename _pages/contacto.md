---
title: "Contáctanos"
permalink: /contacto/
layout: single
classes: wide
author_profile: true
excerpt: "¡Siempre estamos disponibles para conversar!"
header:
  overlay_image: https://bioemprendedor.cl/static/contacto-bHgDJd.jpg
  overlay_filter: 0.5
  caption: "Foto: [Thought Catalog](https://unsplash.com/photos/UK78i6vK3sc) @ Unsplash"
---

Para que nos pongamos en contacto te proponemos 2 alternativas, redes sociales y el clásico formulario de contacto vía correo electrónico. ¡Cualquier sirve!

Lo único que te pedimos es que no uses estos medios como vía de SPAM. ¡Los simples mortales lo odiamos!

[<i class="fab fa-twitter"></i> Twitter](https://twitter.com/bioemprendedorcl){: .btn .btn--primary .btn--twitter .btn--x-large} [<i class="fas fa-envelope"></i> Formulario de contacto](https://diegoscl.typeform.com/to/IbXplr){: .btn .btn--primary .btn--success .btn--x-large}

<form name="contacto" action="" method="POST" data-netlify="true" netlify-honeypot="_gotcha">
  <fieldset>
    Nombre: * <input class="input" id="name" type="text" name="name" value="" placeholder="¿Cual es tu nombre?" required="required" />
    Email: * <input class="input" id="_replyto" type="email" name="_replyto" value="" placeholder="hola@belmar.ws" required="required" />
    Mensaje: * <textarea class="textarea" id="message" name="message" placeholder="¿Que me quieres decir?" required="required"></textarea>
    <p>
      <div data-netlify-recaptcha></div>
    </p>
    <input class="button" type="submit" value="Enviar mensaje" />
    <br/>
    <small class="small">Todos los campos son requeridos.</small>

    <input type="text" name="_gotcha" style="display:none">
    <input type="hidden" name="_subject" value="Nuevo mensaje desde el blog">
    <input type="hidden" name="_next" value="/thanks/" />
  </fieldset>
</form>
