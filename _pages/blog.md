---
layout: archive
permalink: /blog/
title: "ionutmodo's Blog"
author_profile: true
pagination:
  enabled: true
---

{% include base_path %}
<!--{% capture written_year %}'None'{% endcapture %}-->
{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}
{% include paginator.html %}

