---
title: "Human"
layout: single
permalink: /blog/human/
author_profile: false
---
# Human

<ul>
  {% for post in site.categories.human %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%B %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>