---
layout: page
title: Halo Dunia!
tagline: Ini yang kau cari
---

<h1>Halo Dunia!</h1>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis magna erat, rhoncus nec consequat eu, laoreet vitae dolor. Morbi vel sem ac nulla fermentum laoreet. Vestibulum et erat sem. Mauris nunc est, tristique a cursus sit amet, venenatis eu turpis. Etiam imperdiet neque eget libero ultrices eget pretium metus tincidunt. Phasellus eget nisi tortor, at accumsan nisi. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Donec vel dolor ipsum, ut bibendum mi. Maecenas vel enim dui. Nulla quis turpis et nisl fringilla pellentesque.</p>
 
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>