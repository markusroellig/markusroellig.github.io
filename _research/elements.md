---
title: "Elemental evolution of the universe"
collection: research
layout: archive
category: branch
order_number: 10
excerpt: "<img src='/images/research/30Dor.jpg' alt=''>"
---

The elemental composition of the ISM determines the chemical and physical evolution ([Röllig, Ossenkopf, Jeyakumar, Stutzki, & Sternberg, 2006](https://ui.adsabs.harvard.edu/abs/2006A&A...451..917R)). For example: CO is the main molecular reservoir for oxygen and carbon. In general, oxygen is about twice as abundant compared to carbon and as a consequence the CO abundance is limited by the elemental carbon abundance. Around carbon rich stars, this situation is inverted and now the limited availability of oxygen atoms controls the CO formation and evolution.

The overall metallicity of the ISM determines its physical and chemical conditions. With a lower abundance of elements heavier than helium, the dust-to-gas ratio decreases. As a consequence FUV radiation can penetrate deeper into molecular clouds. Another consequence is the reduction of the CO-to-C<sup>+</sup> column density ratio because the shielding of CO from destructive FUV radiation depends on the CO column, which is diminished for lack of carbon atoms.  


<div>
{% assign categ_pages = site.research | where:"category", "elements" %}
{% assign ordered_pages =  categ_pages | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
