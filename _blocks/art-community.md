---
title: Test - Inline Tabs
slug: test-inline-tabs
order: 98
hidden: false
image: https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif
back_url: /
back_label: Головна
categories:
  - StreamElements
  - OBS
---
## Контент до вкладок

Звичайний текст **з форматуванням**. Вкладки нижче змінюють секцію під собою і не торкаються цього тексту.

<small>Підпис перед блоком вкладок</small>

---

<div class="inline-tabs">
  <nav class="tabs-nav" role="tablist">
    <button class="tab-btn active" data-tab="alpha" role="tab" aria-selected="true">Крок 1</button>
    <button class="tab-btn" data-tab="beta" role="tab" aria-selected="false">Крок 2</button>
    <button class="tab-btn" data-tab="gamma" role="tab" aria-selected="false">Крок 3</button>
  </nav>
  <div class="tab-panel active" data-tab="alpha">
    <p><strong>Перший крок</strong> — встанови розширення.</p>
    <p>Натисни <code>Ctrl+Shift+P</code> і введи назву.</p>
  </div>
  <div class="tab-panel" data-tab="beta">
    <p><strong>Другий крок</strong> — налаштуй змінні.</p>
    <p>Відкрий файл <code>config.json</code> і зміни значення.</p>
  </div>
  <div class="tab-panel" data-tab="gamma">
    <p><strong>Третій крок</strong> — запусти і перевір.</p>

```bash
npm start
```

  </div>
</div>

---

## Контент після вкладок

Цей текст знаходиться **після** блоку вкладок — вкладки не впливають на нього.

| Функція       | Статус |
|---------------|--------|
| Inline tabs   | ✅     |
| Download icon | ✅     |
| Copy code     | ✅     |

![Тест зображення](https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif)