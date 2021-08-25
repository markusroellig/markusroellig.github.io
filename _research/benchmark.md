---
title: "The PDR Comparison Benchmark"
collection: research
category: data
order_number: 10
layout: archive
excerpt: "<img src='/images/research/benchmark-quer.jpg'>"
header:
  og_image: "research/benchmark-quer"
---
<img align="right" src="/images/research/title2.gif" width="100%" />

Photon Dominated Regions (PDRs) play an important role in modern astrophysics as they are responsible for many emission characteristics of the ISM, and dominate the infrared and sub-millimeter spectra of star forming regions and galaxies as a whole. Theoretical models addressing the structure of PDRs have been available for approximately 30 years and have evolved into advanced computer codes accounting for a growing number of physical effects with increasing accuracy.

These codes have been developed with different goals in mind: some are geared to efficiently model a particular type of region, e.g. HII regions, protoplanetary disks, planetary nebulae, diffuse clouds, etc.; others emphasize a strict handling of the micro-physical processes in full detail (e.g. wavelength dependent absorption), but at the cost of increased computing time. Yet others aim at efficient and rapid calculation of large model grids for comparison with observational data, which comes at the cost of pragmatic approximations using effective rates rather than detailed treatment. As a result, the different models have focused on the detailed simulation of different processes determining the structure in the different regions while using only rough approximations for other processes. The model setups vary greatly among different model codes. This includes the assumed model geometry, their physical and chemical structure, the choice of free parameters, and other details. Consequently it is not always straightforward to directly compare the results from different PDR codes. Taking into account that there are multiple ways of implementing physical effects in numerical codes, it is obvious that the model output of different PDR codes can differ from each other. As a result, significant variations in the physical and chemical PDR structure predicted by the various PDR codes can occur.

This divergency would prevent a unique interpretation of observed data in terms of the parameters of the observed clouds. Several new facilities such as Herschel, SOFIA, APEX, ALMA, and others will become available over the next years and will deliver many high quality observations of line and dust continuum emission in the sub-millimeter and FIR wavelength regime. Many important PDR tracers emit in this range (\[CII\] (158µm), \[OI\] (63 and 146 µm), \[CI\] (370 and 610 µm), CO (650, 520, ..., 57.8 µm), H<sub>2</sub>O, etc.). In order to reliably analyze these high quality data we need a set of high quality tools, including PDR models that are well understood and properly debugged. As an important preparatory step toward these missions an international cooperation between many PDR model groups was initialized. The goals of this PDR-benchmarking were:

* to understand the differences in the different code results
* to obtain (as much as possible) the same model output with every PDR code when using the same input
* to agree on the correct handling of important processes
* to identify the specific limits of applicability of the available codes

To this end, a [PDR-benchmarking workshop](http://www.lc.leidenuniv.nl/lc/web/2004/105/info.php3?wsid=105) was held at the [Lorentz Center](https://www.lorentzcenter.nl) in Leiden, Netherlands in 2004 to jointly work on these topics

Here we present the results from this workshop and the results originating from the follow-up activities.

[PDR Comparison Archive](https://lecture.ph1.uni-koeln.de/pdr-comparison/){: .btn--research}

## Publications

{% assign sorted-publications = site.publications | where: "tags","data" %}
{% assign sorted-publications2 = sorted-publications | where: "tags","benchmark" %}
{% for post in sorted-publications2 reversed %}
    {% include archive-single.html %}
{% endfor %}
