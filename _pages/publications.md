---
layout: page
permalink: /Publications/
title: Publications 
description: 
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->
<div class="publications">

## Journal Publications
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=publication] %}

## Conference Papers
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=conference] %}

</div>
