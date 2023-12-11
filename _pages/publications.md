---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on my [**Google Scholar**](https://scholar.google.com/citations?user=a_49dn0AAAAJ&hl=en) and [**DBLP**](https://dblp.uni-trier.de/pid/227/1165.html) profiles. All of them are open access, or there is an unpaywalled version available. Please email me if you're struggling to download any of my papers. Thank you for showing interest in my work!



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
