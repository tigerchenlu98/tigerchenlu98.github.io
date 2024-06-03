---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="wordwrap">You can find a full list of my publications on <a href="{{https://ui.adsabs.harvard.edu/search/q=docs(library%2Fw1612yBmSPmrRy2smeA3ow)&sort=date%20desc%2C%20bibcode%20desc&p_=0}}">NASA ADS</a>.</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
