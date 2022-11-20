---
layout: post
title: "Ejecutar una orden al iniciar la terminal."
date: 2022-01-10 05:00:00 -0600
baner: https://unsplash.com/photos/xbEVM6oJ1Fs/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8Mnx8YmFzaHx8MHx8fHwxNjQzMTI5ODE3&force=true&w=640
descripcion: Si al lanzar una terminal quieres que se ejecute un comando como por ejemplo `neofetch` lo que...
category: wiki
permalink: /:collection/:categories/:title
---

Si al lanzar una terminal quieres que se ejecute un comando como por ejemplo `neofetch` lo que tenemos que hacer es editar el archivo de configuración de nuestra shell. Y añadir la orden que deseemos al final del archivo.

Este archivo se encuentra en la carpeta principal del usuario.

Para bash editaremos el archivo con la ruta `~/.bashrc`

Y para zsh es `~/.zshrc`

## Pasos en consola

~~~bash
#abrios el archivo con el editor nano
$ nano ~/.bashrc

#añadimos la linea `neofetch` al final del archivo (ver imagen siguiente)
~~~

![bash](../../../../../assets/images/screenshot001.png)

~~~bash
#guardamos con ctrl + s
#cerramos el editor con ctrl + x

#listo, lanza tu terminal y mira la magia
~~~