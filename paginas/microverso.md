---
layout: page
title: microverso
permalink: /microverso/
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post neu">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Leer más</a>
    </article>
  {% endfor %}
</div>