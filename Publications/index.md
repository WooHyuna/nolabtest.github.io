---
title: Publications
nav:
  order: 1
  tooltip: Published works
---

# 📰 Publications

International/Domestic Journal/Books/Reports/Articles

{% include section.html %}

## All Publications

{% include search-box.html %}

{% include search-info.html %}

{% for item in site.data.publications %}
  {% include citation.html
    title=item.title
    authors=item.authors
    link=item.link
    journal=item.journal
    style="rich"
  %}
{% endfor %}
