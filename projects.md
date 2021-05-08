---
layout: page
title: Projects
permalink: /projects/
---


{% for page in site.pages %}
{% if page.categories contains 'project' %}
* [{{ page.title }}]({{ page.url | absolute_url }}) - *{{ page.description }}*
{% endif %}
{% endfor %}

