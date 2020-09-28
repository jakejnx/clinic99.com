---
title: Blog
permalink: "/blog/"
layout: page
---

Welcome to the Clinic99 blog where we will post the latest news and events related to our new sexual health, contraception and HIV clinic software.

  {% for post in site.posts %}
<div class="w3-card-4 w3-ul"><a href="{{ post.url }}">
    <li class="w3-bar">
      <img src="/assets/img/blog/{{ post.image }}" alt=""  class="w3-bar-item w3-circle" style="width:100px; height: 85px;">
      <div class="w3-bar-item">
        <span style="font-size: 1.5rem; color: #000;">{{ post.title }}</span><br>
        <span style="color: #000;">{{ post.date | date: "%d %b, %Y" }}</span>
      </div></li></a></div>
  {% endfor %}