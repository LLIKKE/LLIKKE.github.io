---
permalink: /
title: "Welcome"
author_profile: true
---

## About Me

Hello, I am **Li Ke**. Welcome to my personal website.

This page presents a brief introduction and my academic publications. More details about my research interests, education, and contact information will be added soon.

## Publications

{% if site.publications.size > 0 %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
Publication information is being updated.
{% endif %}
