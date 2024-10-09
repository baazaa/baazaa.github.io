---
layout: index
title: Home
---

Twitter: [@baazaa9](https://x.com/baazaa9)


Latest Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>
