---
layout: page
title: fly1988happy
tagline: day day up
---
{% include JB/setup %}

###Here's my learning 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




