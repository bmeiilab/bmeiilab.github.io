---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-graduation-cap" %}Team

## Professor
{% include list.html data="members" component="portrait" filter="role == 'professor'" %}

{% include section.html %}
## Students
{% include list.html data="members" component="portrait" filter="role == 'phd_student'" %}
{% include list.html data="members" component="portrait" filter="role == 'graduate_student'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergraduate_student'" %}
<!-- {% include list.html data="members" component="portrait" filter="role != 'pi'" %} -->

{% include section.html background="images/GGI_unjbw2unjbw2unjb.png" dark=true %}

{% include button.html icon="fa-solid fa-school-flag" text="Join the Team" link="contact" style="button" %}

{%- comment -%}
{% include section.html %}
## Alumni 
{% include list.html data="members" component="portrait" filter="role == 'bachelors_degree'" %}
{% include list.html data="members" component="portrait" filter="role == 'masters_degree'" %}
{% include list.html data="members" component="portrait" filter="role == 'doctor_degree'" %}
{%- endcomment -%}

{% include section.html %}
## Photos
{% capture content %}

{% include figure.html caption="Office" image="images/p_team/IMG_3522.png" %}
{% include figure.html caption="2024" image="images/p_team/IMG_6531.JPG" %}
{% include figure.html caption="2025" image="images/p_team/IMG_6532.JPG" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
