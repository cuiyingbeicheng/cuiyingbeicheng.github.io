---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 3
---

<p class="page-intro">My work spans statistical methodology and collaborative biomedical research. Topics include survival analysis, precision medicine, clinical trials, medical devices, biomedical AI, and reproducible health-data science.</p>

<div class="publications">
<section class="publication-group">
  <h2 class="publication-group-title">Statistical Methods&ndash;Oriented Publications</h2>
  {% bibliography --group_by none --query @*[category=methods] %}
</section>

<section class="publication-group">
  <h2 class="publication-group-title">Biomedical and Public Health Collaboration&ndash;Oriented Publications</h2>
  {% bibliography --group_by none --query @*[category=collaborative] %}
</section>

<section class="publication-group">
  <h2 class="publication-group-title">Conference Abstracts</h2>
  {% bibliography --group_by none --query @*[category=abstracts] %}
</section>
</div>
