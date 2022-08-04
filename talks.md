---
layout: default
---

<div class="posts">
  {% for talk in site.categories.talk %}
    <article class="post">
      <a href="{{ site.baseurl }}{{ talk.url }}">
        <h1>{{ talk.title }}</h1>

        <p style="color:black;">
          {{ talk.description }}
        </p>

        <p>Leer más</p>
      </a>
    </article>
  {% endfor %}
</div>