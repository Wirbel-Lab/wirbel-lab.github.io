---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'","status!='alumn'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'","status!='alumn'"   %}
{% include list.html data="members" component="portrait" filter="role == 'vphd'","status!='alumn'"   %}
{% include list.html data="members" component="portrait" filter="role == 'master'","status!='alumn'"   %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'","status!='alumn'"  %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-bugs" %}Furry Commensals

{% include list.html data="members" component="portrait" filter="role == 'furry-commensal'"  %}
{% include list.html data="members" component="portrait" filter="role == 'furry-commensals'"  %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-person-hiking" %}Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumn'"  %}
