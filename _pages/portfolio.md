---
layout: archive
#title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

# Research projects
{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

# Other projects
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
