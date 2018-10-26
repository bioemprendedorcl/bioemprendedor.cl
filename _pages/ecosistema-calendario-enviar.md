---
title: "Envía tus eventos y actividades"
permalink: /ecosistema/calendario/enviar
layout: single
author_profile: true
excerpt: "Compartenos los datos de tu evento o actividad para que la agreguemos a nuestro calendario."
header:
  overlay_image: https://res.cloudinary.com/bioemp/image/upload/c_limit,f_auto,q_auto,w_1200/b2/calendario.jpg
  overlay_filter: 0.5
  caption: "Foto: [rawpixel](https://unsplash.com/photos/ZMMXSRMSoI8) @ Unsplash"
sidebar:
  nav: "ecosistema"
---

Si conoces u organizas un evento que pueda ser útil para los Bioemprendedores envianos los datos y lo agregaremos a nuestra sección de eventos y actividades lo antes posible. Para esto usa el siguiente formulario:

<form name="calendario" action="/contacto/enviado" method="POST" data-netlify="true" netlify-honeypot="_gotcha">
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
    <input class="button" type="submit" value="Enviar mensaje" />
  </fieldset>
</form>