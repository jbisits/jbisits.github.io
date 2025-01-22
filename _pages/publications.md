---
permalink: /publications/
title: "Publications and presentations"
toc: true
header:
  overlay_color: "#333"
---

## Publications

{% bibliography --file papers -T%}

## Oral presentations

{% bibliography --file presentations --query @*[addendum=Oral presentation]  -T%}

## Poster presentations

{% bibliography --file presentations --query @*[addendum=Poster presentation]  -T%}
