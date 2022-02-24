---
layout: page
title: Ocean Wellbeing Workshop
---
# Speakers and Panelists

# Organizing Committee

{% for p in site.data.speakers %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}
