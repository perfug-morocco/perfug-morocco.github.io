---
layout: page
title: Accueil
tagline: 
---
{% include JB/setup %}



<p>Groupe de travail sur les sujets de la performance dans l&#39;IT au Maroc</p>


    
####  Posts



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



<div class="twitter-feed" id="twitter-feed">
    <h5>Twitter feed</h5>
<a class="twitter-timeline" href="https://twitter.com/perfugmorocco" data-widget-id="520912578600390656">Tweets by @perfugmorocco</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
</div>
