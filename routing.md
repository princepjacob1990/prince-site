---
title: "Routing Labs"
layout: single
permalink: /routing/
classes: wide
---

## Routing Labs

Below are real routing issues and labs.

{% assign routing_posts = site.posts | where_exp: "post", "post.categories contains 'routing'" %}

{% if routing_posts.size > 0 %}
{% for post in routing_posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% else %}
_No routing posts found._
{% endif %}
