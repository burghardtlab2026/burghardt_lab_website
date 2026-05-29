---
title: Team
nav:
  order: 2
---

## {% include icon.html icon="fa-solid fa-users" %}Current Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'lab-manager'" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alum'" %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
