---
title: "Low Metallicity ISM"
collection: research
category: elements
order_number: 10
layout: single-portfolio
excerpt: "<img src='/images/research/clump-2.png' alt=''>"
header:
  og_image: "research/clump-2.png.jpg"
---




## Publications

{% for post in site.publications reversed %}
  {% if post.tag == 'low-Z' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
