---
title: 💛 Підтримати Мене
slug: support
order: 77
hidden: true
image: webp/SABURO_ThankYou.webp
back_url: /
categories:
  - Twitch
embed_max_width: 500px
---
<video autoplay loop muted playsinline style="max-width:100%; border-radius:4px; display:block;">
  <source src="webm/SABURO_ThankYou.webm" type="video/webm">
</video>

<div style="margin-top: 0.5rem;"></div>

### Всі бажаючі тепер можуть встановити собі в описі Twitch, панель нашого Telegram або Discord.
Це абсолютно ⚠️ не обов’язково, але буду вдячний!

<div style="margin-top: 0.5rem;"></div>

---

<div class="inline-tabs">
  <nav class="tabs-nav" role="tablist">
    <button class="tab-btn active" data-tab="tab-tg" role="tab" aria-selected="true">
      <img src="/svg/sm_telegram.svg" class="tab-icon-svg" style="width:18px; height:18px;" alt="">
      <span>Telegram</span>
    </button>
    <button class="tab-btn" data-tab="tab-dc" role="tab" aria-selected="false">
      <img src="/svg/sm_discord.svg" class="tab-icon-svg" style="width:18px; height:18px;" alt="">
      <span>Discord</span>
    </button>
  </nav>

  <!-- TAB 1: Telegram -->
  <div class="tab-panel active" data-tab="tab-tg">
    <div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">
      <!-- Image 1 -->
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif"
             class="tab-icon-svg"
             alt="Telegram image 1"
             style="width:100%; border-radius:4px; display:block;">
             <a class="btn-saburo" data-visual="pill"
                style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
                href="..." download="..." target="_blank">
               <span class="material-icons-round btn-icon-visual">download</span>
               <span class="btn-label">Завантажити</span>
             </a>
      </div>

      <!-- Image 2 -->
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif"
             class="tab-icon-svg"
             alt="Telegram image 2"
             style="width:100%; border-radius:4px; display:block;">
             <a class="btn-saburo" data-visual="pill"
                style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
                href="..." download="..." target="_blank">
               <span class="material-icons-round btn-icon-visual">download</span>
               <span class="btn-label">Завантажити</span>
             </a>
      </div>
    </div>
  </div>

  <!-- TAB 2: Discord -->
  <div class="tab-panel" data-tab="tab-dc">
    <div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">
      <!-- Image 1 -->
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif"
             class="tab-icon-svg"
             alt="Discord image 1"
             style="width:100%; border-radius:4px; display:block;">
             <a class="btn-saburo" data-visual="pill"
                style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
                href="..." download="..." target="_blank">
               <span class="material-icons-round btn-icon-visual">download</span>
               <span class="btn-label">Завантажити</span>
             </a>
      </div>

      <!-- Image 2 -->
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="https://i.postimg.cc/JzZmjqMr/Pxl-Art-GIF-TG.gif"
             class="tab-icon-svg"
             alt="Discord image 2"
             style="width:100%; border-radius:4px; display:block;">
             <a class="btn-saburo" data-visual="pill"
                style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
                href="..." download="..." target="_blank">
               <span class="material-icons-round btn-icon-visual">download</span>
               <span class="btn-label">Завантажити</span>
             </a>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════
     TWITCH AVATARS (70×70 circles, clickable)
     ═══════════════════════════════════════════ -->
<h2 style="margin-top:3rem;">Наша Twitch команда</h2>

<div id="twitch-avatars" style="display:flex; flex-wrap:wrap; gap:1.5rem; justify-content:center; margin-top:1.5rem;">
  <!-- Dynamically filled by script below -->
</div>

<script>
(function(){
  // ⚡ Put your Twitch usernames here
  const twitchUsers = [
    "saburo_ua",
    "xqcow",
    "shroud",
    "pokimane",
    "ninja",
    "summit1g"
  ];

  const container = document.getElementById("twitch-avatars");
  if (!container) return;

  twitchUsers.forEach(user => {
    // Use Unavatar – free, reliable Twitch avatar service
    const avatarUrl = `https://unavatar.io/twitch/${user}`;
    const twitchLink = `https://twitch.tv/${user}`;

    const wrapper = document.createElement("a");
    wrapper.href = twitchLink;
    wrapper.target = "_blank";
    wrapper.rel = "noopener noreferrer";
    wrapper.style.cssText = "display:flex; flex-direction:column; align-items:center; gap:0.5rem; text-decoration:none; color:inherit;";

    const img = document.createElement("img");
    img.src = avatarUrl;
    img.alt = user;
    img.className = "tab-icon-svg";          // disables download overlay
    img.style.cssText = "width:70px; height:70px; border-radius:50%; object-fit:cover; border:2px solid rgba(255,255,255,0.2);";

    const name = document.createElement("span");
    name.textContent = user;
    name.style.cssText = "font-size:0.85rem; color:var(--text); text-align:center; max-width:80px; overflow:hidden; text-overflow:ellipsis; white-space:nowrap;";

    wrapper.appendChild(img);
    wrapper.appendChild(name);
    container.appendChild(wrapper);
  });
})();
</script>


---

Всі бажаючі тепер можуть встановити собі в описі Twitch каналу панель нашої Telegram групи.
##### Це абсолютно ⚠️ не обов’язково, але буду вдячний!
‎
‎# ПОСИЛАННЯ:
В налаштуваннях панелі 👇 додайте посилання на запрошення
`https://t.me/saburo_ua`

**Ваша підтримка мотивує мене робити ще більше цікавих штучок для стрімерів і розвивати українське** 💙💛