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

Para que nos pongamos en contacto te proponemos 2 alternativas: redes sociales y el clásico formulario de contacto vía correo electrónico. ¡Cualquier sirve!

Lo único que te pedimos es que no uses estos medios como vía de SPAM. ¡Los simples mortales lo odiamos!

<h2>Escríbenos en redes sociales</h2>
[<i class="fab fa-twitter"></i> Envíanos un DM en Twitter](https://twitter.com/messages/compose?recipient_id=1009086166140968960){: .btn .btn--primary .btn--twitter .btn--x-large}

<h2>Escríbenos un correo electrónico</h2>
Te aseguramos que leemos todos los correos por lo que intentaremos contestar lo antes posible, pero recuerda que no somos robots <i class="fas fa-robot"></i> que están todo el día tecleando así que ten paciencia (Todos los campos son requeridos).

<form name="contacto" action="" method="POST" data-netlify="true" netlify-honeypot="_gotcha">
  <fieldset>
    <i class="fas fa-fw fa-user-ninja"></i> Tu nombre y apellido: <input class="input" id="name" type="text" name="name" value="" required="required" />
    <i class="fas fa-fw fa-at"></i> Tu correo electrónico: <input class="input" id="_replyto" type="email" name="_replyto" value="" required="required" />
    <i class="fas fa-fw fa-pencil-alt"></i> Tu mensaje:<textarea class="textarea" rows="4" id="message" name="message" required="required"></textarea>
    <p>
      <div data-netlify-recaptcha></div>
    </p>
    <br/>
    <input type="text" name="_gotcha" style="display:none">
    <input type="hidden" name="_subject" value="Nuevo mensaje desde el blog">
    <input type="hidden" name="_next" value="https://bioemprendedor.cl/contacto/enviado" />
    <input class="button" type="submit" value="Enviar mensaje" />
  </fieldset>
</form>
