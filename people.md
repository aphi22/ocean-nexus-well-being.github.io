---
layout: page
title: Ocean Well-being Workshop
---
## Workshop Team

<!-- prettier-ignore -->
<div class="container" style="margin-top: 20px;margin-bottom: 10px;">
  
  <div class="row">
  {% for p in site.data.coordinatingteam %}
  {% if forloop.index<=4 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% include profile_detail.html p=p %} 
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.coordinatingteam %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>4 and forloop.index<=10%}
  {% include profile.html p=p %}
  {% include profile_detail.html p=p %} 
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.coordinatingteam %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>10%}
  {% include profile.html p=p %}
  {% include profile_detail.html p=p %} 
  {% endif %}
  {% endfor %}
 </div>
</div>

## Additional Collaborators

{% for p in site.data.addcollab %} {% if forloop.index<8 %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}

## Coordinating Team


{% for p in site.data.coordinatingteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}

{% endif %} {% endfor %}
