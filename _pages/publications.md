---
permalink: /publications/
title: "Publications and presentations"
toc: true
header:
  overlay_color: "#333"
---

## Publications

{% bibliography --file papers%}

## Selected oral presentations

{% bibliography --file presentations --query @*[addendum=Oral presentation]%}

## Selected poster presentations

{% bibliography --file presentations --query @*[addendum=Poster presentation] %}
