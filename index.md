---
layout: page
title: Team CrystalMath
tagline: Just codin'
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)




  {% for post in site.posts %}
  <ul class="posts">
    <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2><span>{{ post.date | date_to_string }}</span><br>
    {{ post.content }}
    </ul>
  {% endfor %}



