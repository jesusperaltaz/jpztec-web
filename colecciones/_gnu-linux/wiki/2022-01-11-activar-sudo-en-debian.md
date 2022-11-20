---
layout: post
title: "Activar sudo en Debian."
date: 2022-01-11 05:00:00 -0600
baner: https://unsplash.com/photos/4Mw7nkQDByk/download?force=true&w=640
descripcion: Por defecto Debian no activa el modo sudo, para ello hay que añadir nuestro usuario al grupo de...
category: wiki
permalink: /:collection/:categories/:title
---

Por defecto Debian no activa el modo sudo, para ello hay que añadir nuestro usuario al grupo de administradores.

## Pasos en terminal

~~~bash
$ su root
~ nano /etc/sudoers

#añadimos la linea
user ALL=(ALL) ALL
~~~

Reiniciamos y listo