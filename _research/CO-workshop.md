---
title: "2012 Workshop on CO Excitation"
collection: research
category: data
order_number: 11
layout: archive
excerpt: "<img src='/images/research/CO-poster-short.jpg'>"
header:
  og_image: "research/CO-poster-short"
---
<img align="right" src="/images/research/CO-poster.jpg" width="50%" HSPACE="50" VSPACE="50" />
# Exciting CO in the Local and High-Redshift Universe

### 27 February - 2 March 2012
### Venue: Lorentz Center@Oort

## Description and Aim

CO is the most widely used tracer of molecular gas throughout the universe. It is seen in a variety of objects: PDRs (UV dominated chemistry), shocks, embedded protostars (low and high mass), protoplanetary disks, interstellar medium (ISM) in nearby and high-redshift galaxies. So far, most observations have focused on the low energy transitions, CO J=1−0, 2−1, and 3−2, which are commonly observed from the ground with a variety of facilities in all these objects. Energy transitions with slightly higher excitation temperatures (J=6 or 7) are much harder to observe in the local universe or even completely blocked (J>8) by the atmosphere. Infrared Space Observatory (ISO) observed a number of high−J CO transitions in the brightest galactic objects. The launch of the Herschel Space Observatory opened up a new spectral window to study the molecular properties of objects at far-infrared and sub-millimeter wavelengths. The accessible wavelength range, ~55−600 μm, reveals new phases of the warm ISM, and makes it possible to study the molecular universe in a variety of conditions. Herschel systematically studies full CO ladders (up to J=38), and a number of guaranteed and open time key programs are dedicated to these particular lines in a variety of sources. Examples from the Herschel science demonstration phase, where CO turns out to be an important tracer, are Markarian 231, an ultra-luminous infrared galaxy, where gas excitation occurs through black hole accretion and star formation, and, on the other side of the range of exploration, the protostar HH46, where the surrounding hot gas is photon and shock heated. The ultimate goal is to use the CO ladder and fully understand the chemistry and excitation of CO as a tracer of the interstellar and circumstellar medium and characterize gas properties, i.e., physics and chemistry and its excitation sources in an unprecedented way.

Currently, everyone uses different numerical models and often various distinct processes for the interpretation of the data in the context of their type of sources. The goal of this workshop is to bring together for the first time people from different galactic and extra-galactic key programs, and learn about their observations and favorite analysis tools (PDRs, XDRs, and shocks), and make a detailed inventory and comparison of the models. Obvious questions are: Do different codes yield consistent solutions with the same input parameters? How unique are the solutions that we obtain with a code, or stated differently, would a code with different processes be able to obtain a solution as well? How are the gas temperatures calculated when exposed to UV and/or X-rays? Understanding the models and correctly applying them to observations is not only important for the interpretation for Herschel data, but also for the data to come from ALMA in the near future. This is a direct continuation of the successful PDR comparison workshop held at the Lorentz Center in 2004 (Röllig et al. 2007), but now placed in a broader context. The workshop is open, and not limited to the people from the key programs only.

Note: In order to compare different analysis tools, a number of test problems will need to be solved before the workshop. We will be in contact with the modellers soon on more details.

To this end, a [CO Excitation workshop](https://www.lorentzcenter.nl/exciting-co-in-the-local-and-high-redshift-universe.html) was held at the [Lorentz Center](https://www.lorentzcenter.nl) in Leiden, Netherlands in 2012 to jointly work on these topics

Here we present the results from this workshop and the results originating from the follow-up activities.

[CO Workshop files](https://github.com/markusroellig/CO-Excitation-Workshop){: .btn--research}

## Publications

{% assign sorted-publications = site.publications | where: "tags","data" %}
{% assign sorted-publications2 = sorted-publications | where: "tags","co-workshop" %}
{% for post in sorted-publications2 reversed %}
    {% include archive-single.html %}
{% endfor %}
