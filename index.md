---
layout: page
title: Joe Huetteman!
tagline: Nobody Cares Anyway
---
---
layout: category
title: 2015 Rinker Captiva 196
category: rinker
---
{% include JB/setup %}
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Put To-Do here

