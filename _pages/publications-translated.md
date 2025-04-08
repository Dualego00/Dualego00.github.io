---
layout: translated-publications
title: "发表论文"
permalink: /publications-translated/
author_profile: true
---

您也可以在[我的Google Scholar主页](https://scholar.google.com/citations?user=o83AL3sAAAAJ&hl=en)上找到我的文章。

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %} 