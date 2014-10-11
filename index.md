---
layout: page
title: Accueil
tagline: 
---
{% include JB/setup %}



<p>Groupe de travail sur les sujets de la performance dans l&#39;IT au Maroc</p>


    
##  Posts



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




