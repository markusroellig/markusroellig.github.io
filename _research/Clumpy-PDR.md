---
title: "Clumpy PDRs"
collection: research
category: modelling
order_number: 20
layout: archive
excerpt: "<img src='/images/research/clumpyDR21.jpg' width='230px' height='234px' alt=''>"
header:
  og_image: "research/clumpyDR21.jpg"
---

*Keywords:* computational astrophysics, photon dominated regions, astrochemistry, physics of the interstellar medium, star formation feedback, radiative transfer, numerical simulation

## Summary

Molecular cloud and star formation (SF) are the fundamental processes in the Cosmic Cycle of Matter. This cycle has shaped the evolution of the universe from the formation of the first generation of stars to its present appearance. The interaction of star formation with the interstellar medium (ISM) is most prominently marked by so-called photon dominated regions (PDR). My research goal is to contribute to a better understanding of the physics and the chemistry in PDRs. If we really want to understand planet and star formation we need to be able to reliably interpret the emission from PDRs. One of my main instruments of choice to achieve this goal is numerical modelling and I am the leading German expert on the numerical modelling of PDRs.
Models are not just a tool to better understand your data. They can be a tool to better understand the physics of the universe. PDR Modelling in particular is crucial in interpreting observations of the interstellar medium (ISM) because all neutral atomic hydrogen gas and a large fraction of the molecular gas in the Milky Way external galaxies lie in PDRs.

## The Vision

Stars and planets are formed from interstellar clouds of gas and dust. To fully understand the formation and the evolution of a stellar system, e.g. the solar system, we need to know their detailed initial conditions, i.e. the physical and chemical state of the original interstellar cloud.

I envision a time where our understanding of the physical and chemical processes in the interstellar medium (ISM) has reached a state that allows to consistently interpret the emission of atomic and molecular gas and of the dust. This is the key to a better understanding of fundamental topics, such as star and planet formation, and to answer fundamental questions such as: Under what conditions do habitable worlds form? What is the origin of the large reservoir of terrestrial water and why are other planets in the solar system lacking it?

Presently, we are far from this goal: We have difficulties to observationally disentangle the emission from different phases of the ISM, partly because we have only limited information on the local geometry. We lack the laboratory data to characterize many key components of the dominant astrochemistry and the important microphysical processes. On the other hand, our detector capacities are continuously growing. Modern instruments are more and more often designed to perform large survey observations. The expected astronomical data volume is gigantic. By way of contrast, the growth in modelling capacity is minor and the gap is widening. We need to invest in high-quality models in order to make good use of the observational data.

Models of photon dominated regions (PDRs) link the geometry of the ISM to its microphysics and are therefore the perfect numerical tool to study their interaction with star formation. However, PDR research is no scientific niche but elementary to understanding star formation, the ISM and consequently, the evolution of the Milky Way and other galaxies. Numerical models are the key to a better understanding of the universe and we need a dedicated effort to improve modern PDR modelling capabilities and to push their application in the analysis of modern astronomical data.

## Models of Photodissociation Regions (PDRs)

PDR modeling is my main focus. I am responsible for supporting and developing the KOSMA-τ PDR code and its applications.  KOSMA-τ features a spherical geometry with isotropic FUV illumination and was part of the large PDR Comparison Benchmark (Röllig et al. 2007). The code is a further development of the plane-parallel PDR code from A. Sternberg, Tel Aviv, and has originally been built to study the C+ - C - CO stratification in PDRs. We constantly update the code and expand its capabilities. Present development projects include the inclusion of a much more refined dust treatment by coupling KOSMA-τ with a full dust radiative transfer code by R. Szczerba, Torun. This will provide the full continuum properties of the model clouds including observable SED's given any dust composition. Additionally, we will also include the stochastic photo-heating of the very small grains (VSG's), which is bealived to be an important contribution to the total energy balance of the cloud.

The spherical model geometry is perfectly suited to be applied in modeling clumpy ensembles of many individual clumps (Cubick et al. 2008).

### 2-Clumpy PDR Commponents in DR 21

Herschel/HIFI observations provided the full range of far infrared (FIR) cooling lines in DR21. For DR 21 two ensembles with different properties have to be superimposed, a hot component, close to the inner HII region with strong FUV illumination, but only a small fraction of the total mass (orange clumps in the Figure), and a cooler component that provides the bulk of the material (beige clumps in Figure).

 This two ensemble fit is able to reproduce all observed lines. We find no evidence for shock-heated material, in agreement with Lane et al. (1990). This seems to be in contradiction with the line profiles that show excited outflow material.

<img align="right" src="/images/research/clumpyDR21.jpg" width="30%" />
Figure: Examplary realisation of a two-ensemble model configuration. All dimensions are plotted true to scale. The position of the central OB cluster is indicated by a blue sphere. The edge of the surrounding HII region is shown by the red wireframe sphere. The hot component clumps are shown as orange spheres. They populate the inner shell. The cool component clumps are shown in beige populating the outer shell. All clumps are randomly positioned and assumedly embedded in a diffuse inter-clump gas.


## Publications

{% assign sorted-publications = site.publications | where: "tags","massiveSF" %}
{% assign sorted-publications2 = sorted-publications | where: "tags","kosma-tau" %}
{% for post in sorted-publications2 reversed %}
    {% include archive-single.html %}
{% endfor %}
