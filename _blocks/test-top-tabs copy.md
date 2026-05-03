---
title: "Test — Можливості (вкладки зверху)"
slug: test-top-tabs
order: 97
hidden: false
image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
back_url: /
back_label: Головна
categories:
  - StreamElements
  - Twitch
  - OBS
tabs:
  - id: text
    icon: format_align_left
    label: Текст
  - id: buttons
    icon: smart_button
    label: Кнопки
  - id: embeds
    icon: image
    label: Медіа
---
# H1 Заголовок сторінки
## H2 Підзаголовок
### H3 Малий заголовок

**Жирний**, *курсив*, ~~закреслений~~, `inline code` — клікни щоб скопіювати.

> Блок цитати виглядає так

---

- Маркований список
  - Вкладений елемент
- Другий пункт

1. Нумерований список
2. Другий пункт

---

| Колонка 1 | Колонка 2 | Колонка 3 |
|-----------|-----------|-----------|
| Дані      | Дані      | Дані      |
| Рядок 2   | Рядок 2   | Рядок 2   |

[Звичайне посилання](https://example.com)

```js
// Блок коду — кнопка Copy з'являється автоматично
const greet = name => `Привіт, ${name}!`;
console.log(greet('Світ'));
```

<!-- tab -->

## Всі стилі кнопок

### Візуальні типи (статичні)

<div style="display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin-bottom:1.5rem;">
  <a class="btn-saburo" data-visual="outline" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#"><span class="btn-label">Outline</span></a>
  <a class="btn-saburo" data-visual="white" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#"><span class="btn-label">White</span></a>
  <a class="btn-saburo" data-visual="pill" style="--btn-w:auto;--btn-h:48px;--radius:28px;" href="#"><span class="btn-label">Pill</span></a>
  <a class="btn-saburo" data-visual="rainbow" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#"><span class="btn-label">Rainbow</span></a>
</div>

### Hover-ефекти

<div style="display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin-bottom:1.5rem;">
  <a class="btn-saburo" data-visual="outline" data-hover="rainbow" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#"><span class="btn-label">Outline → Rainbow</span></a>
  <a class="btn-saburo" data-visual="pill" data-hover="white" style="--btn-w:auto;--btn-h:48px;--radius:28px;" href="#"><span class="btn-label">Pill → White</span></a>
  <a class="btn-saburo" data-visual="pill" data-hover="outline" style="--btn-w:auto;--btn-h:48px;--radius:28px;" href="#"><span class="btn-label">Pill → Outline</span></a>
  <a class="btn-saburo" data-visual="rainbow" data-hover="white" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#"><span class="btn-label">Rainbow → White</span></a>
</div>

### З іконками

<div style="display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin-bottom:1.5rem;">
  <a class="btn-saburo" data-visual="outline" data-icon-visual="favorite" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#">
    <span class="material-icons-round btn-icon-visual">favorite</span>
    <span class="btn-label">Іконка перед</span>
  </a>
  <a class="btn-saburo" data-visual="outline" data-icon-visual="download" data-icon-position="after" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#">
    <span class="btn-label">Іконка після</span>
    <span class="material-icons-round btn-icon-visual">download</span>
  </a>
  <a class="btn-saburo" data-visual="pill" data-icon-visual="star" data-icon-hover="arrow_forward" style="--btn-w:auto;--btn-h:48px;--radius:28px;" href="#">
    <span class="material-icons-round btn-icon-visual">star</span>
    <span class="material-icons-round btn-icon-hover">arrow_forward</span>
    <span class="btn-label">Hover-зміна іконки</span>
  </a>
  <a class="btn-saburo" data-visual="rainbow" data-hover="rainbow" data-icon-visual="rocket_launch" data-icon-position="after" style="--btn-w:auto;--btn-h:48px;--radius:10px;" href="#">
    <span class="btn-label">Rainbow + іконка</span>
    <span class="material-icons-round btn-icon-visual">rocket_launch</span>
  </a>
</div>

### Розміри (висота)

<div style="display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin-bottom:1.5rem;">
  <a class="btn-saburo" data-visual="pill" style="--btn-w:auto;--btn-h:32px;--radius:28px;" href="#"><span class="btn-label">Малий 32px</span></a>
  <a class="btn-saburo" data-visual="pill" style="--btn-w:auto;--btn-h:48px;--radius:28px;" href="#"><span class="btn-label">Звичайний 48px</span></a>
  <a class="btn-saburo" data-visual="pill" style="--btn-w:auto;--btn-h:60px;--radius:28px;" href="#"><span class="btn-label">Великий 60px</span></a>
</div>

### Радіус

<div style="display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin-bottom:1.5rem;">
  <a class="btn-saburo" data-visual="outline" style="--btn-w:auto;--btn-h:48px;--radius:4px;" href="#"><span class="btn-label">Гострий 4px</span></a>
  <a class="btn-saburo" data-visual="outline" style="--btn-w:auto;--btn-h:48px;--radius:14px;" href="#"><span class="btn-label">Округлений 14px</span></a>
  <a class="btn-saburo" data-visual="outline" style="--btn-w:auto;--btn-h:48px;--radius:28px;" href="#"><span class="btn-label">Пілюля 28px</span></a>
</div>

### Повна ширина

<div style="display:flex;flex-direction:column;gap:10px;max-width:400px;">
  <a class="btn-saburo" data-visual="outline" data-hover="rainbow" style="--btn-w:100%;--btn-h:48px;--radius:10px;" href="#"><span class="btn-label">Повна ширина — Outline → Rainbow</span></a>
  <a class="btn-saburo" data-visual="rainbow" style="--btn-w:100%;--btn-h:48px;--radius:10px;" href="#"><span class="btn-label">Повна ширина — Rainbow</span></a>
</div>

<!-- tab -->

## Зображення

![Тестове зображення](https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif)

---

## Відео (YouTube embed)

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>