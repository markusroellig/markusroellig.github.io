---
title: "GEco - Elemental feedback of massive star formation"
collection: research
category: elements
order_number: 10
layout: archive
excerpt: "<img src='/images/research/CrabNebula-480x630.png' alt=''>"
header:
  og_image: "research/CrabNebula-480x630.png"
---

[“Galactic Ecology”](http://www.ccatobservatory.org/index.cfm/page/science/science-facts/galactic_ecology.htm) studies in multiple spectral lines the dynamic interstellar medium in a wide range of environments in the Milky Way, the Magellanic Clouds and other nearby galaxies. Spectral large-scale mapping with CHAI of fine structure and mid- to high-excitation CO lines are at the core of the my research interests and activities as they trace the flows and accumulation of gas into cores and young stars.

<img align="right" src='/images/research/CrabNebula-480x630.png' width='400'> I am PI of the GEco science case ‘Chemical Feedback in the Milky Way’ on the [CCAT-prime/FYST](http://www.ccatobservatory.org/) telescope in Chile. it is the second highest telescope in the world and will give the best transmission of any radio telescope. This project is granted more than 4100 hrs. observing time to perform an unbiased survey of the Milky Way in important atomic and molecular cooling lines. These data can then be combined and correlated with complementary studies of elemental abundance variation across the Milky Way from UV absorption studies and from stellar spectroscopy. It will allow to study questions such as: is the detailed elemental variation across the Galaxy traced by the different phases of the ISM? What are good tracers? What are spatial scales of these variations and do we detect similar variations in the chemical evolution of molecular clouds?

To answer these questions, we need sophisticated models (Röllig, Szczerba, & Ossenkopf, 2013) and calibrating these models is only possible with an observational data set that covers a large portion of the relevant parameter ranges. This long-time project will offer many exciting and beneficial research opportunities particularly for students and young researchers. Learning observational astrophysics from the experts and being part of a large international consortium is a very valuable experience. Analyzing large surveys is a complex endeavor and modern data analysis methods and machine learning techniques will be of enormous importance. We already gained a lot of experience using unsupervised machine learning techniques, such as principal component analysis (PCA) and others to improve the data reduction performance for data from the upGREAT heterodyne instrument onboard the Stratospheric Observatory for Infrared Astronomy (SOFIA). But this is just the tip of the iceberg and will be mandatory for the big data astronomy that we are embarking on in GEco.

[GEco Project Page](http://www.ccatobservatory.org/index.cfm/page/science/science-facts/galactic_ecology.htm){: .btn--research}

## Publications

{% assign sorted-publications = site.publications | where: "tags","low-Z" %}
{% for post in sorted-publications reversed %}
    {% include archive-single.html %}
{% endfor %}
