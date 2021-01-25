
---
title: "News"
layout: textlay
excerpt: "Allan Lab at Leiden University."
sitemap: false
permalink: /allnews.html
---
![Image text](http://faculty.dlut.edu.cn/_resources/group1/M00/00/1E/ynZMhF8RfiKAYPa3AAEKMjZAwuA675.jpg)
# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
