---
layout: content
title: Hi!
---
This blog is dedicated to write-ups (mostly professional but some personal) concerning IT, cybersecurity, and programming. The posts here are not guides but more so a journal of my experiences with different projects and topics. Find some recent posts below:

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