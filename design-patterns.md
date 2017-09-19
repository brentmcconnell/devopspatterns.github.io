---
layout: page
title: Design Patterns 
subtitle: and Anti-Patterns
bigimg: /img/cogs2.jpg
---
<div>
{% for pattern in site.collections %}
    {% if pattern.label != 'posts' %}
        <h3><a href="{{ pattern.url }}">{{ pattern.title }}</a></h3>
        <div class="pattern_description">{{ pattern.description }}</div>
    {% endif %}
{% endfor %}
</div>

