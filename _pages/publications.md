---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-T0S164QJL9"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-T0S164QJL9');
</script>
{% include base_path %}


The full list of my publications can be found on [my Google Scholar profile](https://scholar.google.com.hk/citations?user=gMsIFuEAAAAJ).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


