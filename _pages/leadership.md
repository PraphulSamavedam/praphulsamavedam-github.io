---
layout: archive
title: "Leadership positions"
permalink: /leadership/
author_profile: true
redirect_from:
  - /lead/
  - /leadership.html
  - /leader.html
  - /lead.html
  - /leader
  - /leader/
---

{% include base_path %}

{% for post in site.leadership reversed %}
  {% include archive-single.html %}
{% endfor %}
