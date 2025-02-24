---
title: Publications
nav:
  order: 1
  tooltip: Published works
---

# 📰 Publications
<div style="text-align: center; font-size: 1.1em;">
  International/Domestic Journal/Books/Reports/Articles
</div>

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
