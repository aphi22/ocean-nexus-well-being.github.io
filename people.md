---
layout: page
title: Ocean Well-being Workshop
---

<!-- prettier-ignore -->

<div class="container" style="margin-top: 20px;margin-bottom: 10px;">

# Workshop Team

{% for p in site.data.workshopteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}

# Additional Collaborators

{% for p in site.data.addcollab %} {% if forloop.index<8 %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}

# Coordinating Team


{% for p in site.data.coordinatingteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}
