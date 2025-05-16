---
layout: page
permalink: /Publications/
title:  Publications
nav: true
nav_order: 1
---

<div class="publications">

{% bibliography --query @*[keywords~=publication] %}

{{ "# Conferences" | markdownify }}
{% bibliography --query @*[keywords~=conference] %}

</div>
