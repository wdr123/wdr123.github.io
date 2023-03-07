---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
header:
og_image: "projects/chineseocr.png"
---


{% include base_path %}

{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %}
{% include archive-single.html type="grid" %}
{% endfor %}
