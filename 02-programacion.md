---
layout: page
title: Programación
permalink: programacion/
---

> Presiona CTRL + F para buscar.

{% assign lista_programacion = site.programacion | reverse %}

{% for post in lista_programacion %}<a href="{{ post.url }}"><img src="{{ post.baner }}" width="243"></a>|<a href="{{ post.url }}">{{ post.title }}</a><br>{{ post.descripcion }}|
{% endfor %}