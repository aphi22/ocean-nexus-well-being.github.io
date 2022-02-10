---
layout: page
title: AI for Public Health
use-site-title: true
---

# Overview
**Update: the deadline for submissions is extended to March 3 (AoE)**

The COVID-19 pandemic has cast a spotlight on the importance of public health. Even beyond this current emergency, public health is an essential component of population-level wellbeing. Topics such as infectious disease surveillance and control, preventative health, behavioral and mental health, maternal and child wellbeing, and more all play a crucial role in society. Moreover, a range of applications in public health benefit from careful use of data to uncover outbreak dynamics, learn patterns of behavior, optimize the design of interventions, and more. The science of machine learning in a public health context is still rapidly developing, and our aim is to build a community encompassing researchers based in both machine learning and public health to address these shared questions.


| ------------- |:-------------:|
| **Submission** | March 3rd, 2021   |
| **Notification** | March 26th, 2021 |
| **Workshop** | May 7th, 2021 |


<hr>

# Speakers and Panelists
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


