---
layout: uprazhneniya-category
title: Программы Блокчейна и Криптовалют - самые Важные (сегодня)
permalink: /uprazhneniya/
---



<div class="posts">
{% for post in site.categories.Uprazhneniya %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Читать дальше</a>
    </article>
  {% endfor %}
</div>

