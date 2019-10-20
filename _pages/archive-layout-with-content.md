---
title: "Archive Layout with Content"
layout: archive
permalink: /archive-layout-with-content/
---

{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}
