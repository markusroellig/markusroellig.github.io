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


## Models of Photodissociation Regions (PDRs)

PDR modeling is my main focus. I am responsible for supporting and developing the KOSMA-τ PDR code and its applications.  KOSMA-τ features a spherical geometry with isotropic FUV illumination and was part of the large PDR Comparison Benchmark (Röllig et al. 2007). The code is a further development of the plane-parallel PDR code from A. Sternberg, Tel Aviv, and has originally been built to study the C+ - C - CO stratification in PDRs. We constantly update the code and expand its capabilities. Present development projects include the inclusion of a much more refined dust treatment by coupling KOSMA-τ with a full dust radiative transfer code by R. Szczerba, Torun. This will provide the full continuum properties of the model clouds including observable SED's given any dust composition. Additionally, we will also include the stochastic photo-heating of the very small grains (VSG's), which is bealived to be an important contribution to the total energy balance of the cloud.

The spherical model geometry is perfectly suited to be applied in modeling clumpy ensembles of many individual clumps (Cubick et al. 2008).

<img align="left" src="/images/research/pdr-ngc3603-small.jpg" width="50%" />
*Figure left: This HST picture of NGC 3603 illustrates the typical PDR situation. The FUV radiation of the massive OB stars ionizes the surrounding ISM;and creates a HII region. On its way farther out, the FUV photons are absorbed and the FUV intensity decreases. Once the hydrogen recombination probability overcomes the ionization probability atomic and molecular material can exist. The transition from the ionized to the atomic/molecular region is called PDR interface or transition region. Credit: Wolfgang Brandner (JPL/IPAC), Eva K. Grebel (Univ. Washington), You-Hua Chu (Univ. Illinois Urbana-Champaign), and NASA*

## Clumpy PDRs

The current development of the KOSMA-τ PDR-model is coordinated through project C1 of the SFB 956. We simulate a clumpy medium by the principle of superposition, i.e. we compose the clumpy cloud from a variety of identical 'building block' according to certain distribution properties. Using full size distributions of clumps we can mimick the fractal structure of the molecular gas in star-forming regions.

<img align="left" src="/images/research/tau-ensembles.png" width="30%" />
*Figure left: [CII] optical depth distribution in a clumpy ensemble. The radiative transfer through the ensemble cannot be described by the average optical depth. Every cell in the 3D PDR model is composed of an ensemble similar to the shown one.*

As test case we use the Orian Bar PDR to turn the above idea into a full model framework. The results are published in the PhD Thesis by Dr. Silke Andree-Labsch and in Andree-Labsch et al. (2016). (astro-ph)

As the KOSMA-τ PDR code only models individual spherical clumps, additional effort is needed to simulate the full complex structure of clumpy and filamentary molecular clouds in the vicinity of young stars. In previous approaches this was simply done by the superposition of an ensemble of clumps mimicking a fractal structure (Cubick et al. 2008). A proper treatment, however, has to take radiative transfer effects into account, in particular for the optically thick  lines of CII and OI observed by Herschel and in future by SOFIA in configurations like the Orion Bar PDR. Existing plane-parallel PDR models always fail to explain the observed stratification of this region when fitting the line intensities. We implemented an extension of the KOSMA-t model by assembling a full three-dimensional model of the Orion Bar from an ensemble of clumps with an appropriate mass spectrum, immersed in a thin inter-clump medium, including the effects of FUV and FIR radiative transfer.

This model provides for the first time a self-consistent picture of the stratification structure of the Orion Bar PDR simultaneously fitting the line intensities and the relative spatial shifts of the emission profiles. The 3D clump-ensemble model (KOSMA-τ-3D) is defined in a flexible way so that it is planned to be applied to many more regions with more complex structures such as M17SW and whole starburst galaxies or the Milky Way.

<img align="left" src="/images/research/csm_orion_model.png" width="100%" />


### 2-Clumpy PDR Commponents in DR 21
<img align="right" src="/images/research/clumpyDR21.jpg" width="40%" />
Herschel/HIFI observations provided the full range of far infrared (FIR) cooling lines in DR21. For DR 21 two ensembles with different properties have to be superimposed, a hot component, close to the inner HII region with strong FUV illumination, but only a small fraction of the total mass (orange clumps in the Figure), and a cooler component that provides the bulk of the material (beige clumps in Figure).

 This two ensemble fit is able to reproduce all observed lines. We find no evidence for shock-heated material, in agreement with Lane et al. (1990). This seems to be in contradiction with the line profiles that show excited outflow material.

*Figure: Examplary realisation of a two-ensemble model configuration. All dimensions are plotted true to scale. The position of the central OB cluster is indicated by a blue sphere. The edge of the surrounding HII region is shown by the red wireframe sphere. The hot component clumps are shown as orange spheres. They populate the inner shell. The cool component clumps are shown in beige populating the outer shell. All clumps are randomly positioned and assumedly embedded in a diffuse inter-clump gas.*

## Future Developments

The main work goes into the improved modelling of the microphysical and chemical processes in the KOSMA-tau PDR model. This means in particular accounting for non-stationary effects:

* to include the full time-dependent chemistry to the model. This will allow to model the impact of :
  * ice evaporation
  * advection flows
  * progressing ionization fronts, and
  * turbulent mixing

Markus Röllig and Yoko Okada are Co-Investigators of the ERS project "Radiative Feedback from Massive Stars as Traced by Multiband Imaging and Spectroscopic Mosaics".

* As preparation for the launch of [JWST](https://www.jwst.nasa.gov/), we are updating KOSMA-tau to solve the full H2 problem (full ro-vib structure). In addition we need to account for non-stationary PAH heating. This is work in progress.
* KOSMA-tau results will be made available on the [PDR model database ISMDB](http://ismdb.obspm.fr/) of the Meudon group in order to allow a comparison between both models.

[Project page in Cologne](https://astro.uni-koeln.de/stutzki/research/pdr){: .btn--research}


## Publications

{% assign sorted-publications = site.publications | where: "tags","massiveSF" %}
{% assign sorted-publications2 = sorted-publications | where: "tags","kosma-tau" %}
{% for post in sorted-publications2 reversed %}
    {% include archive-single.html %}
{% endfor %}
