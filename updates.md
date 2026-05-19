---
title: Updates
permalink: /updates/
eyebrow: Project
lede: Notes and updates from the Govnr project.
---

{% if site.posts.size > 0 %}
  {% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p>{{ post.date | date: "%-d %B %Y" }}</p>
    {% if post.lede %}
      <p>{{ post.lede }}</p>
    {% endif %}
  </article>
  {% endfor %}
{% else %}
No updates have been published yet.
{% endif %}

