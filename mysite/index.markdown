---
layout: default
title: Home
---
# Welcome to Junnie's home! 

#### *Find out the hot topic at the moment*

<br>

{% for post in site.posts %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{{ post.excerpt }}
{% endfor %}

