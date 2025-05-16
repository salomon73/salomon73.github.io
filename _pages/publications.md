---
layout: page
permalink: /Publications/
title: Publications 
nav: true
nav_order: 1
---

<div class="publications">

{{ "## Journal Publications" | markdownify }}
{% bibliography --query @*[keywords~=publication] %}

{{ "## Conference Papers" | markdownify }}
{% bibliography --query @*[keywords~=conference] %}

</div>
