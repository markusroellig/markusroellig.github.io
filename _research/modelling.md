---
title: "Models of the Interstellar Medium"
collection: research
layout: archive
category: branch
order_number: 30
excerpt: "<img src='/images/research/ensemble.png' alt=''>"
---

## Models of the Interstellar Medium

My research goal is to contribute to a better understanding of the physics and the chemistry in PDRs. If we really want to understand planet and star formation we need to be able to reliably interpret the emission from PDRs. One of my main instruments of choice to achieve this goal is numerical modelling and I am the leading German expert on the numerical modelling of PDRs.
Models are not just a tool to better understand your data. They can be a tool to better understand the physics of the universe. PDR Modelling in particular is crucial in interpreting observations of the interstellar medium (ISM) because all neutral atomic hydrogen gas and a large fraction of the molecular gas in the Milky Way external galaxies lie in PDRs.

I envision a time where our understanding of the physical and chemical processes in the interstellar medium (ISM) has reached a state that allows to consistently interpret the emission of atomic and molecular gas and of the dust. This is the key to a better understanding of fundamental topics, such as star and planet formation, and to answer fundamental questions such as: Under what conditions do habitable worlds form? What is the origin of the large reservoir of terrestrial water and why are other planets in the solar system lacking it?

Presently, we are far from this goal: We have difficulties to observationally disentangle the emission from different phases of the ISM, partly because we have only limited information on the local geometry. We lack the laboratory data to characterize many key components of the dominant astrochemistry and the important microphysical processes. On the other hand, our detector capacities are continuously growing. Modern instruments are more and more often designed to perform large survey observations. The expected astronomical data volume is gigantic. By way of contrast, the growth in modelling capacity is minor and the gap is widening. We need to invest in high-quality models in order to make good use of the observational data.

Models of photon dominated regions (PDRs) link the geometry of the ISM to its microphysics and are therefore the perfect numerical tool to study their interaction with star formation. However, PDR research is no scientific niche but elementary to understanding star formation, the ISM and consequently, the evolution of the Milky Way and other galaxies. Numerical models are the key to a better understanding of the universe and we need a dedicated effort to improve modern PDR modelling capabilities and to push their application in the analysis of modern astronomical data.


<div>
{% assign categ_pages = site.research | where:"category", "modelling" %}
{% assign ordered_pages =  categ_pages | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
