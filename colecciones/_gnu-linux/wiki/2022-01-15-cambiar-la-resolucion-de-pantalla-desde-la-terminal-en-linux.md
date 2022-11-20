---
layout: post
title: "Cambiar la resolución de pantalla desde la terminal en Linux."
date: 2022-01-15 05:00:00 -0600
baner: https://unsplash.com/photos/vXInUOv1n84/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8OXx8cHJvZ3JhbWFtaW5nfGVzfDB8fHx8MTY1NjcxNjUxMA&force=true&w=640
descripcion: Obtenemos las resolluciones disponibles de nuestro monitor ejecuntado el comando `xrandr` y...
category: wiki
permalink: /:collection/:categories/:title
---

Obtenemos las resolluciones disponibles de nuestro monitor ejecuntado el comando `xrandr` y obtendremos la siguiente salida:

![resoluciones_de_pantalla](../../../../../assets/images/screenshot002.png)

Ahora ejecutaremos el comando `xrandr -s #` remplazando # por el número de resolución que queramos poner empezando desde 0.

Por ejemplo si queremos poner la resolución 800x600 el comando ejecutariamos:

~~~bash
$ xrandr -s 3
~~~