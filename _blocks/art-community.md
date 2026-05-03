---
title: "Test — Вкладки посередині"
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
## Контент перед вкладками

Цей текст знаходиться **вище** вбудованих вкладок. Вкладки нижче є незалежним блоком — вони не впливають на цей текст.

-# Малий підпис перед вкладками через синтаксис -#

---

<div class="inline-tabs">
  <nav class="tabs-nav" role="tablist">
    <button class="tab-btn active" data-tab="step1" role="tab" aria-selected="true">Крок 1</button>
    <button class="tab-btn" data-tab="step2" role="tab" aria-selected="false">Крок 2</button>
    <button class="tab-btn" data-tab="step3" role="tab" aria-selected="false">Крок 3</button>
  </nav>
  <div class="tab-panel active" data-tab="step1">
    <p><strong>Перший крок</strong> — встановлення.</p>
    <p>Відкрий термінал і виконай команду:</p>
    <pre><code>npm install my-package</code></pre>
  </div>
  <div class="tab-panel" data-tab="step2">
    <p><strong>Другий крок</strong> — налаштування файлу <code>config.json</code>.</p>
    <pre><code>{
  "token": "ВАШ_ТОКЕН",
  "channel": "назва_каналу"
}</code></pre>
  </div>
  <div class="tab-panel" data-tab="step3">
    <p><strong>Третій крок</strong> — запуск і перевірка роботи.</p>
    <pre><code>npm start</code></pre>
    <p>Якщо все гаразд — у консолі побачиш <code>Connected!</code></p>
  </div>
</div>

---

## Контент після вкладок

Цей блок знаходиться **після** вбудованих вкладок і ніяк не пов'язаний з ними.

Перенос рядка через зворотній слеш: \ 
Другий рядок починається тут.

| Можливість       | Статус |
|------------------|--------|
| Inline tabs      | ✅     |
| -# малий текст   | ✅     |
| \\ перенос рядка | ✅     |
| Завантаження фото | ✅    |
| Copy code        | ✅     |

![Тест](https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif)

-# Зображення вище: наведи для кнопки завантаження