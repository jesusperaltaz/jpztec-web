---
layout: post
title: "Añadir lanzadores al menu de aplicaciones de GNU/Linux."
date: 2022-10-20 04:00:00 -0500
baner: https://unsplash.com/photos/4Mw7nkQDByk/download?force=true&w=640
descripcion: Nos hubicamos en el directorio `/usr/share/applications` para añadir un lanzador en todo el...
category: wiki
permalink: /:collection/:categories/:title
published: false
---

Nos hubicamos en el directorio `/usr/share/applications` para añadir un lanzador en todo el sistema y en el directorio `/home/username/.local/share/applicatios/` para añadirlo solo al menu de un usuario en especifico.

Una vez ubicados en este directorio crearemos un archivo con la siguiente estructura:

~~~bash
[Desktop Entry]
Name=
Type=
Categories=
Exec=
Icon=
Keywords=
~~~

Y rellenaremos los campos según lo necesitemos:

~~~bash
[Desktop Entry]
Name=VS Code
Type=Application
Categories=Programación
Exec=~/Programas/VSCode/bin/code
Icon=~/Iconos/vscode.png
Keywords=Programación;VS;Code;HTML;Python;
~~~

Guardamos el archivo con un nombre descriptivo, seguido de la extención `.desktop`, como por ejemplo: vscode.desktop y reiniciamos nuestra sesión grafica si es necesario y listo tendremos el lanzador que creamos en nuestro menu de aplicaciones. 