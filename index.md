---
layout: page_head
title: vaccarus
tagline: this is where the words go
---
{% include JB/setup %}


## Hey there ...

There's a pic of my dog Mosley.

And here's a list of some recent posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


