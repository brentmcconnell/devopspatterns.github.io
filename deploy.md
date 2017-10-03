---
layout: page
type: deploy
show-avatar: no
title: Deploy Design Patterns
---
{% for entry in site.deploy %}
<div class="pattern">
    <h3><a href="{{ entry.url }}">{{ entry.title }}</a></h3>
    {{ entry.excerpt }}
</div>
{% endfor %}