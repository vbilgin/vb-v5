---
layout: content
title: Hi!
---

I'm **Victor**, an aspiring IT professional. Read more about me [here](/about). This blog is dedicated to write-ups about general IT topics and Cybersecurity. The posts here are not guides but moreso a journal of my experiences with different projects and topics. Find some recent posts below:

## Latest Posts
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
      <br/>
    </li>
  {% endfor %}
</ul>