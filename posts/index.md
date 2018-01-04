<div class="tiles">
{% for post in site.categories.posts %}
{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 posts 的列出来-->