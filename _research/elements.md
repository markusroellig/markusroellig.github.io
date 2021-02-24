---
title: "Elemental evolution of the universe"
collection: research
layout: archive
category: branch
order_number: 10
excerpt: "<img src='/images/research/30Dor.jpg' alt=''>"
---


## Elemental evolution of the universe




<div>
{% assign categ_pages = site.research | where:"category", "elements" %}
{% assign ordered_pages =  categ_pages | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
