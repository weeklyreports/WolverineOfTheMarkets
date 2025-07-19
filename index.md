---
layout: default
title: WolverineOfTheMarkets
permalink: /
---

# Добро пожаловать!

Список всех публикаций:

<ul class="list-disc ml-6">
{% for post in site.posts %}
  <li class="mb-1">
    <time class="text-gray-400">{{ post.date | date: "%-d %B %Y" }}</time>
    — <a href="{{ post.url }}" class="text-blue-400 hover:underline">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
