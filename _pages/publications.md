---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}


The full list of my publications can be found on [my Google Scholar profile](https://scholar.google.com.hk/citations?user=gMsIFuEAAAAJ).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
