---
layout: page
title: bookmarks
---

## Bookmark

{% for link in site.data.bookmark %}
  [ {{ link.name }} ]({{ link.url }})
{% endfor %}

