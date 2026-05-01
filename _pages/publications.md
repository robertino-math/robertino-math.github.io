---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Preprints

* **Stable Wild Vafa-Witten Bundles on the Projective Plane** Robert J. Cornea  
  *Submitted, 2026.* [[PDF](files/Stable_Wild_Vafa_Witten_Bundles_on_the_Projective_Plane.pdf)] [[arXiv](https://arxiv.org/abs/2605.XXXXX)]


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
