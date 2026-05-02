---
title: Демо кнопок
slug: art-community
order: 2
image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
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
published: true
---
## Hello World

<button class="btn-saburo" data-visual="outline" style="--btn-w:auto;--btn-h:48px;--radius:10px;">Hello World</button>

---

## 4 типи кнопок

<div style="display:flex;flex-wrap:wrap;gap:20px;align-items:center;">

<button class="btn-saburo" data-visual="outline" style="--btn-w:auto;--btn-h:48px;--radius:10px;">Outline</button>
<button class="btn-saburo" data-visual="white" style="--btn-w:auto;--btn-h:48px;--radius:10px;">White</button>
<button class="btn-saburo" data-visual="rainbow" style="--btn-w:auto;--btn-h:48px;--radius:10px;">Rainbow</button>
<button class="btn-saburo" data-visual="pill" style="--btn-w:auto;--btn-h:48px;--radius:10px;">Pill</button>

</div>

### З іконками

<button class="btn-saburo" data-visual="outline" data-icon-visual="favorite" style="--btn-w:auto;--btn-h:48px;--radius:10px;">З іконкою</button>
<button class="btn-saburo" data-visual="rainbow" data-icon-visual="arrow_forward" data-icon-position="after" style="--btn-w:auto;--btn-h:48px;--radius:10px;">Іконка після</button>

### Ширина за вмістом

<button class="btn-saburo" data-visual="pill" style="--btn-w:auto;--btn-h:48px;--radius:10px;">Автоширина</button>

<!-- tabs:start -->

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

<!-- tabs:end -->

Звичайний текст після вкладок.