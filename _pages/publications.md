---
layout: page
permalink: /Research/
title: Research
nav: true
nav_order: 1
---

<div class="Preprints">
{% bibliography --query @*[keywords~=preprint] %}
</div>

# Publications

<div class="Publications">
{% bibliography --query @*[keywords~=publication] %}
</div>


# Conferences

<div class="Conferences">
{% bibliography --query @*[keywords~=conference] %}
</div>


