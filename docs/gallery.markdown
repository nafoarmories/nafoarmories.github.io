---
layout: default # change this too!
title: Gallery
permalink: /gallery/
---

# Gallery

Click on any image to view it in full size.

<div class="nafoarms-gallery">
    {% for image in site.static_files %}
        {% if image.path contains 'images/gallery' %}
            <div class="nafoarms-galleryimage">
                <a href="{{ image.path  | relative_url }}"><img src="{{ image.path | relative_url }}" alt="image" /></a>
            </div>
        {% endif %}
    {% endfor %}
</div>