---
permalink: /
title: "About"
author_profile: true
---

Hello, I am **Ke Li**, a second-year master's student at the School of Software Technology, Zhejiang University. I expect to graduate in 2028. I am currently interning at ByteDance.

My research interests include deep learning and model compression. You can also find my work on [Google Scholar](https://scholar.google.com/citations?user=ZSc1khwAAAAJ&hl=en).

## Publications

<div class="publication-list">
{% if site.publications.size > 0 %}
  {% for post in site.publications reversed %}
    {% include publication-compact.html %}
  {% endfor %}
{% endif %}
</div>
