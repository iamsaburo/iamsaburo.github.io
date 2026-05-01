---
title: Демо кнопок
slug: art-community
image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
gif_image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
categories:
  - StreamElements
  - Twitch
description: Усі стилі кнопок та форматування
layout: block-info
back_url: /
back_label: Головна
---

## Hello World

{% include btn-saburo.html label="Hello World" visual="outline" %}

---

## 4 типи кнопок

<div style="display:flex;flex-wrap:wrap;gap:20px;align-items:center;">

{% include btn-saburo.html label="Outline" visual="outline" %}
{% include btn-saburo.html label="White" visual="white" %}
{% include btn-saburo.html label="Rainbow" visual="rainbow" %}
{% include btn-saburo.html label="Pill" visual="pill" %}

</div>

### З іконками

{% include btn-saburo.html label="З іконкою" visual="outline" icon_visual="favorite" %}
{% include btn-saburo.html label="Іконка після" visual="rainbow" icon_visual="arrow_forward" icon_position="after" %}

### Ширина за вмістом

{% include btn-saburo.html label="Автоширина" visual="pill" width="auto" %}

---

## Форматування тексту

**Жирний**, *курсив*, ~~закреслений~~, `код`

- список
  - вкладений

1. нумерований
2. список

> Цитата

Роздільник:

---

### Заголовки

# H1
## H2
### H3

[Посилання](https://example.com)

Картинка: ![лого]({{ '/svg/logo_symbol.svg' | relative_url }})

Таблиця:

| Стовпець 1 | Стовпець 2 |
|------------|------------|
| дані       | дані       |