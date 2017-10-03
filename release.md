---
layout: page
type: release
show-avatar: no
title: Release Design Patterns
---
{% for entry in site.release %}
<div class="pattern">
    <h3><a href="{{ entry.url }}">{{ entry.title }}</a></h3>
    {{ entry.excerpt }}
</div>
{% endfor %}