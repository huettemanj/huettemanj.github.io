---
layout: page
title: Joe Huetteman!
tagline: Nobody Cares Anyway
---
{% include JB/setup %}  
## Important Topics 
[2015 Rinker Captiva](https://huettemanj.github.io/rinker/) 
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Put To-Do here

