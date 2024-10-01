---
layout: default
title: Home
---

# Jessie's GitHub Pages website

Welcome to my GitHub Pages website！🚀

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - 
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

## About

[Learn more about me on the About page](about.html).
![image](https://github.com/user-attachments/assets/cee35a5e-162c-4482-8ebf-b071c4b606ef)
