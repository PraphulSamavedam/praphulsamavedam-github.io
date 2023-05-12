---
layout: archive
title: "Work Experience"
permalink: /experiences/
author_profile: true
redirect_from:
  - /work experience/
  - /work.html
  - /experience.html
  - /corporateExperience.html
  - /corporate
  - /experiences/
  - /experience/
  - /work/
  - /corporate/
---

{% include base_path %}

{% for post in site.experiences reversed %}
  {% include archive-single.html %}
{% endfor %}