---
title: Демо блок
slug: demo
order: 5
hidden: false
image: https://i.postimg.cc/DySMFyy9/Screenshot-2026-05-02-at-14-37-41-Adaptivnij-Shout-Out-Telegraph.png
gif_image: https://files.catbox.moe/eb4l4z.gif
back_url: /
back_label: Головна
categories:
  - StreamElements
  - Streamer.bot
  - Twitch
tabs:
  - id: se
    svg_icon: /svg/streamelements.svg
    label: StreamElements
  - id: sb
    svg_icon: /svg/streamer-bot.svg
    label: Streamer.bot
embed_max_width: 450px
---
---
title: Адаптивний ShoutOut
slug: adaptive-shoutout
order: 5
hidden: false
image: https://i.postimg.cc/DySMFyy9/Screenshot-2026-05-02-at-14-37-41-Adaptivnij-Shout-Out-Telegraph.png
gif_image: https://files.catbox.moe/eb4l4z.gif
back_url: /
back_label: Головна
categories:
  - StreamElements
  - Streamer.bot
  - Twitch
tabs:
  - id: se
    svg_icon: /svg/streamelements.svg
    label: StreamElements
  - id: sb
    svg_icon: /svg/streamer-bot.svg
    label: Streamer.bot
embed_max_width: 450px
---
# ЯК ВСТАНОВИТИ

> 📢 Адаптивний ShoutOut v2.0 (15.02.2026)


## 1. Натисни 👇

<div style="display:flex;flex-wrap:wrap;gap:20px;align-items:center;" markdown="1">
{::nomarkdown}
{% include btn-saburo.html href="https://iamsaburo.github.io/" label="ВСТАНОВИТИ ВІДЖЕТ" visual="white" hover="rainbow" icon_position="before" icon_visual="favorite" %}
{:/}
</div>
---
{:start="2"}
2. Авторизуйся через 🚀 StreamElements <br>
Код: `1771178628138` <br>


![картинка]({{ 'https://i.postimg.cc/tTSsjHXS/Login.png' | relative_url }})
---
## 3. Налаштуй під себе
( 📂 ВІДЖЕТ ) 👉 ( 🔧 Settings )


![картинка]({{ 'https://i.postimg.cc/tTSsjHXS/Login.png' | relative_url }})
---
## 4. Збережи налаштування ( SAVE )

## 5. Скопіюй (🔗) посилання


![картинка]({{ 'https://i.postimg.cc/tTSsjHXS/Login.png' | relative_url }})
---
## 6. В OBS додай джерело **` 🌍 Браузер `**

- **URL-aдpeca:** встав скопійоване раніше <br>
- **Ширина:** `1000` \| Висота: `400` <br>
- ✅ Керувати звуком через OBS <br>
---
## 7. Щоб звуки було чути тобі і глядачам:
- В **розширених налаштуваннях аудіо** вибери ` Прослуховування та вивід `


![картинка]({{ 'https://i.postimg.cc/tTSsjHXS/Login.png' | relative_url }})
---
## 8. Натисни 👇

<div style="display:flex;flex-wrap:wrap;gap:20px;align-items:center;" markdown="1">
{::nomarkdown}
{% include btn-saburo.html href="https://streamelements.com/dashboard/bot/commands/custom?data=JTdCJTIyY29vbGRvd24lMjIlM0ElN0IlMjJ1c2VyJTIyJTNBMTUlMkMlMjJnbG9iYWwlMjIlM0E1JTdEJTJDJTIyYWxpYXNlcyUyMiUzQSU1QiU1RCUyQyUyMmtleXdvcmRzJTIyJTNBJTVCJTVEJTJDJTIydGl0bGVLZXl3b3JkcyUyMiUzQSU1QiU1RCUyQyUyMmVuYWJsZWQlMjIlM0F0cnVlJTJDJTIyZW5hYmxlZE9ubGluZSUyMiUzQXRydWUlMkMlMjJlbmFibGVkT2ZmbGluZSUyMiUzQXRydWUlMkMlMjJoaWRkZW4lMjIlM0FmYWxzZSUyQyUyMmNvc3QlMjIlM0EwJTJDJTIydHlwZSUyMiUzQSUyMnNheSUyMiUyQyUyMmFjY2Vzc0xldmVsJTIyJTNBMTAwJTJDJTIyY29tbWFuZCUyMiUzQSUyMmZlZndlZnclMjIlMkMlMjJyZXBseSUyMiUzQSUyMndlZmZldyUyMiUyQyUyMnJlZ2V4JTIyJTNBJTIyJTIyJTdE" label="ДОДАТИ КОМАНДУ" visual="white" hover="rainbow" icon_position="before" icon_visual="favorite" %}
{:/}
</div>


9. Активуй команду ( ACTIVATE COMMAND )



<div style="margin: 20px 0; font-family: sans-serif;">
  <label for="twitch-username" style="display: block; margin-bottom: 5px; font-weight: bold;">
    Your Twitch username:
  </label>
  <input
    type="text"
    id="twitch-username"
    placeholder="e.g. ninja"
    style="padding: 8px; width: 250px; margin-bottom: 10px; border: 1px solid #ccc; border-radius: 4px;"
  />
  <br />
  <button
    onclick="goToRewards()"
    style="padding: 10px 20px; background-color: #9146FF; color: white; border: none; border-radius: 4px; cursor: pointer;"
  >
    Go to Channel Point Rewards
  </button>
</div>

<script>
  function goToRewards() {
    const username = document.getElementById("twitch-username").value.trim();
    if (!username) {
      alert("Please enter a username.");
      return;
    }
    const url = `https://dashboard.twitch.tv/u/${username}/viewer-rewards/channel-points/rewards`;
    window.open(url, "_blank");
  }
</script>


