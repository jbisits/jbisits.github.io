---
permalink: /publications/
title: "Publications and presentations"
toc: true
header:
  overlay_color: "#333"
---

## Publications

{% bibliography --file papers --template%}

## Oral presentations

{% bibliography --file presentations --query @*[addendum=Oral presentation]  --template%}

## Poster presentations

{% bibliography --file presentations --query @*[addendum=Poster presentation]  --template%}
