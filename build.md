---
layout: page
type: build
title: Build Design Patterns
---
{% for entry in site.build %}
<div class="pattern">
    <h3><a href="{{ entry.url }}">{{ entry.title }}</a></h3>
    {{ entry.excerpt }}
</div>
{% endfor %}

