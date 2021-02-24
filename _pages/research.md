---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

*Keywords:* microphysics of the interstellar medium (ISM), chemical and elemental evolution of the ISM, Galactic and Extragalactic research, computational astrophysics, astrochemistry, formation and evolution of stars and planets, stellar feedback, machine learning, numerical simulation

What makes studies of the interstellar medium (ISM) such an important and active research topic? The ISM makes up only 10% of the baryonic matter in the local universe but it is tightly coupled to the formation of stars and planets. It sets the stage for their formation as well as providing all the materials they are built from. Equally important is the coupling to the final stages of stellar evolution when evolved stars feed large portions of their mass, enriched by nucleosynthesis, back into the ISM, thus defining the elemental context for the next stellar generations. The coupling is even more complex because it operates in both directions. Stars are formed from gravitational collapse in dense molecular clouds and newborn massive stars provide a powerful feedback to the ISM in the form of radiation, stellar winds and expanding ionized gas, possibly triggering or preventing the next period of star formation.

## Research Areas

<div>
{% assign categ_pages = site.research | where:"category", "branch" %}
{% assign ordered_pages =  categ_pages | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
