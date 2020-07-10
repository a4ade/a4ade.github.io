---
layout: default
title: "ötmeyen horozun çöplüğü."
---

<style>
.btn-github {
  display:none !important;
  }  
</style>
<h1>Son Yazılar</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
