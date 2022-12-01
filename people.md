---
layout: page
title: Meet the Team
---
<style>
ul#display-inline-block-example,
ul#display-inline-block-example li {        
/* Setting a common base */         
margin: 0;
padding: 0;     }

ul#display-inline-block-example li {
    display: inline-block;
    width: 100px;
    min-height: 100px;
    background: #ccc;
} 
</style>

<ul id="display-inline-block-example">
<li>Item one</li>
<li>Item two</li>
<li>Item three</li>

## Workshop Team

{% for p in site.data.workshopteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
{% endif %} {% endfor %}

 
## Additional Collaborators

{% for p in site.data.addcollab %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
{% endif %} {% endfor %}
 
 
## Coordinating Team

{% for p in site.data.coordinatingteam %} {% if forloop.index<8 %}
{% capture id %}{{ p[0] }}{% endcapture %} {% include profile_contact.html p=p %}
{% capture id %}{{ p[1] }}{% endcapture %} {% include profile_detail.html p=p %}
{% endif %} {% endfor %}
