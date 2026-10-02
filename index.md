Cloud Computing and Big Data Analytics

IT 526

The accessible list of all topics is below :

<ul>
{% for file in site.static_files %}
{% comment %} Check for both PDF and HTML files {% endcomment %}
{% if file.extname == ".pdf" or file.extname == ".html" %}
<li><a href="{{ file.path | relative_url }}">{{ file.basename }}</a></li>
{% endif %}
{% endfor %}
</ul>
