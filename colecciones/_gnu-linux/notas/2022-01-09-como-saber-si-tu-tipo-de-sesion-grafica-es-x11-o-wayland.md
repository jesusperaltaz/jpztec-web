---
layout: post
title: "Como saber si tu tipo de sesión gráfica es x11 o wayland."
date: 2022-01-09
baner: https://unsplash.com/photos/oTjFWTHDRZQ/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8NDF8fHNjcmVlbnxlc3wwfHx8fDE2NTY3MDYxMzg&force=true&w=640
descripcion: Proceso util para cuando quieres saber si tu sesion grafica esta corriendo sobre xorg o wyland...
category: notas
permalink: /:collection/:categories/:title
---

Proceso util para cuando quieres saber si tu sesion grafica esta corriendo sobre xorg o wyland.

Para ello correremos estos comandos:

~~~bash
$ loginctl
$ loginctl show-session numero_de_sesion -p Type
~~~

Remplazando numero_de_sesion por nuestro número de sesión.

Ejemplo:

~~~bash
$ loginctl show-session 2 -p Type
~~~

## Pasos en terminal

~~~bash
#obtenemos el numero de sesión

[jpz@hackerz ~]$ loginctl
SESSION  UID USER SEAT  TTY
      1 1000 jpz  seat0 

1 sessions listed.

#obtenemos el tipo de sesión

[jpz@hackerz ~]$ loginctl show-session 1 -p Type
Type=x11
[jpz@hackerz ~]$ 

#nuestra sesion es tipo x11
~~~