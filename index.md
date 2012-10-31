---
layout: page
title: Halo Dunia!
tagline: 
---
{% include JB/setup %}

<ul class="unstyled">
  {% for post in site.posts %}
    <li>
        <p><h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2></p>
        {{ post.excerpt }}<em> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.teaser }} &raquo;</a></em>
    </li>
  {% endfor %}
</ul>
