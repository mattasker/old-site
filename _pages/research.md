---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
How do bacteria with mutations take over the population they reside in? What mechanisms allow for multiple species to co-exist in a niche? What role do stochastic fluctuations play in the evolution of such systems? How does the ever-changing environment of these systems impact their evolution? Can we utilise any mechanisms to drive undesirable species to extinction while allowing the survival of beneficial bacteria? These are the sorts of questions I'm interested in!

In my current research, I am considering the interplay between ecological and evolutionary processes in population dynamics scenarios, particularly those concerning the emergence of cooperative behaviour and species coexistence. I use techniques from statistical physics, dynamical systems, and evolutionary game theory to investigate how environmental variability coupled to internal fluctuations can impact such systems. These findings are relevant to the global issue of antimicrobial resistance (AMR) and the longstanding problem of species diversity.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
