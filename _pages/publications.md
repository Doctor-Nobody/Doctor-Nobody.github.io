---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}


The full list of my publications can be found on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
