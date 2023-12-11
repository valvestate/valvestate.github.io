---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can also find my articles on <u><a href="{https://scholar.google.com/citations?user=a_49dn0AAAAJ&hl=en}">my Google Scholar </a></u> and <u><a href="{https://dblp.uni-trier.de/pid/227/1165.html}"> DBLP pages</a></u>



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
