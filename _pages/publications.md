---
layout: page
permalink: /Publications/
title: 
nav: true
nav_order: 1
---

<div class="publications">

{{ "# Publications " | markdownify }}
{% bibliography --query @*[keywords~=publication] %}

{{ "# Conferences" | markdownify }}
{% bibliography --query @*[keywords~=conference] %}

</div>
