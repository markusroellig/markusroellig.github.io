---
title: "KOSMA-tau"
collection: research
category: modelling
order_number: 40
layout: archive
excerpt: "<img src='/images/research/clump-2.png' alt=''>"
header:
  og_image: "research/clump-2.png.jpg"
---

*Keywords:* photon dominated regions, astrochemistry, physics of the interstellar medium, numerical simulation

<img align="right" src="/images/research/kosma-tau-1.png"/>
# KOSMA-tau - The Cologne PDR code

KOSMA-tau is a numerical code to compute the physical and chemical structure of a spherical molecular cloud, a so called photo-dissociation region (PDR). This code has been developed from an earlier PDR code, written by A. Sternberg from Tel Aviv University in Israel (Sternberg & Dalgarno 1989; Sternberg & Dalgarno 1995). His original code uses a plane-parallel geometry and was updated to employ spherical geometry (Gierens, Stutzki and Winnewisser 1992; Köster et al. 1994; Störzer, Stutzki and Sternberg 1996; Zielinsky, Stutzki & Störzer 2000).

## The main blocks of the problem to be solved

<img  src="/images/research/pdr-numerical-scheme.png"  />
+ Chemistry: Solving the chemical problem is equivalent to solving a nonlinear system of rate equations, one equation for each chemical species that is included in the model. The rate equation included all formation and destruction reactions of this particular species.
* Energy balance: Solving the energy balance means balancing all heating and cooling processes to derive the local kinetic gas (and dust) temperature.
* Level population: Solving the excitation problem, i.e. compute the energy level population of species that are relevant for the energy balance and for the emission of the model clump. This is again a system of nonlinear rate equations where all populating and de-populating processes, such as collisions and radiative decays, are included (one rate equation per energy level).
* Radiative transfer: The radiative transfer computes the emission and absorption processes along a line-of-sight through the model cloud. This brings geometry into play and couples remote cloud volumes with each other, i.e. couples the physical and chemical conditions of different parts of the cloud together.

The different 'blocks' in the mentioned scheme depend on each other which makes an iterative solution necessary. The result is a the chemical and physical structure of the model cloud as a function of radius.

## Model features

* spherical geometry, isotropic FUV illumination
* modular chemistry including carbon and oxygen isotopes (Standard database: [UDfA 2012](http://udfa.ajmarkwick.net/)) user selects species, code selects reactions, creates conservation equations and computes Jacobian
  * update to the fractionation reaction from Langer et al. 84 ([Mladenovic & Roueff,2014](http://adsabs.harvard.edu/abs/2014A%26A...566A.144M))
  * isotopic reaction set ([Röllig et al. 2013](http://adsabs.harvard.edu/abs/2013A%26A...550A..56R))
  * reactions with vibrationally excited H<sub>2</sub><sup>*</sup> to overcome activation energy barrier
  * CH<sup>+</sup> and SH<sup>+</sup> formation enhanced due to rotationally excited H<sub>2</sub> ([Agundez et al. 2010](http://adsabs.harvard.edu/abs/2010ApJ...713..662A), [Nagy et al. 2013](http://adsabs.harvard.edu/abs/2013A%26A...550A..96N))
  * cyclic and linear-isomers included (new branching ratios from [Chabot et al. 2013](http://adsabs.harvard.edu/abs/2013ApJ...771...90C)) with all isotopologues
    * l-C<sub>3</sub>H<sub>3</sub>,  l-C<sub>3</sub>H<sub>2</sub>, l-C<sub>2</sub>H<sub>2</sub>, l-C<sub>3</sub>H
  * Fluorine chemistry ([Neufeld et al. 2005](http://adsabs.harvard.edu/abs/2005ApJ...628..260N))
  * Photodissociation of CS<sub>2</sub>, N<sub>2</sub>O ([van Dishoeck et al.](http://home.strw.leidenuniv.nl/~ewine/photo/))
  * H2 formation
    * Chemi- & physisorption ([Cazaux & Tielens 2002](http://adsabs.harvard.edu/abs/2002ApJ...575L..29C), [2004](http://adsabs.harvard.edu/abs/2004ApJ...604..222C), [2010](http://adsabs.harvard.edu/abs/2010ApJ...715..698C))
* Full Surface Chemistry Upgrade
  * Coupling of gas-phase and surface chemistry
  * Steady-state chemistry
  * Rate equation approach ([Hasegawa et al. 1992](http://adsabs.harvard.edu/abs/1992ApJS...82..167H), [1993](http://adsabs.harvard.edu/abs/1993MNRAS.263..589H))
  * Processes included:
    * adsorption (only neutrals, no sticking of H2)
    * desorption only from 2 top layers ([Aikawa et al. 1996](http://adsabs.harvard.edu/abs/1996ApJ...467..684A))
      * thermal desorption (binding energies from UDfA + updates)
      * photo-desorption(photo cross-section like gas-phase)photo-dissociative desorption(eg.JH2O + hν → OH + H [Andersson+ 08](http://adsabs.harvard.edu/abs/2008A%26A...491..907A))
      * photo-dissociation on grains (equivalent to gas-phase)
      * CR inducedphoto-desorption/diss. ([Hasegawa & Herbst 1993](http://adsabs.harvard.edu/abs/1993MNRAS.263..589H))
      * H2-formation induceddesorption ([Willacy et al. 1994](http://adsabs.harvard.edu/abs/1993MNRAS.260..635W), [2007](http://adsabs.harvard.edu/abs/2007ApJ...660..441W))
      * chemistry induced desorption ([Minissale et al. 2015](http://adsabs.harvard.edu/abs/2015A%26A...577A...2M), [Cazaux et al. 2015](http://adsabs.harvard.edu/abs/2016A%26A...585A..55C))
    * surface-surfaceprocesses([Langmuir-Hinshelwood](https://en.wikipedia.org/wiki/Heterogeneous_catalysis))
* applicable to clumpy environments  (see [Cubick et al. (2008)](http://adsabs.harvard.edu/abs/2008A%26A...488..623C))
* full continuum radiative transfer
* complex dust properties (e.g. [Weingartner & Draine 2001](http://adsabs.harvard.edu/abs/2001ApJ...548..296W) size distribution, [full description in Röllig et al. (2013)](http://adsabs.harvard.edu/abs/2013A%26A...549A..85R))
* optimized for large parameter space surveys
* fully benchmarked in the [PDR Comparison Benchmark](https://zeus.ph1.uni-koeln.de/site/pdr-comparison/benchmark.htm)


[Project Page Cologne](https://astro.uni-koeln.de/stutzki/research/kosma-tau){: .btn--research}
[Summary Article](https://ui.adsabs.harvard.edu/abs/2013A&A...549A..85R){: .btn--research}
## Publications

{% assign sorted-publications = site.publications | where: "tags","kosma-tau" %}
{% for post in sorted-publications reversed %}
    {% include archive-single.html %}
{% endfor %}
