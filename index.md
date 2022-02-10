---
layout: page
title: Ocean Wellbeing Workshop
use-site-title: false
---

# Ocean Nexus
<iframe width="560" height="315" src="https://www.youtube.com/embed/O31CdTU92FE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Our Mission: To contribute to transforming ocean governance through scholarship, communication, and training a transdisciplinary and international network of researchers integrating human-centered tools, perspectives, evidence and narratives.

[Visit Ocean Nexus Center Website](https://oceannexus.uw.edu/)

<hr>

# Workshop Overview
**Objective:** The goal of the workshop is to encompass and understand a holistic approach to wellbeing for oceans 

## **Dates**

| ------------- |:-------------:|
| **Day 1**     | June 23, 2021 |
| **Day 2**     | June 24, 2021 |

## Speakers and Panelists
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

## Organizing Committee

<hr>

# Mentorship

To build a stronger community for AI for Public Health and to encourage collaborations between researchers in the field, 
we are hosting a Submission Mentorship Program. Through this program, our goal is to connect junior researchers 
(mentees) planning to submit to our workshop with experienced mentors who can provide them with constructive 
feedback and guidance on their work. We believe that such a mentorship scheme will also increase the impact and 
quality of the workshop submissions and foster future collaborations between the mentors and mentees.

| ----------------------------------------------- |:--------------------:|
| **Deadline for applying to be a mentor/mentee** | January 24th, 2021   |



<div class="container" style="margin-top: 20px;margin-bottom: 10px;">
<a href="mentorship">More Info</a>
</div>


<hr>

# Organizing Committee

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

# Advisory Committee

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <div class="row">
    {% for p in site.data.advisory %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>



<div class="container" style="margin-bottom: 10px;"></div>

<hr>


