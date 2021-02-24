---
title: "Massive Star Formation & Feedback"
collection: research
layout: archive
category: branch
order_number: 20
excerpt: "<img src='/images/research/ngc3603.jpg' alt=''>"
---

## Massive Star Formation & Feedback

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.


<div>
{% assign categ_pages = site.research | where:"category", "massiveSF" %}
{% assign ordered_pages =  categ_pages | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
