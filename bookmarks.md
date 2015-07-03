---
layout: page
title: bookmarks
---

{% for link in site.data.bookmark %}
  [ {{ link.name }} ]({{ link.url }})
{% endfor %}

