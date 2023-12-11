---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on my [**Google Scholar**](https://scholar.google.com/citations?user=a_49dn0AAAAJ&hl=en) and [**DBLP**](https://dblp.uni-trier.de/pid/227/1165.html) profiles.



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
