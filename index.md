---
layout: post
title: WolverineOfTheMarkets
---

# Добро пожаловать на WolverineOfTheMarkets!

Здесь будут ссылки на ваши свежие аналитические посты:

<ul>
{% for post in site.posts %}
  <li>
    <time>{{ post.date | date: "%-d %B %Y" }}</time> —
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
