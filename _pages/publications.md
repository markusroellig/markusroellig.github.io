---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

My publication list at [NASA astrophysics data system](https://ui.adsabs.harvard.edu/search/filter_database_fq_database=AND&filter_database_fq_database=database%3A%22astronomy%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(database%3A%22astronomy%22)&p_=0&q=%20author%3A%22R%C3%B6llig%2C%20M.%22%20NOT%20%22KATRIN%22&sort=date%20desc%2C%20bibcode%20desc) and  [Google Scholar](https://scholar.google.com/citations?user=Cv6I6lYAAAAJ&hl=de).

# Refereed publications
Jump directly to [Non-refereed publications](#non-refereed-publications)
 
{% for post in site.publications reversed %}
  {% if post.refereed == 'yes' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<hr style="border-top: 8px solid #bbb; border-radius: 5px"> 


# Non-refereed publications
Jump back to [Refereed publications](#refereed-publications)
	
{% for post in site.publications reversed %}
  {% if post.refereed == 'no' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
