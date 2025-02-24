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

{% assign publications_by_year = site.data.publications | group_by_exp: "pub", "pub.year" | sort: "name" | reverse %}

{% for year in publications_by_year %}
  <h3>{{ year.name }}</h3> <!-- 연도별 헤더 추가 -->
  {% for item in year.items %}
    {% include citation.html
      title=item.title
      authors=item.authors
      link=item.link
      journal=item.journal
      style="rich"
    %}
  {% endfor %}
{% endfor %}
