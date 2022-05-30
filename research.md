---
layout: page
permalink: /research/
title: Research
physics_pubs:

    - title:   "An exploratory study of the impact of CMS double-differential top distributions on the gluon parton distribution function."
      author:  "M. Czakon, S. Dulat, T.-J. Hou, J. Huston, A. Mitov, A.S. Papanastasiou, I. Sitiwaldi, Z. Yu and C.-P. Yuan"
      journal: "J.Phys.G 48 (2021) 1, 015003"
      year:    "2021"
      doi:     "https://doi.org/10.1088/1361-6471/abb1b6"
      arxiv:   "https://arxiv.org/abs/1912.08801"

    - title:   "Higher order corrections to spin correlations in top quark pair production at the LHC."
      author:  "A. Behring, M. Czakon, A. Mitov, A.S. Papanastasiou and R. Poncelet"
      journal: "Phys.Rev.Lett. 123 (2019) 8, 082001"
      year:    "2019"
      doi:     "https://doi.org/10.1103/PhysRevLett.123.082001"
      arxiv:   "https://arxiv.org/abs/1901.05407"


physics_preprints:

    - title:   "Simultaneous extraction of $\alpha_s$ and $m_t$ from LHC $t\bar{t}$ differential distributions"
      author:  "A.M. Cooper-Sarkar, M. Czakon, M.A. Lim, A. Mitov, A.S. Papanastasiou"
      year:    "2020"
      arxiv:   "https://arxiv.org/abs/2010.04171"



---

## Physics Publications (peer reviewed)

{% for pub in page.physics_pubs %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}* 
{% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}
{% if pub.arxiv %}[[arxiv]({{pub.arxiv}})]{% endif %}

{% endfor %}


## Physics Pre-prints

{% for pub in page.physics_preprints %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pub.author}}<br />
 *{{pub.year}}* 
{% if pub.arxiv %}[[arxiv]({{pub.arxiv}})]{% endif %}

{% endfor %}
