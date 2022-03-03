---
layout: page
title: Ocean Wellbeing Workshop
---
# Workshop Team

{% for p in site.data.workshopteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}

# Coordinating Team


{% for p in site.data.coordinatingteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}
