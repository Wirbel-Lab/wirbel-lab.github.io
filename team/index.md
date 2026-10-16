---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'vphd'" %}
{% include list.html data="members" component="portrait" filter="role == 'master'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-users" %}Furry Commensals

{% include list.html data="members" component="portrait" filter="role == 'fluffy-symbiont'"  %}
{% include list.html data="members" component="portrait" filter="role == 'fluffy-symbionts'"  %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="members" component="portrait" filter="status == 'alum'"  %}
