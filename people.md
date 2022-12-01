---
layout: page
title: Meet the Team
---
# Workshop Team

{% for p in site.data.workshopteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
{% endif %} {% endfor %}

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

<table>
  <tr class="row1">
    <td class="col1">
   {% for p in site.data.workshopteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
    </td>
    <td class="col2">
      {% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
    </td>
  </tr>
  <tr class="row2">
    <td class="col1">
      {% for p in site.data.addcollab %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
    </td>
    <td class="col2">
      {% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
    </td>
  </tr>
  <tr class="row3">
    <td class="col1">
      {% for p in site.data.coordinatingteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
    </td>
    <td class="col2">
      {% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
    </td>
  </tr>
</table>
