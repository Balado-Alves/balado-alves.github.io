---
layout: archive
title: "Preprints"
permalink: /publications/
author_profile: true
---

- J. M. Balado-Alves and A. Siffert, _Construction of r-harmonic submanifolds in spheres_, preprint [https://arxiv.org/abs/2404.02535](https://arxiv.org/abs/2404.02535) (2024).

Accepted
======
I am a PhD student in mathematics at the [Mathematical Institute](https://www.uni-muenster.de/MathematischesInstitut/en/index.shtml) of the [University of Münster](https://www.uni-muenster.de/en/). I am a member of the Cluster of Excellence "Mathematics Münster: Dynamics – Geometry – Structure" and the CRC 1442 "Geometry: Deformations and Rigidity". My supervisor is Anna Siffert.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
