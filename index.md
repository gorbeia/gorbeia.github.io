---
layout: page
title: Gorbeia's Github page!
tagline: Small pastimes
---
{% include JB/setup %}

Page for my small projects.

<ul>
<li><a href="/EnpleguDatuakJS/">Data for employment by council</a></li>
</ul>
## Sample Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
