---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

박사과정, 석사과정, 학부 연구생 모집합니다
We are looking for new PhD, Master, Bachelor students to join the team!

{%
  include button.html
  type="email"
  text="seongjin.noh@kumoh.ac.kr"
  link="seongjin.noh@kumoh.ac.kr"
%}
{%
  include button.html
  type="phone"
  text="(+82)-54-478-7621"
  link="(+82)-54-478-7621"
%}
{%
  include button.html
  type="address"
  tooltip="Room 302, Bldg. Global, Kumoh National Institute of Technology 61, Daehak-ro, Gumi-si, Gyeongsangbuk-do, Republic of Korea"
  link="https://www.google.com/maps](https://maps.app.goo.gl/hfpLMf7GiugaUHKC9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
