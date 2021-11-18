---
title: "Machine Learning and AI"
collection: research
category: modelling
order_number: 20
layout: archive
excerpt: "<img src='/images/research/data.png' width='230px' height='234px' alt=''>"
header:
  og_image: "research/data.png"
---

*Keywords:* computational astrophysics, machine learning, neural networks, ai, astrochemistry, numerics, scientific programming

## Summary

I recently became interested in current developments in the field of artificial intelligence (AI) and machine learning (ML) and their applications in astronomy and astrophysics. An obvious and fast developing area is the application of ML techniques in the (un)supervised classification of astronomical objects, such as supernovae ([Sasdelli, et al., 2016](https://ui.adsabs.harvard.edu/abs/2016MNRAS.461.2044S/abstract)), main sequence stars ([Bellinger, et al., 2016](https://ui.adsabs.harvard.edu/abs/2016ApJ...830...31B/abstract)), gravitational wave detection ([Gebhard, Kilbertus, Harry, & Schölkopf, 2019](https://ui.adsabs.harvard.edu/abs/2019PhRvD.100f3015G/abstract), [George & Huerta, 2018](https://ui.adsabs.harvard.edu/abs/2018PhRvD..97d4039G/abstract)) or galaxy morphology ([Dieleman, Willett, & Dambre, 2015](https://ui.adsabs.harvard.edu/abs/2015MNRAS.450.1441D/abstract)) and exoplanet identification ([Shallue & Vanderburg, 2018](https://ui.adsabs.harvard.edu/abs/2018AJ....155...94S/abstract)). However, neural networks are “general function approximators” and I am currently exploring their application in the context of numerical models of ISM physics and chemistry.

<img align="left" src="/images/research/machine-learning.png" width="40%" />
The capability of neural networks to invert time-varying matrices ([Tavakkoli, Chedjou, & Kyamakya, 2019](https://ui.adsabs.harvard.edu/abs/2019Senso..19.4002T/abstract)) and as a general matrix inverter ([Rohit Shukla, 2018](https://www.frontiersin.org/articles/10.3389/fnins.2018.00115/full)) demonstrates their potential. The group of Serena Viti from Leiden University recently presented CHEMULATOR, an approximator for astrochemical computations ([Holdship, Viti, Haworth, & Ilee, 2021](https://ui.adsabs.harvard.edu/abs/2021A%26A...653A..76H/abstract)) as a proof-of-concept but with yet unsatisfying accuracy. I am exploring how concepts from the field of natural language processing (NLP) such as context sensitive word representations in vector space such as word2vec ([Tomas Mikolov, 2013](https://arxiv.org/abs/1301.3781)) and GloVe ([Manning, 2014](https://nlp.stanford.edu/pubs/glove.pdf)) that tremendously accelerated NLP advances can large-scale magneto-hydrodynamical simulations is evident and will provide the means to advance the predictive
power of these simulations to unprecedented levels.

Obviously, there are many related applications in numerical models of the ISM, e.g. PDR models. Radiative transfer and molecular excitation computations come to mind immediately and I am planning the assess how recent ML developments can be integrated into these models. Machine learning will revolutionize astrophysical research and my recent activities contribute to the dedicated German research initiative on AI.







## Publications

{% assign sorted-publications = site.publications | where: "tags","machinelearning" %}
{% assign sorted-publications2 = sorted-publications | where: "tags","machinelearning" %}
{% for post in sorted-publications2 reversed %}
    {% include archive-single.html %}
{% endfor %}
