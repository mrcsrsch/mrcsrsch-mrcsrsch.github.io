---
layout: archive
#title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Here I link my current and previous projects. The replication package of each project is linked under the detailed project description.

# Research projects
{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

# Other projects
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
