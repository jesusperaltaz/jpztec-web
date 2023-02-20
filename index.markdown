---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<h2 class="post-list-heading"> Ultimos videos </h2>

<span class="post-meta">
  <a href="https://www.youtube.com/c/JPZTEC" >Todos los videos.</a>
</span>

|<a target="_blank" href="https://youtu.be/jf_48ANNPgI"><img src="https://img.youtube.com/vi/jf_48ANNPgI/maxresdefault.jpg" width="243"></a>|<a target="_blank" href="https://youtu.be/jf_48ANNPgI">Activar Virtualización :: Laptop Hp Pavilion.</a>|
|<a target="_blank" href="https://youtu.be/An_1HuLS-50"><img src="https://img.youtube.com/vi/An_1HuLS-50/maxresdefault.jpg" width="243"></a>|<a target="_blank" href="https://youtu.be/An_1HuLS-50">Activar Virtualización :: HP Compaq.</a>|
|<a target="_blank" href="https://youtu.be/z0VpNwZbzRA"><img src="https://img.youtube.com/vi/z0VpNwZbzRA/maxresdefault.jpg" width="243"></a>|<a target="_blank" href="https://youtu.be/z0VpNwZbzRA">Tasker :: Creación de una escena - Dialogo :: Tutorial Android.</a>|

<h2 class="post-list-heading"> GNU/Linux </h2>

<span class="post-meta">
  <a href="./gnu-linux" >Todas las publicaiones en GNU/Linux.</a>
</span>

{% assign lista_gnu-linux = site.gnu-linux | reverse %}

|<a href="{{ lista_gnu-linux[0].url }}"><img src="{{ lista_gnu-linux[0].baner }}" width="243"></a>|<a href="{{ lista_gnu-linux[0].url }}">{{ lista_gnu-linux[0].title }}</a><br>{{ lista_gnu-linux[0].descripcion }}|
|<a href="{{ lista_gnu-linux[1].url }}"><img src="{{ lista_gnu-linux[1].baner }}" width="243"></a>|<a href="{{ lista_gnu-linux[1].url }}">{{ lista_gnu-linux[1].title }}</a><br>{{ lista_gnu-linux[1].descripcion }}|
|<a href="{{ lista_gnu-linux[2].url }}"><img src="{{ lista_gnu-linux[2].baner }}" width="243"></a>|<a href="{{ lista_gnu-linux[2].url }}">{{ lista_gnu-linux[2].title }}</a><br>{{ lista_gnu-linux[2].descripcion }}|

<h2 class="post-list-heading"> Programación </h2>

<span class="post-meta">
  <a href="./programacion" >Todas las publicaiones en Programación.</a>
</span>

{% assign lista_programacion = site.programacion | reverse %}

|<a  href="{{ lista_programacion[0].url }}"><img src="{{ lista_programacion[0].baner }}" width="243"></a>|<a  href="{{ lista_programacion[0].url }}">{{ lista_programacion[0].title }}</a><br>{{ lista_programacion[0].descripcion }}|
|<a  href="{{ lista_programacion[1].url }}"><img src="{{ lista_programacion[1].baner }}" width="243"></a>|<a  href="{{ lista_programacion[1].url }}">{{ lista_programacion[1].title }}</a><br>{{ lista_programacion[1].descripcion }}|
|<a  href="{{ lista_programacion[2].url }}"><img src="{{ lista_programacion[2].baner }}" width="243"></a>|<a  href="{{ lista_programacion[2].url }}">{{ lista_programacion[2].title }}</a><br>{{ lista_programacion[2].descripcion }}|

<h2 class="post-list-heading"> Android </h2>

<span class="post-meta">
  <a href="./android" >Todas las publicaiones en Android.</a>
</span>

{% assign lista_android = site.android | reverse %}

|<a href="{{ lista_android[0].url }}"><img src="{{ lista_android[0].baner }}" width="243"></a>|<a  href="{{ lista_android[0].url }}">{{ lista_android[0].title }}</a><br>{{ lista_android[0].descripcion }}|
|<a href="{{ lista_android[1].url }}"><img src="{{ lista_android[1].baner }}" width="243"></a>|<a  href="{{ lista_android[1].url }}">{{ lista_android[1].title }}</a><br>{{ lista_android[1].descripcion }}|
|<a href="{{ lista_android[2].url }}"><img src="{{ lista_android[2].baner }}" width="243"></a>|<a  href="{{ lista_android[2].url }}">{{ lista_android[2].title }}</a><br>{{ lista_android[2].descripcion }}|

<!---
<h2 class="post-list-heading"> Otros Posts </h2>

<span class="post-meta">
  <a href="./posts" >Todas las publicaiones en Posts.</a>
</span>

|<a  href="{{ site.posts[0].url }}"><img src="{{ site.posts[0].baner }}" width="243"></a>|<a  href="{{ site.posts[0].url }}">{{ site.posts[0].title }}</a><br>{{ site.posts[0].descripcion }}|
|<a  href="{{ site.posts[1].url }}"><img src="{{ site.posts[1].baner }}" width="243"></a>|<a  href="{{ site.posts[1].url }}">{{ site.posts[1].title }}</a><br>{{ site.posts[1].descripcion }}|
|<a  href="{{ site.posts[2].url }}"><img src="{{ site.posts[2].baner }}" width="243"></a>|<a  href="{{ site.posts[2].url }}">{{ site.posts[2].title }}</a><br>{{ site.posts[2].descripcion }}|
--->