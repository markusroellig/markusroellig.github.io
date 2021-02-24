---
title: "Data Astronomy - New Analysis Strategies"
collection: research
layout: archive
category: branch
order_number: 50
excerpt: "<img src='/images/research/3DContourPlot-CII-2.png' alt=''>"
---




<div>
{% assign categ_pages = site.research | where:"category", "data" %}
{% assign ordered_pages =  categ_pages | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
