---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

[Link to my GoogleScholar profile](https://scholar.google.com.au/citations?user=JDBDDEgAAAAJ&hl=en)

### Data-driven multi-body dynamics

<div class="publications">
  {% bibliography --group_by none --query @*[dyn=true]* %}
</div>

### Robot design

<div class="publications">
  {% bibliography --group_by none --query @*[des=true]* %}
</div>

### Navigation and control

<div class="publications">
  {% bibliography --group_by none --query @*[nav=true]* %}
</div>
