---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

연구실 멤버들을 소개합니다.

{% include section.html %}

## Principal Investigator (PI)

{% include team_list.html filter="role == 'pi'" %}

## Team Members

{% include team_list.html filter="role != 'pi'" %}
