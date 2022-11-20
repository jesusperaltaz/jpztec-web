---
layout: post
title: "Iniciar XAMPP en Linux."
date: 2022-01-12 05:00:00 -0600
baner: https://unsplash.com/photos/fPkvU7RDmCo/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8eGFtcHB8ZXN8MHx8fHwxNjU2NzA2MzU2&force=true&w=640
descripcion: "Para iniciar XAMPP simplemente ejecuta este comando: /opt/lampp/lampp start como administrador..."
category: notas
permalink: /:collection/:categories/:title
---

Para iniciar XAMPP simplemente ejecuta este comando:

~~~bash
$ sudo /opt/lampp/lampp start
~~~

Para iniciar la herramienta gráfica ejecutar este comando:

~~~bash
$ cd /opt/lampp
$ sudo ./manager-linux.run (or manager-linux-x64.run)
~~~

O crear un alias en nuestra shell:

~~~bash
$ nano ~/.bashrc

#añadimos la linea
$ alias xampp='sudo /opt/lampp/manager-linux-x64.run'
~~~