---
layout: page
permalink: /Publications/
title: Publications 
nav: true
nav_order: 1
---

<div class="publications">

## Journal Publications
{% bibliography --query @*[keywords~=publication] %}

## Conference Papers
{% bibliography --query @*[keywords~=conference] %}

</div>
