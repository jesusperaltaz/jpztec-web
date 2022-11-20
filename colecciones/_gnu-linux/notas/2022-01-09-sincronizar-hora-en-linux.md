---
layout: post
title: "Sincronizar la hora en Linux."
date: 2022-01-09 05:00:00 -0600
baner: https://unsplash.com/photos/vGnM9e-dYgA/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8N3x8Y29tcHV0ZXIlMjBjbG9ja3xlc3wwfHx8fDE2NTY3MDYyNDM&force=true&w=640
descripcion: Esta nota es más que nada para personas a las que se les cambia la hora por un error en la zona...
category: notas
permalink: /:collection/:categories/:title
---

Esta nota es más que nada para personas a las que se les cambia la hora por un error en la zona horaria por tener dual boot con windows.

Bastara con ejecutar estos comandos:

~~~bash
$ timedatectl
$ sudo timedatectl set-ntp true
$ timedatectl
~~~