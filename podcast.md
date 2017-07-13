---
layout: page
title: Podcast del Maratón Linuxero
permalink: /podcast/
---

¿Te perdiste el directo? ¡No pasa nada! Recogeremos todos los momentos y los pondremos a disposición de la comunidad en forma de podcast.
El feed está creado desde GitHub: <http://maratonlinuxero.github.io/feed.xml>

{% for post in site.categories.podcast %}
 + [{{ post.title }}]({{ page.url }})
{% endfor %}
