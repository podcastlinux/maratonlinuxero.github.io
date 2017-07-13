---
layout: page
title: Podcast del Maratón Linuxero
permalink: /podcast/
---

¿Te perdiste el directo? ¡No pasa nada! Recogeremos todos los momentos y los pondremos a disposición de la comunidad en forma de podcast.
El feed está creado desde GitHub: <http://maratonlinuxero.github.io/feed.xml>

**Episodios:**

  <div class="posts">
  {% for post in site.categories.Podcast %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      <h5><div class="post-meta">{{ post.date | date: "%d/%m/%Y" }}</div></h5>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Sigue leyendo...</a>
    </article>
  {% endfor %}
</div>

