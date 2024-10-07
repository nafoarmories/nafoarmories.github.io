---
layout: post
title:  "Fundraiser - OBBP XV - Barbecubes"
date: 2024-07-23
author: Wende
categories: fundraisers update obbp15
image: assets/images/gallery/obbp15.jpeg
fundraiser_target:
- title: 8" FPV Drones
  count: x16
- title: The Queen Hornet FPV Drones
  count: x2
- title: Leyleys
  count: x100
- title: Ecoflow
  count: x3

fundraiser_data:
- title: 🎯Goal
  tag: goal
  count: 14000$

fundraiser_chart_data:
  min: 0
  max: 14000
  api: donations/get/default/total
---

{% include stat_display.html stats=page.fundraiser_data
api="donations/get/default/total" api_id="goal" %}

![obbp13]({{ "assets/images/gallery/obbp15.jpeg" | relative_url }})

{% include handle_link.md thing=site.data.twitter.team %} and the 92nd Assault Brigade invite you to:

## 𝐎𝐩𝐞𝐫𝐚𝐭𝐢𝐨𝐧 𝐁𝐨𝐨𝐦 𝐁𝐨𝐨𝐦 𝐏𝐨𝐰 𝐗𝐕: 𝐁𝐚𝐫𝐛𝐞𝐜𝐮𝐛𝐞𝐬

{% include half_circle_chart.html data=page.fundraiser_chart_data %}

# What’s it for:

{% include stat_display.html stats=page.fundraiser_target %}

🎁$50 donation - get a NAFOArmories patch. DM {% include handle_link.md
thing=site.data.twitter.wende %}

<div class="dono-img">
    <a href="{{ '/donate/' | relative_url }}"><img src="{{ '/assets/images/gallery/patches-pride.png' | relative_url }}" alt="Gallery"></a>
</div>

We are thankful for your support. Together We Will Win 🙏❤️🇺🇦

{% include donate_button.html %}
