---
permalink: /projects/
title: "Projects"
---

{% include base_path %}

{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %}
{% include archive-single.html type="grid" %}
{% endfor %}
