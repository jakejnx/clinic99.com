---
title: Welcome
layout: home
---

<h2>Welcome to Clinic99</h2>
<p>We believe the time has come for sexual health electronic patient records to be more focussed around the new world we work in.  Current software was built many years ago and the needs have changed as clinics and services have responded to the changing needs of patients.</p>
<p>
We want to take an approach of listening to front line staff to make software that is really easy to use and "just works".  We want to take the clinicians attention away from the computer and back to the patient.</p>
<p>
Our project is anticipated to run for 12 months before we have a release candidate ready to run in a service.  We are currently building the software and working closely with our experts to ensure our attention is put in the right places.</p>

<h3>Latest News:</h3>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  - {{ post.date | date: "%d %b, %Y" }}
    </li>
  {% endfor %}
</ul>