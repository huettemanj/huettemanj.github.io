---
title: 2015 Rinker 196 Captiva  
permalink: /rinker/  
layout: page  
sitemap: false  
---


## All about my 2015 Rinker Captiva ##

**Purchase Date:** 1/27/2017  
**Model:** Rinker Captiva 196  
**Engine:** Merc 4.3  
**Outdrive:** Alpha 1  
**Length:** 19'6"  
**Purchase From:** [Krupas Boat Mart (Jackson Michigan)](http://www.krupas.com/)

### Special Links ###
[Mercury Service Bulletin on Fogging a MPI Engine](http://www.marinemechanic.com/merc/distributors/mercurymarine/sterndrive/foggingefi.pdf)

### Pictures ###
[Link To Show Room Pictures](<https://huettemanj.github.io/rinkerpictures>)  

{% if string contains 'hello' %}
   string includes 'hello'
{% endif %}

## Blog Posts about the Rinker

<ul class="posts">
  {% for post in site.posts %}
    {% if post.title contains 'Rinker' %} 
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
