---
layout: post
title: "Texto de colores en un Script para Linux."
date: 2022-01-13 05:00:00 -0600
baner: https://unsplash.com/photos/a4X1cdC1QAc/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjU2NzE2NjA2&force=true&w=640
descripcion: "Crea un script en bash colorido con este formato. El formato es el siguiente: echo -e `#mTexto`..."
category: wiki
permalink: /:collection/:categories/:title
---

Crea un script en bash colorido con este formato.

**El formato es el siguiente:**

~~~bash
echo -e "\e#mTexto"
~~~

**Donde # lo remplazamos por el número de color:**

|Código|Color|
|------|-----|
|30|negro|
|31|rojo|
|32|verde|
|33|amarillo|
|34|azul|
|35|magenta|
|36|cyan|
|37|blanco|

**Ejemplo:**

~~~bash
echo -e "\e[34mScript \e[33mde \e[31mprueba \e[35mde \e[36mcolores \e[0m"
~~~

**Resultado:**

![script_de_colores](../../../../../assets/images/script-de-colores.jpg)