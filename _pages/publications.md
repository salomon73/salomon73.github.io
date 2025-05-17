---
layout: page
permalink: /Publications/
title: Publications
nav: true
nav_order: 1
---

<div class="publications">

<h2>Publications</h2>
{% bibliography --query @*[keywords~=publication] %}

<h2>Conferences</h2>
{% bibliography --query @*[keywords~=conference] %}


</div>
