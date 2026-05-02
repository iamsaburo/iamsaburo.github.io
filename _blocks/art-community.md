---
title: Демо блок
slug: art-community
order: 3
hidden: false
image: https://www.nintenderos.com/wp-content/uploads/2023/08/zelda-tears-of-the-kingdom-logo-y.jpg
gif_image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
back_url: /
back_label: Головна
categories:
  - StreamElements
  - Twitch
  - OBS
tabs:
  - id: buttons
    icon: smart_button
    label: Кнопки
  - id: formatting
    svg_icon: /svg/logo_symbol.svg
    label: Форматування
---
## Hello World

{::nomarkdown}
{% include btn-saburo.html label="Hello World" visual="outline" %}
{:/}

---

## 4 типи кнопок

<div style="display:flex;flex-wrap:wrap;gap:20px;align-items:center;" markdown="1">

{::nomarkdown}
{% include btn-saburo.html label="Outline" visual="outline" %}
{% include btn-saburo.html label="White" visual="white" %}
{% include btn-saburo.html label="Rainbow" visual="rainbow" %}
{% include btn-saburo.html label="Pill" visual="pill" %}
{:/}

</div>

### З іконками

{::nomarkdown}
{% include btn-saburo.html label="З іконкою" visual="outline" icon_visual="favorite" %}
{% include btn-saburo.html label="Іконка після" visual="rainbow" icon_visual="arrow_forward" icon_position="after" %}
{:/}

### Ширина за вмістом

{::nomarkdown}
{% include btn-saburo.html label="Автоширина" visual="pill" width="auto" %}
{:/}

<!-- tab -->

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