---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a full list of my publications on [my ADS Library][tlu-ads].

[tlu-ads]: https://ui.adsabs.harvard.edu/search/p_=0&q=docs(library%2Fw1612yBmSPmrRy2smeA3ow)&sort=date%20desc%2C%20bibcode%20desc

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
