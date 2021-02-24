---
layout: archive
title: "CV"
permalink: /cv/
toc: true
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Education
======
* __Habilitation__ (postdoctoral lecture qualification) und venia legendi in Experimental Physics, Cologne University, Germany, Thesis: _Fortschritte in der numerischen Modellierung von Photo-Dissoziationsregionen_, 2013
* __Ph.D__, Institute for Theoretical Physics, Goethe-University Frankfurt, Germany, Supervisor: Prof. Dr. W.H. Kegel, Grade: "very good"  (magna cum laude),  Thesis: _Der Einfluss von turbulenten Str&ouml;mungen  auf die Photodissoziation von CO in interstellaren Wolken_, 2002
* __Physics Diploma__, Institute for Theoretical Physics, Goethe-University Frankfurt, Germany, Supervisor: Prof. Dr. W.H. Kegel,  Grade: "very good"  (outstanding) Thesis: _A-Typ Methanol Maser in interstellaren Molek&uuml;lwolken unter Ber&uuml;cksichtigung von IR/HII  Quellen und Linien&uuml;berlapp_, 1997


Work experience
======
* __2008 - present__ Senior Researcher, I. Physical Institute, Cologne University, Germany
* __2006 - 2007__    Post-Doc, Argelander-Institute for Astronomy, Bonn University, Germany
* __2003 - 2006__    Post-Doc, I. Physical Institute, Cologne University, Germany
* __2002__           Research Assistant (voluntary), Goethe-University Frankfurt, Germany
* __1998 - 2001__    PhD Student, Goethe-University Frankfurt, Germany


Research Expertise and Interests
======
* Research in observational galactic and extragalactic astrophysics
* Microphysics of the interstellar medium (ISM)
* Chemical and elemental evolution of the ISM
* Formation and evolution of stars and planets
* Data analysis of complex multi-dimensional & multi-wavelength data
* Numerical modelling and scientific programming
* Machine learning and KI in astronomy
* Astronomical observations in the Radio, IR, Far-IR and THz spectral regimes
* Research and project experience with space-based, airborne and terrestrial astronomical observatories
* Project experience in large-scale, multinational collaborations
* Radiative transfer
* CRC/SFB planning and application (total CRC 956 volume: 33 mil. EUR)


Refereed Publications
======

  <ul>
  {% for post in site.publications reversed %}
	{% if post.refereed == 'yes' %}
		{% include archive-single-cv.html %}
	{% endif %}
  {% endfor %}
  </ul>

Non-refereed Publications
======

  <ul>
  {% for post in site.publications reversed %}
	{% if post.refereed == 'no' %}
		{% include archive-single-cv.html %}
	{% endif %}
  {% endfor %}
  </ul>

Academic Talks
======
  <ul>
  {% for post in site.talks reversed %}
	{% if post.tag == 'academic' %}
		{% include archive-single-talk-cv.html %}
	{% endif %}
  {% endfor %}
  </ul>

Public Outreach Talks
======
  <ul>
  {% for post in site.talks reversed %}
	{% if post.tag == 'public' %}
		{% include archive-single-talk-cv.html %}
	{% endif %}
  {% endfor %}
  </ul>

Teaching at Frankfurt
======
  <ul>{% for post in site.teaching %}
  {% if post.venue == "Goethe-University Frankfurt, IAP" %}
    {% include archive-single-cv.html %}
  {% endif %}
  {% endfor %}</ul>

Teaching at Cologne
======
  <ul>{% for post in site.teaching %}
  {% if post.venue == "Cologne University, I. Physical Institute" %}
    {% include archive-single-cv.html %}
  {% endif %}
  {% endfor %}</ul>

Service and leadership
======
* Local Organizing Committee, 7th Chile-Cologne-Bonn-Symposium, 2022, 200+ participants, Puerto Varas, Chile
* Member: Bonn-Cologne Graduate School, H2-Grant review panel, 2016, Cologne, Germany
* Local Organizing Committee, 6-th Zermatt ISM-Symposium 2015, 250+ participants, Zermatt, Switzerland
* Member: Bonn-Cologne Graduate School, H2-Grant review panel, 2014, Bonn, Germany
* Local Organizing Committee, SOFIA Winter School 2014, 70 participants
* Referee for ANR: Agence Nationale de la Recherche (French national funding agency), France (2013) project volume: 4 yrs., 446035 EUR
* Editor: EAS Conference proceedings, 5th Zermatt ISM-Symposium 2010
* Local Organizing Committee, 5th Zermatt ISM-Symposium 2010, 250+ participants, Zermatt, Switzerland
