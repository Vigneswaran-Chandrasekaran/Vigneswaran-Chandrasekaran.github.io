---
layout: default
title: Posts
permalink: /about/
---

<div class="posts">
  {% for post in site.posts reversed%}
    <article class="post">

      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>

      <div class="entry">
      </div>
    </article>
  {% endfor %}
</div>
