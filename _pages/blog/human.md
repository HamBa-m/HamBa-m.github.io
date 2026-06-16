---
layout: single
title: "Human"
permalink: /blog/human/
author_profile: true
classes: wide
---

**Life, Logic, & Leadership.**

Behind every researcher is a human being navigating the complexities of career, community, and growth. This is where I share personal experiences, thoughts on society, economy, politics, and the intersection of technology with the human experience.

### Recent Posts

<div class="notice--info" markdown="1">

{% for post in site.categories.human %}
* <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
  * {{ post.date | date: "%B %d, %Y" }} — {{ post.excerpt | strip_html | truncatewords: 20 }}
{% endfor %}

</div>