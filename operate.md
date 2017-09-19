---
layout: page
type: operate
title: Operate Design Patterns
---
{% for entry in site.operate %}
<div class="pattern">
    <h3><a href="{{ entry.url }}">{{ entry.title }}</a></h3>
    {{ entry.excerpt }}
</div>
{% endfor %}