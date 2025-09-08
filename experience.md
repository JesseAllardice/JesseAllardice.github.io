---
layout: page
title: Experience
permalink: /experience/
---

## Professional Experience

<div class="experience-grid">
  {% assign sorted_experience = site.experience | sort: 'start_date' | reverse %}
  {% for experience in sorted_experience %}
    {% unless experience.employment_type == 'Fellowship' or experience.employment_type == 'Residency' or experience.employment_type == 'Education' or experience.employment_type == 'Volunteering' %}
      {% include experience-card.html experience=experience %}
    {% endunless %}
  {% endfor %}
</div>

## Education & Training

<div class="experience-grid">
  {% assign sorted_experience = site.experience | sort: 'start_date' | reverse %}
  {% for experience in sorted_experience %}
    {% if experience.employment_type == 'Fellowship' or experience.employment_type == 'Residency' or experience.employment_type == 'Education' %}
      {% include experience-card.html experience=experience %}
    {% endif %}
  {% endfor %}
</div>

## Selected Awards

I received 1st place in the Winton Berkeley-Cambridge exchange's Research Proposal Competition. During my PhD, I was supported by scholarships from the Cambridge Trust, St. John's College, and the Winton Program for the Physics of Sustainability. As an undergraduate, I received the Victoria University Excellence Scholarship and was recognized as the Top Physics Student.

## Volunteering

<div class="experience-grid">
  {% assign sorted_experience = site.experience | sort: 'start_date' | reverse %}
  {% for experience in sorted_experience %}
    {% if experience.employment_type == 'Volunteering' %}
      {% include experience-card.html experience=experience %}
    {% endif %}
  {% endfor %}
</div>