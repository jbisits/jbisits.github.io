---
permalink: /publications/
title: "Publications and presentations"
toc: true
# toc_label: "Research"
# toc_icon: "book-open"
---

## Publications

{% bibliography --file papers %}

## Oral presentations

{% bibliography --file presentations --query @*[addendum='Poster presentation'] %}

## Poster presentations

{% bibliography --file presentations --query @*[addendum='Poster presentation'] %}
