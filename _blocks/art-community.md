title: Art Community
slug: art-community
image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
gif_image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
categories:
  - StreamElements
  - Twitch
description: Демонстрація всіх можливостей
layout: block-info
back_url: /
---

<div class="content-container">

## Чотири стилі кнопок

<div style="display:flex; flex-wrap:wrap; gap:16px; align-items:center; margin-bottom:2rem;">

{% include btn-saburo.html label="Outline" visual="outline" %}
{% include btn-saburo.html label="White" visual="white" %}
{% include btn-saburo.html label="Rainbow" visual="rainbow" %}
{% include btn-saburo.html label="Pill" visual="pill" %}

</div>

## Комбінації з наведенням

<div style="display:flex; flex-wrap:wrap; gap:16px; align-items:center; margin-bottom:2rem;">

{% include btn-saburo.html label="Outline → Rainbow" visual="outline" hover="rainbow" %}
{% include btn-saburo.html label="Rainbow → White" visual="rainbow" hover="white" %}
{% include btn-saburo.html label="Pill → Outline" visual="pill" hover="outline" %}

</div>

## Іконки та позиціонування

<div style="display:flex; flex-wrap:wrap; gap:16px; align-items:center; margin-bottom:2rem;">

{% include btn-saburo.html label="Зірочка" visual="outline" icon_visual="star" %}
{% include btn-saburo.html label="Іконка після" visual="rainbow" icon_visual="favorite" icon_position="after" %}

</div>

---

## Форматування тексту

Це **жирний текст**, а це *курсив*. Можна ~~закреслити~~ слово.

### Заголовки

# H1
## H2
### H3
#### H4

### Списки

- Ненумерований
- Другий пункт
  - Вкладений

1. Нумерований
2. Другий
   1. Вкладений

### Цитата

> Ексклюзивний контент для спільноти SABURO — безкоштовно та зі смаком.

### Код

Вбудований `код` всередині рядка.

// блок коду
function hello() {
  console.log("Привіт, світе!");
}

### Горизонтальна лінія

---

### Посилання та зображення

[Посилання на головну](/)

![Лого]({{ '/svg/logo_symbol.svg' | relative_url }})

### Таблиця (якщо підтримується)

| Стовпець 1 | Стовпець 2 |
|------------|------------|
| значення   | значення   |

</div>