---
layout: page
title: Dad's Cardiac Event
permalink: /dad-cardiac/
---

Here is a list of posts about Dad's cardiac situation:

<ul>
  {% for post in site.categories.dad-cardiac %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
