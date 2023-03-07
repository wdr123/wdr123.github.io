---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research falls into two main areas: Reinforcement learning research and applications, where I develop novel algorithms
to handle well-known difficult problems in RL training, such as ```offline learning, uncertainty-aware RL, semi-supervised RL``` to handle data limitation and sub-optimality problems.

My other main research agenda uses advanced RL methods combining with uncertainty theory to help predict user's preference on movies (```recommender system, multi-modal fusion```),
predict ASD patients from time series data recording from their reactions when playing a game (```medicine, time sequence prediction```), and CV related ```image based sketch retrieval, object detection```, etc.

Now, my focus is on applying RL to language models for text summarization and traditional backbone networks for architecture search to solve ```Lottery Ticket Hypothesis``` problem.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
