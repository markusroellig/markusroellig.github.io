---
title: "SOFIA Legacy program - FEEDBACK"
collection: research
category: massiveSF
order_number: 20
layout: archive
excerpt: "<img src='/images/research/sofia-feedback.png' alt=''>"
header:
  og_image: "research/s106_4.gif"
---


*Main investigor Cologne:*  [Nicola Schneider](https://hera.ph1.uni-koeln.de/~nschneid/).

*Main investigator University of Maryland/University of Leiden:* Alexander Tielens, [see Feedback](http://feedback.astro.umd.edu/index.html)

FEEDBACK is a SOFIA legacy project using the upGREAT heterodyne receiver to map the CII 158 micron line in Galactic molecular clouds. The observations will be carried out in Cycle 7 (2019) and Cycle 8 (2020).

We will study the interaction of massive stars with their environment in a sample of sources that span a range in stellar characteristics from single OB stars, to small groups of O stars, to rich young stellar clusters, to mini starbursts. The aim of these observations is to quantify the mechanical energy injection and radiative heating efficiency in regions dominated by these different processes (stellar winds, thermal expansion, radiation pressure).

This Legacy Program takes full advantage of the unique capabilities of the upGREAT/SOFIA combination: The high spatial (14") and spectral (sub-km/s) resolution of the 14 element upGREAT heterodyne spectrometer coupled with the nimble telescope of SOFIA allows for efficient mapping of the [CII] line over large areas. With a total observing time of 96h, we will cover ~6000 arcmin<sup>2</sup> in 11 prominent Galactic sources.

The [CII] line uniquely provides the kinematics of the gas exposed to the mechanical energy input by massive stars and therefore directly measures the mechanical energy injection into the medium. In addition, for low to moderate densities and UV fields, this line is the dominant cooling line of the gas, and observations then directly yield the radiative energy injection/heating efficiency of the gas. Thus, by surveying regions with a range of massive star formation activity, we will quantify the relationship between star formation activity and energy injection and the negative and positive feedback processes involved, and link that to other measures of activity on scales of individual massive stars, of small stellar groups, and of star clusters. These [CII] maps, together with the less explored [OI] 63μm line (observed in parallel), provide an outstanding data base for the community and will serve as a starting point for many studies and follow-up observations.

[Project Page Cologne](https://astro.uni-koeln.de/stutzki/research/feedback){: .btn--research}

## Publications

{% assign sorted-publications = site.publications | where: "tags","sofia-feedback" %}
{% for post in sorted-publications reversed %}
    {% include archive-single.html %}
{% endfor %}
