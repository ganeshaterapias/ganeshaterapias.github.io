---
layout: page
title: "Contactanos"
show_meta: false
header:
   image_fullwidth: "ganesha-header-1.jpg"
teaser: "Dejanos un mensaje usando el formulario."
permalink: "/contactanos/"
---

<form action="https://getsimpleform.com/messages?form_api_token=9d6093f2d1ba9bda0e09c378060d3172" method="post">
  <input type="hidden" name="redirect_to" value="{{ site.url }}" />
  <input type="text" name="name" placeholder="Nombre..." />
  <input type="text" name="email" placeholder="Email..." />
  <textarea rows="4" name="message" maxLength="1000" placeholder="Escriba su mensaje..."></textarea>
  <input type="submit" value="Enviar" />
</form>

