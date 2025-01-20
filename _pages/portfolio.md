---
layout: archive
#title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

# Non-academic projects
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

# Academic projects
Working paper versions and replication packages are available in the linked detailed project descriptions. 

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}
