---
permalink: "/archive/"
title: "Archive"
order: 1
---

<div>

   {% assign index = true %}
   {% assign year  = '' %}

   <ul class="article-list">
      {% for post in site.posts %}
      {% assign page = post %}
      {% assign date = page.date | date: "%Y" %}

      {% if year != date %}
      {% assign year = date %}
      <li class="list-year"> {{year}} </li>
      {% endif%}

      <li class="list-item">
        <span class="list-date" >{{ page.date | date: "%Y-%m-%d" }}</span> 
        <a href="{{ page.url }}">{{ page.title }}</a>
       </li>
       {% endfor %}
   </ul>

<p class="rss-subscribe">Subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>
