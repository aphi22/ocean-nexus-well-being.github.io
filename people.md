---
layout: page
title: Meet the Team
---

<div id='content'>
   <div id='div-1'><!-- Contains table --></div>
   <div id='div-2'><!-- contains two more divs that require to be arranged one below other --></div>
 
# Workshop Team

{% for p in site.data.workshopteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
{% endif %} {% endfor %}

</div>





 
# Additional Collaborators

{% for p in site.data.addcollab %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
{% endif %} {% endfor %}
 
 
# Coordinating Team

{% for p in site.data.coordinatingteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
{% endif %} {% endfor %}
