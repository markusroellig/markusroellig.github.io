---
title: "Star formation in low-metallicity ISM"
collection: research
category: elements
order_number: 20
layout: archive
excerpt: "<img src='/images/research/clump-2.png' alt=''>"
header:
  og_image: "research/clump-2.png.jpg"
---

A reduced metallicity significantly affects the cooling and heating capacity of the interstellar medium. Lower amounts of dust and PAHs lead to weaker photo-electric heating efficiencies. The formation of H<sub>2</sub> is less effective because the available grain surface is decreased. On the other hand, the majority of cooling lines is also damped due to reduced elemental abundances of the coolants. We study massive star forming regions in low-metallicity environments, e.g. the LMC and SMC to study how the local metallicity informs the typical tracers of massive star formation.


## Publications

{% assign sorted-publications = site.publications | where: "tags","low-Z" %}
{% for post in sorted-publications reversed %}
    {% include archive-single.html %}
{% endfor %}
