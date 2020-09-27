---
title: Blog
permalink: "/blog/"
layout: page
---

Welcome to the Clinic99 blog where we will post the latest news and events related to our new sexual health, contraception and HIV clinic software.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  - {{ post.date | date: "%d %b, %Y" }}
    </li> <img src="/assets/img/blog/{{ post.image }}" alt="" width="100" height="100">
  {% endfor %}
</ul>