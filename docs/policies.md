---
layout: default # change this too!
title: Policies
permalink: /policies/
image: assets/images/pride_100x100.png

enable_translate: true
---

<div class="lang-eng">

{% assign page = site.pages | where: "url", "/policies-eng/" | first %}
{{ page.content }}


</div>

<div class="lang-ua" style="display: none; visibility: hidden;">

{% assign page = site.pages | where: "url", "/policies-ua/" | first %}
{{ page.content }}

</div>


<br>
<br>
