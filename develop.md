---
layout: page
type: develop
title: Develop Design Patterns
---
{% for entry in site.develop %}
<div class="pattern">
    <h3><a href="{{ entry.url }}">{{ entry.title }}</a></h3>
    {{ entry.excerpt }}
</div>
{% endfor %}
