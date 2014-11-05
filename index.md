---
layout: page
title: Midnight Teaparty
tagline:
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


<br>
<br>
<br>
<h2> To-Do <h2/>
<p>
This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/thebadhatter/thebaddesthat.git)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.<p>


