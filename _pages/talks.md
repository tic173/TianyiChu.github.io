---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---

## Talks

<div class="section-card" id="pubList">
<h3>Invited Talks</h3>

{% bibliography --query @incollection[keywords ^= invited] %}

<h3>Regular Talks</h3>

{% bibliography --query @incollection[keywords ^= regular] %}

<h3>Contributed Talks</h3>

{% bibliography --query @incollection[keywords ^= contribued] %}
</div>
