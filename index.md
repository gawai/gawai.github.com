---
layout: page
title: Halo Dunia!
tagline: 
---

<ul class="unstyled">
  {% for post in site.posts %}
    <li>
        <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
        {{ post.content | replace:"more start -->","" | replace:"<-- more end","" }}
        <p style="text-align: right"><em><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.teaser }} &raquo;</a></em></p>
    </li>
  {% endfor %}
</ul>
