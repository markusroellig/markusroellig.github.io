---
title: "Massive Star Formation & Feedback"
collection: research
layout: archive
category: branch
order_number: 20
excerpt: "<img src='/images/research/ngc3603.jpg' alt=''>"
---

## Massive Star Formation & Feedback

Recent ALMA (Atacama Large Millimeter Array, Chile) observations of the closest massive star forming region Orion (distance 416 pc) clearly show the direct influence of the young massive Trapezium stars on the nearby Orion Molecular Cloud. Strong radiation and shock waves excavate dense clumps from the molecular cloud. The erosion of the cloud surface is the most detailed direct observation of the dynamics and the extreme non-stationary processes involved in massive star formation. With unprecedented spatial resolution we observe that the ISM is progressively evolved with growing distance from the illuminating stars. The so called ionization front is particularly important. This is where the hot ionized gas from the HII region expands with velocities of about 10 km/s into the molecular cloud and excavates large, dense clumps of molecular gas. Even though they are now unshielded from the intense FUV radiation, molecules may further survive because the chemical time scales involved are larger than those of the kinematics (approx. 20000 years). The chemical composition of the molecular clumps is not in equilibrium with their surroundings.


<div>
{% assign categ_pages = site.research | where:"category", "massiveSF" %}
{% assign ordered_pages =  categ_pages | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
