---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc' and status=='active'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and status=='active'"   %}
{% include list.html data="members" component="portrait" filter="role == 'vphd' and status=='active'"   %}
{% include list.html data="members" component="portrait" filter="role == 'master' and status=='active'"   %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and status=='active'"  %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-bugs" %}Furry Commensals

{% include list.html data="members" component="portrait" filter="role == 'furry-commensal'"  %}
{% include list.html data="members" component="portrait" filter="role == 'furry-commensals'"  %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-person-hiking" %}Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumn'"  %}
