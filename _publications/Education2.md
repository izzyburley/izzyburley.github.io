---
layout: archive
title: "EDUCATION"
permalink: /education/
author_profile: true
---

{% for post in site.education reversed %}
  {% include plublications.html %}
{% endfor %}
