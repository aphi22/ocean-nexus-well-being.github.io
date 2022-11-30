---
layout: page
title: Ocean Well-being Workshop
---
# Workshop Team

{% for p in site.data.workshopteam %} {% if forloop.index<=4 %} {% capture id %}{{ p[1] }}{% endcapture %} {% include profile.html p=p %} {% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %} {% endif %} {% endfor %}
{% for p in site.data.workshopteam %} {% capture id %}{{ p[1] }}{% endcapture %} {% if forloop.index>4 and forloop.index<=10%} {% include profile.html p=p %} {% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %} {% endif %} {% endfor %}
{% for p in site.data.workshopteam %} {% capture id %}{{ p[1] }}{% endcapture %} {% if forloop.index>10%} {% include profile.html p=p %} {% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %} {% endif %} {% endfor %}

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
