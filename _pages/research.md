---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

In my current research, I am considering the interplay between ecological and evolutionary processes in population dynamics scenarios, and hope to unveil a deeper understanding of how environmental variability and internal fluctuations can impact such systems. These findings are relevant to the global issue of antimicrobial resistance (AMR) and the longstanding problem of species diversity.

To do this, I use several techniques from statistical physics, dynamical systems (largely focused on population dynamics), and evolutionary game theory.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
