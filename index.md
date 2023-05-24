# Cookbook

## Savoury
{% assign doclist = site.pages | sort: 'url'  %}
<ul>
{% for doc in doclist %}
{% if doc.name contains '.md' and doc.dir contains 'savoury/' %}
<li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.dir | url_decode | remove: "/savoury/" | remove: ".md" }}{{ doc.name }}</a></li>
{% endif %}
{% endfor %}
</ul>

## Sweet
{% assign doclist = site.pages | sort: 'url'  %}
<ul>
{% for doc in doclist %}
{% if doc.name contains '.md' and doc.dir contains 'sweet/' %}
<li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.dir | url_decode | remove: "/sweet/" | remove: ".md" }}{{ doc.name }}</a></li>
{% endif %}
{% endfor %}
</ul>