---
layout: archive
title: "Preprints"
# permalink: /publications/
author_profile: true
---

- J. M. Balado-Alves and A. Siffert, _Construction of r-harmonic submanifolds in spheres_, preprint [https://arxiv.org/abs/2404.02535](https://arxiv.org/abs/2404.02535) (2024).

Accepted
======

2. J. M. Balado-Alves, _Polyharmonic hypersurfaces into complex space forms_, preprint [https://arxiv.org/abs/2310.14452](https://arxiv.org/abs/2310.14452) (2023), To appear in: Ann. Mat. Pura Appl.
1. J. M. Balado-Alves, _Explicit harmonic self-maps of complex projective spaces_, J. Geom. Anal. **34** (2024) 21 (pp. 22) [https://doi.org/10.1007/s12220-023-01465-w](https://doi.org/10.1007/s12220-023-01465-w)


 {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
 {% endif %}

 {% include base_path %}

 {% for post in site.publications reversed %}
  {% include archive-single.html %}
 {% endfor %}
