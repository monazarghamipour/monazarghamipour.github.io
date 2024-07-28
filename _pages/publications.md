---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
<b>Zarghamipour, M.,<b> Malakooti, H., & Bordbar, M. H. (2024). Spatio-temporal Analysis of the factors affecting NOx concentration during the evaluation cycle of high pollution episodes in Tehran metropolitan. Atmospheric Pollution Research, 15(8), 102177. [Link](https://www.sciencedirect.com/science/article/abs/pii/S1309104224001429)
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
