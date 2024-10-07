---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:  "NAFO Armories"
image: assets/images/pride_100x100.png
---

# So, what do we do here?

Oh nothing much, we just supply the Ukrainian Armed Forces

We do both manufacturing as well as procurement for stuff like this

<div class="nafoarms-flex-row">

{% include stat_display.html stats=site.data.stats.overall_stats api="donations/get/total" api_id="total" title="Overall statistics" %}

{% include recent_donations.html %}

</div>

And we have many more on the way, and even more so when our small OEM line is at full capacity.

Currently we are operating at limited capacity.
