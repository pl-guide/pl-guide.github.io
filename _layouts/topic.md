---
layout: default
---

{% if page.title %}
<h1>{{ page.title }}</h1>
{% else %}
<div class="title-warning"><strong>Warning:</strong> This page has no title</div>
{% endif %}

{{ content }}