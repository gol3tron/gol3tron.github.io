---
layout: page
title: "Home"
---

## Welcome

Hello! Welcome to my online [resume/CV](https://gol3tron.github.io/cv), blog and portfolio! Thanks for visiting!

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
