---
title: Blog
permalink: "/blog/"
layout: page
---

This is something new which is coming soon.

<div class="content">
<ul>
{% assign blog1 = site.posts | sort: 'date' | reverse %}
{% for post in blog1 %}
<li><a href="{{ post.url }}"> {{ post.title }}</a> - {{ post.categories }} - {{ post.date | date: "%B %Y"}} </li>
{% endfor %}
</ul>
</div>