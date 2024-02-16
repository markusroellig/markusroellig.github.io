---
title: "JWST Early Release Science"
collection: research
category: massiveSF
order_number: 10
layout: archive
excerpt: "<img src='/images/research/cropped-logo_pdrs4all_transparent_clean.png' alt=''>"
header:
  og_image: "research/Images_release.006-2.png"
---


*PI team:*  [Olivier Berné](https://www.irap.omp.eu/author/olivier-berne/), [Emilie Habart](https://www.ias.u-psud.fr/en), [ Els Peeters](https://physics.uwo.ca/~epeeters/).

*Core team:* [LIST](https://pdrs4all.org/team/)

Massive stars disrupt their natal molecular cloud material by dissociating molecules, ionizing atoms and molecules, and heating the gas and dust. These processes drive the evolution of interstellar matter in our Galaxy and throughout the Universe from the era of vigorous star formation at redshifts of 1-3, to the present day. Much of this interaction occurs in Photo-Dissociation Regions (PDRs) where far-ultraviolet photons of these stars create a largely neutral, but warm region of gas and dust. PDR emission dominates the IR spectra of star- forming galaxies and also provides a unique tool to study in detail the physical and chemical processes that are relevant for most of the mass in inter- and circumstellar media including diffuse clouds, protoplanetary disk – and molecular cloud surfaces, globules, planetary nebulae, and starburst galaxies.

We propose to provide template datasets designed to identify key PDR characteristics in JWST spectra in order to guide the preparation of Cycle 2 proposals on star-forming regions in our Galaxy and beyond. We plan to obtain the first spatially resolved, high spectral resolution IR observations of a PDR using NIRCam, NIRSpec and MIRI. These data will test widely used theoretical models and extend them into the JWST era. We have engaged the broader community as exemplified by the supporting large international team of 138 scientists. We will assist the community interested in JWST observations of PDRs through science-enabling products that will guide observational planning and allow fast data analysis. We will train the community through telecons and dedicated workshops.

[Project Page](https://pdrs4all.org/){: .btn--research}

## Publications

{% assign sorted-publications = site.publications | where: "tags","pdrs4all" %}
{% for post in sorted-publications reversed %}
    {% include archive-single.html %}
{% endfor %}
