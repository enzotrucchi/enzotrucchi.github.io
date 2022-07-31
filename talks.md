---
layout: default
---

<div class="posts">
  {% for talk in site.categories.talk %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ talk.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ talk.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>