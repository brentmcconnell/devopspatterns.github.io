---
layout: page
type: test
show-avatar: no
title: Test Design Patterns
---
{% for entry in site.test %}
<div class="pattern">
    <h3><a href="{{ entry.url }}">{{ entry.title }}</a></h3>
    {{ entry.excerpt }}
</div>
{% endfor %}