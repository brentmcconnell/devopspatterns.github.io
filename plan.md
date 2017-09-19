---
layout: page
type: plan
title: Plan Design Patterns
---
{% for entry in site.plan %}
<div class="pattern">
    <h3><a href="{{ entry.url }}">{{ entry.title }}</a></h3>
    {{ entry.excerpt }}
</div>
{% endfor %}