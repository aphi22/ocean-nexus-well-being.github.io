---
layout: page
title: Ocean Wellbeing Workshop
use-site-title: true
---

# Ocean Nexus
Our Mission: To contribute to transforming ocean governance through scholarship, communication, and training a transdisciplinary and international network of researchers integrating human-centered tools, perspectives, evidence and narratives.

[Visit Ocean Nexus Center Website](https://oceannexus.uw.edu/)

<hr>

# Workshop Overview
**Objective:** The goal of the workshop is to encompass and understand a holistic approach to wellbeing for oceans 

### **Dates**

| ------------- |:-------------:|
| **Day 1**     | June 23, 2021 |
| **Day 2**     | June 24, 2021 |

### Speakers and Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 10px;">
  <div class="row">
  {% for p in site.data.speakers %}
  {% if forloop.index<=4 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>4 and forloop.index<=10%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>10%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
 </div>
</div>

<div class="container" style="margin-top: 40px;margin-bottom: 10px;">
<a href="speakers">More Info</a>
</div>

<hr>

### Organizing Committee

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 20px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>

\*primary contact: bryan.wilder0@gmail.com
<hr>


