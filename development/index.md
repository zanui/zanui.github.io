---
layout: page
title: Development
excerpt: "An archive of posts related to software development."
---

<ul class="post-list">
{% for post in site.categories.development %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>
