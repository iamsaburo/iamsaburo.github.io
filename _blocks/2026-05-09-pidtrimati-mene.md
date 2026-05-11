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

Всі бажаючі тепер можуть встановити собі в описі Twitch каналу панель нашої Telegram групи.
##### Це абсолютно ⚠️ не обов’язково, але буду вдячний!

---

# ПОСИЛАННЯ:
В налаштуваннях панелі 👇 додайте посилання на запрошення<br>
#`https://t.me/saburo_ua`

**Ваша підтримка мотивує мене робити ще більше цікавих штучок для стрімерів і розвивати українське** 💙💛

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

  <!-- 📁 TAB 1: Telegram -->
  <div class="tab-panel active" data-tab="tab-tg">
    <div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="/webp/SABURO_TG_MEDIUM.png" class="tab-icon-svg" alt="Telegram Medium"
             style="width:100%; border-radius:4px; display:block;">
        <a class="btn-saburo" data-visual="pill" data-icon-visual="download"
           style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
           href="/webp/SABURO_TG_MEDIUM.png" download="SABURO_TG_MEDIUM.png" target="_blank">
          <span class="material-icons-round btn-icon-visual">download</span>
          <span class="btn-label">Завантажити</span>
        </a>
      </div>
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="/webp/SABURO_TG_SMALL.png" class="tab-icon-svg" alt="Telegram Small"
             style="width:100%; border-radius:4px; display:block;">
        <a class="btn-saburo" data-visual="pill" data-icon-visual="download"
           style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
           href="/webp/SABURO_TG_SMALL.png" download="SABURO_TG_SMALL.png" target="_blank">
          <span class="material-icons-round btn-icon-visual">download</span>
          <span class="btn-label">Завантажити</span>
        </a>
      </div>
    </div>
  </div>

  <!-- 📁 TAB 2: Discord -->
  <div class="tab-panel" data-tab="tab-dc">
    <div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="/webp/SABURO_DS_MEDIUM.png" class="tab-icon-svg" alt="Discord Medium"
             style="width:100%; border-radius:4px; display:block;">
        <a class="btn-saburo" data-visual="pill" data-icon-visual="download"
           style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
           href="/webp/SABURO_DS_MEDIUM.png" download="SABURO_DS_MEDIUM.png" target="_blank">
          <span class="material-icons-round btn-icon-visual">download</span>
          <span class="btn-label">Завантажити</span>
        </a>
      </div>
      <div style="flex:0 0 auto; max-width:300px;">
        <img src="/webp/SABURO_DS_SMALL.png" class="tab-icon-svg" alt="Discord Small"
             style="width:100%; border-radius:4px; display:block;">
        <a class="btn-saburo" data-visual="pill" data-icon-visual="download"
           style="--btn-w:100%; --btn-h:40px; --radius:10px; margin-top:0.5rem;"
           href="/webp/SABURO_DS_SMALL.png" download="SABURO_DS_SMALL.png" target="_blank">
          <span class="material-icons-round btn-icon-visual">download</span>
          <span class="btn-label">Завантажити</span>
        </a>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════
     TWITCH AVATARS (unavatar + fallback, left‑aligned)
     ═══════════════════════════════════════════ -->
<h2 style="margin-top:3rem;">💛 Дякую за підтримку:</h2>

<div id="twitch-avatars" style="display:flex; flex-wrap:wrap; gap:1.2rem; justify-content:flex-start; margin-top:1.5rem;">
  <!-- filled by script -->
</div>

<script>
(function(){
  const twitchUsers = [
    "Lamark_sk8", "DMTRNKOO", "Sonna_Sonia", "Hassk14", "freshnia4ok", "thesanches_",
    "Evgeniusd", "JesVikk", "Xenatik0", "ZubikStyle", "blueberrycblack", "vtomleni",
    "snellkin", "Trickster_Lis", "bloody_specter", "the0ara", "Goolkim", "DannyelGray",
    "Alex969Hell", "Nisenitnytsya", "Vladykus", "bander_oli4ka", "izumkaua", "bastetvibe",
    "Stop_me_2", "pis_tashka", "jeleshka____", "Finka_o", "Fotograf_UA", "DzrtFoxUA",
    "Kavalets", "gamebulochka", "Otolich", "ArdenLich"
  ];

  const container = document.getElementById("twitch-avatars");

  twitchUsers.forEach(user => {
    const a = document.createElement("a");
    a.href = `https://twitch.tv/${user}`;
    a.target = "_blank";
    a.rel = "noopener noreferrer";
    a.style.display = "flex";
    a.style.flexDirection = "column";
    a.style.alignItems = "center";
    a.style.gap = "0.4rem";
    a.style.textDecoration = "none";
    a.style.color = "inherit";

    const img = document.createElement("img");
    img.className = "tab-icon-svg";
    img.alt = user;
    img.style.width = "60px";
    img.style.height = "60px";
    img.style.borderRadius = "50%";
    img.style.objectFit = "cover";
    img.style.border = "2px solid rgba(255,255,255,0.2)";

    // Try unavatar (works for most)
    img.src = `https://unavatar.io/twitch/${user}`;

    // If it fails, show a dark circle with the first letter
    img.onerror = function() {
      this.onerror = null;
      const letter = user.charAt(0).toUpperCase();
      this.src = `data:image/svg+xml,${encodeURIComponent(
        `<svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 60 60">
          <circle cx="30" cy="30" r="30" fill="#1a1a1a"/>
          <text x="30" y="36" text-anchor="middle" fill="#fff" font-size="28" font-family="Arial">${letter}</text>
        </svg>`
      )}`;
    };

    const span = document.createElement("span");
    span.textContent = user;
    span.style.fontSize = "0.75rem";
    span.style.textAlign = "center";
    span.style.maxWidth = "70px";
    span.style.overflow = "hidden";
    span.style.textOverflow = "ellipsis";
    span.style.whiteSpace = "nowrap";

    a.appendChild(img);
    a.appendChild(span);
    container.appendChild(a);
  });
})();
</script>

---

