---
layout: post
title: "Auto-click con Python usando pyautogui."
date: 2022-01-14 05:00:00 -0600
baner: https://unsplash.com/photos/Y5yxdx2a4PI/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MTE1fHxwcm9ncmFtaW5nfGVzfDB8fHx8MTY1NjcwNTgzMg&force=true&w=640
descripcion: Pequeño tutorial de como usar la libreria "pyautogui" que sirve para automatizar el puntero de...
category: tutoriales
permalink: /:collection/:categories/:title
---

Pequeño tutorial de como usar la libreria "pyautogui" que sirve para automatizar el puntero de nuestro PC.

~~~python
import pyautogui

#obtenemos el tamaño de la pantalla
width, height = pyautogui.size()

#obtenemos la posición actual del mouse
x, y = pyautogui.position()

#movemos el cursor a una coordenada especifica
pyautogui.moveTo(100, 100, duration=0.25)

#movemos el cursor 100 pixeles a la derecha durante 0.25 segundos
pyautogui.moveRel(100, 0, duration=0.25)
#movemos el cursor 100 pixeles a la izquierda durante 0.25 segundos
pyautogui.moveRel(-100, 0, duration=0.25)
#movemos el cursor 100 pixeles a la abajo durante 0.25 segundos
pyautogui.moveRel(0, 100, duration=0.25)
#movemos el cursor 100 pixeles a la arriba durante 0.25 segundos
pyautogui.moveRel(0, -100, duration=0.25)

#realizamos un clic
pyautogui.click()
~~~