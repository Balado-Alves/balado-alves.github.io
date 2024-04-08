---
layout: archive
title: "Selected talks"
permalink: /talks/
author_profile: true
---

- _Critical submanifolds of higher order functionals_, University of Cagliari, February 2024.
- _Explicit harmonic self-maps of complex projective spaces_, University of Iasi, September 2023.
- _Recíproco del Teorema Egregium_, University of Santiago de Compostela, April 2021.

Reseach stays
======

- University of Cagliari, Italy, February 2024.

Outreach
======

- _¿Para qué sirven las matemáticas?_, INGADA Foundation, October 2020.

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
