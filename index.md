---
layout: page
title: This is my first post!
tagline: there is no tagline 
---
{% include JB/setup %}

## This must be a title

This is my first post. I just want to play for fun~

    Is this used to show codes?

Here shows all the posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



