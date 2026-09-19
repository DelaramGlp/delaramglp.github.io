---
permalink: /
title: "Delaram Golpayegani"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Selected Publications

{% assign key_pubs = site.publications | where_exp: "post", "post.category == 'key'" | sort: "order" %}
{% for post in key_pubs %}
  {% include archive-single.html %}
{% endfor %}

See the full list on the [Publications page](/publications/).
