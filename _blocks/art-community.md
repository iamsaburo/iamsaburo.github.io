---
title: Art Community
slug: art-community
image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
gif_image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
categories:
  - StreamElements
  - Twitch
description: Демонстрація всіх варіантів кнопок
layout: block-info
back_url: /
---

<div class="content-container">

## Усі стилі кнопок

<div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px;">

{% include btn-saburo.html label="Outline (default)" visual="outline" %}
{% include btn-saburo.html label="White" visual="white" %}
{% include btn-saburo.html label="Rainbow" visual="rainbow" %}
{% include btn-saburo.html label="Pill" visual="pill" %}

{% include btn-saburo.html label="Outline → White" visual="outline" hover="white" %}
{% include btn-saburo.html label="Outline → Rainbow" visual="outline" hover="rainbow" %}
{% include btn-saburo.html label="White → Outline" visual="white" hover="outline" %}
{% include btn-saburo.html label="White → Rainbow" visual="white" hover="rainbow" %}
{% include btn-saburo.html label="Rainbow → Outline" visual="rainbow" hover="outline" %}
{% include btn-saburo.html label="Rainbow → White" visual="rainbow" hover="white" %}
{% include btn-saburo.html label="Pill → White" visual="pill" hover="white" %}
{% include btn-saburo.html label="Pill → Outline" visual="pill" hover="outline" %}
{% include btn-saburo.html label="Pill → Rainbow" visual="pill" hover="rainbow" %}

</div>

## З іконками

<div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px;">

{% include btn-saburo.html label="Outline" visual="outline" icon_visual="favorite" %}
{% include btn-saburo.html label="White" visual="white" icon_visual="star" %}
{% include btn-saburo.html label="Rainbow" visual="rainbow" icon_visual="arrow_forward" %}
{% include btn-saburo.html label="Pill" visual="pill" icon_visual="arrow_back" %}

{% include btn-saburo.html label="Outline → Rainbow" visual="outline" hover="rainbow" icon_visual="arrow_forward" icon_hover="arrow_forward" %}
{% include btn-saburo.html label="Rainbow → White" visual="rainbow" hover="white" icon_visual="favorite" icon_hover="favorite" %}

</div>

## Різні розміри та радіуси

<div style="display:flex; flex-wrap:wrap; gap:20px; align-items:center;">

{% include btn-saburo.html label="Маленька" visual="pill" width=100 height=30 radius=20 %}
{% include btn-saburo.html label="Велика" visual="rainbow" width=250 height=60 radius=12 %}
{% include btn-saburo.html label="Квадратна" visual="white" hover="outline" width=120 height=120 radius=0 %}

</div>

</div>