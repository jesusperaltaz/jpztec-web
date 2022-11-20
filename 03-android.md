---
layout: page
title: Android
permalink: android/
---

> Presiona CTRL + F para buscar.

{% assign lista_android = site.android | reverse %}

{% for post in lista_android %}<a href="{{ post.url }}"><img src="{{ post.baner }}" width="243"></a>|<a href="{{ post.url }}">{{ post.title }}</a><br>{{ post.descripcion }}|
{% endfor %}