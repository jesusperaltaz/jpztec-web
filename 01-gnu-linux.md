---
layout: page
title: GNU/Linux
permalink: gnu-linux/
---

> Presiona CTRL + F para buscar.

{% assign lista_gnu-linux = site.gnu-linux | reverse %}

{% for post in lista_gnu-linux %}<a href="{{ post.url }}"><img src="{{ post.baner }}" width="243"></a>|<a href="{{ post.url }}">{{ post.title }}</a><br>{{ post.descripcion }}|
{% endfor %}