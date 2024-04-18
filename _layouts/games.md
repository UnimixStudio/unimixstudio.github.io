---
layout: default
---
<h1>Список игр</h1>
<ul>
  {% for game in site.games %}
    <li><a href="{{ game.url }}">{{ game.title }}</a></li>
  {% endfor %}
</ul>