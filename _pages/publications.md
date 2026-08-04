---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<p class="page-intro">My work spans statistical methodology and collaborative biomedical research. Topics include survival analysis, precision medicine, clinical trials, medical devices, biomedical AI, and reproducible health-data science.</p>

<div class="publications">
{% bibliography --query @*[year>=2022] %}

<h2 class="bibliography">Before 2022</h2>
{% bibliography --group_by none --query @*[year<2022] %}
</div>
