---
layout: default # change this too!
title: Gallery
permalink: /gallery/
image: assets/images/pride_100x100.png
---

# Videos

{% include youtube_vod.html video_id="Dt99a0Q-slg" %}

# Pictures

Click on any image to view it in full size

<div class="nafoarms-gallery">
    {% for image in site.static_files %}
        {% if image.path contains 'images/gallery' %}
            <div>
                <a href="{{ image.path  | relative_url }}"><img src="{{ image.path | relative_url }}" alt="image" /></a>
            </div>
        {% endif %}
    {% endfor %}
</div>
