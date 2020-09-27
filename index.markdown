---
title: Welcome
layout: home
---

<h2>Welcome to Clinic99</h2>
welcome to clinic99

<h3>Recent Blog Posts:</h3>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  - {{ post.date | date: "%d %b, %Y" }}
    </li>
  {% endfor %}
</ul>