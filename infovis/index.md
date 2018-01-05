---
layout: archive
title: "信息可视化作品集"
date: 2017-10-02T10:03:03-04:00
modified:
tags: []

image: 
  feature: infovis.jpg
---
 


<div class="tiles">
{% for post in site.categories.infovis %}
{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
