---
layout: archive
title: "Lista de páginas"
permalink: /page-archive/
author_profile: false
---

{% for post in site.pages %}
  {% unless post.hidden %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}