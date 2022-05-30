---
layout: page
permalink: /research/
title: Research
pubs:

    - title:   "Higher order corrections to spin correlations in top quark pair production at the LHC"
      author:  "A. Behring, M. Czakon, A. Mitov, A.~S. Papanastasiou and R. Poncelet"
      journal: "Phys.Rev.Lett. 123 (2019) 8, 082001"
      note:    "SIGGRAPH Asia"
      year:    "2019"
      doi:     "https://doi.org/10.1103/PhysRevLett.123.082001"



---

## Publications (peer reviewed)

{% for pub in page.pubs %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}* {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}

{% endfor %}
