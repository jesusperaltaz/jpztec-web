---
layout: page
title: Posts
permalink: posts/
published: false
---

> Presiona CTRL + F para buscar.

{% for post in site.posts %}<a href="{{ post.url }}"><img src="{{ post.baner }}" width="243"></a>|<a href="{{ post.url }}">{{ post.title }}</a><br>{{ post.descripcion }}|
{% endfor %}