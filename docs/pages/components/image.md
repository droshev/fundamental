---
title: Image
keywords: image
sidebar: left-navigation-sidebar
toc: false
permalink: components/image.html
folder: components
summary:
---

When using images, use the following helpers classes to adjust the size and the shape.

<hr>

## Size and Shape

Size Options: `--s` 24x24, `--m` 36x36, `--l` 48x48

Shape Option: `--circle` will render a round image

{% capture default %}
<span class="fd-image--s" aria-label="Image label"
style="background-image: url('https://placeimg.com/400/400/nature');"></span>

<span class="fd-image--m" aria-label="Image label"
style="background-image: url('https://placeimg.com/400/400/nature');"></span>

<span class="fd-image--l" aria-label="Image label"
style="background-image: url('https://placeimg.com/400/400/nature');"></span>

<br><br>

<span class=" fd-image--s fd-image--circle" aria-label="Image label"
style="background-image: url('https://placeimg.com/400/400/nature');"></span>

<span class=" fd-image--m fd-image--circle" aria-label="Image label"
style="background-image: url('https://placeimg.com/400/400/nature');"></span>

<span class=" fd-image--l fd-image--circle" aria-label="Image label"
style="background-image: url('https://placeimg.com/400/400/nature');"></span>
{% endcapture %}

{% include display-component.html component=default %}
