---
layout: page
permalink: /publications/
title: publications
description: Research publications and preprints in Artificial Intelligence and Partial Differential Equations.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

<h3 class="mt-4">🤖 Artificial Intelligence & Machine Learning</h3>
{% bibliography -f papers -q @*[keywords~=ai]* %}

<hr class="my-5">

<h3 class="mt-4">📐 Partial Differential Equations & Applied Math</h3>
{% bibliography -f papers -q @*[keywords~=pde]* %}

</div>
