---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %} Team

Professor, Team members and Alumni

{% include section.html %}

## Principal Investigator (PI)
{% include team_list.html filter="role == 'PI'" %}

## Team Members
{% include team_list.html filter="role != 'PI'" %}
