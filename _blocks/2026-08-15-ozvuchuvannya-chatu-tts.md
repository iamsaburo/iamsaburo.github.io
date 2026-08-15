---
title: Озвучування чату (TTS)
slug: text-to-speech
order: 6
hidden: true
image: webp/Звукові Twitch Емоути.webp
webm_image: webm/Звукові Twitch Емоути.webm
back_url: /
categories:
  - StreamElements
  - Twitch
embed_max_width: 500px
---
<video autoplay loop muted playsinline style="max-width:100%; border-radius:8px; display:block;">
  <source src="webm/Звукові Twitch Емоути.webm" type="video/webm">
</video>

## 🥳 Звукові Twitch Емоути  `v26.7`

<div style="display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin-bottom:1.5rem;">
  <a class="btn-saburo" data-visual="rainbow" data-hover="rainbow" data-icon-visual="add_circle" data-icon-hover="add_circle" style="--btn-w:180px;--btn-h:47px;--radius:30px;" href="/twitch-sound-emotes-access">
    <span class="material-icons-round btn-icon-visual">add_circle</span>
    <span class="material-icons-round btn-icon-hover">add_circle</span>
    <span class="btn-label">Встановити</span>
  </a>
</div>

Тепер кожен з ваших **Twitch емоутів** може мати свій **звук**, який прозвучить як тільки хтось використає його в чаті. <br>
Одні спамлять 😄 - і лунає сміх, інші 💛 - і чутно як б'ється серце.

## ОСНОВНІ ФУНКЦІЇ
> 🎵 До 15 емоутів <br>
> ✨ Емоути з'являються на екрані <br>
> 🔊 Керування гучністю <br>
> 🚀 Підтримка анімованих емоутів


<!-- ===== AUTHOR BLOCK ===== -->
<div style="display:flex; flex-direction:column; gap:1rem; background:var(--sur2); border-radius:12px; padding:1.25rem; max-width:min(500px, 100%); width:100%; margin:1.5rem auto 1.5rem 0; border:3px solid #ffc600; box-sizing:border-box;">
  <!-- Row 1: Avatar + text -->
  <div style="display:flex; align-items:center; gap:1.5rem; flex-wrap:wrap;">
    <img id="author-avatar" src="" alt="Twitch profile picture" class="tab-icon-svg" style="width:80px; height:80px; border-radius:50%; object-fit:cover; border:2px solid rgba(255,255,255,0.2); flex-shrink:0;">
    <div style="flex:1; min-width:160px;">
      <h3 style="margin:0 0 0.3rem 0; font-weight:700;">Автор віджету</h3>
      <p style="margin:0; color:var(--muted); font-size:0.9rem;"><strong>ZubikStyle</strong> - творець технічного контенту, який на своєму YouTube створює україномовні гайди з налаштування Streamer.bot, OBS та інших інструментів для стрімінгу.</p>
    </div>
  </div>

  <!-- Row 2: Buttons (full width, left-aligned) -->
  <div style="display:flex; flex-wrap:wrap; gap:0.5rem; justify-content:flex-start; width:100%;">
    <a class="btn-saburo" data-visual="pill" href="https://www.twitch.tv/zubikstyle" target="_blank" rel="noopener noreferrer" style="--btn-w:auto; --btn-h:40px; --radius:6px; gap:8px;">
      <img src="/svg/sm_twitch.svg" class="tab-icon-svg" style="width:24px; height:19px;" alt="">
      <span class="btn-label">Twitch</span>
    </a>
    <a class="btn-saburo" data-visual="pill" href="https://www.youtube.com/@ZubikStyle" target="_blank" rel="noopener noreferrer" style="--btn-w:auto; --btn-h:40px; --radius:6px; gap:8px;">
      <img src="/svg/sm_youtube.svg" class="tab-icon-svg" style="width:18px; height:14px;" alt="">
      <span class="btn-label">YouTube</span>
    </a>
    <a class="btn-saburo" data-visual="pill" href="https://discord.gg/Rks2StY4QC" target="_blank" rel="noopener noreferrer" style="--btn-w:auto; --btn-h:40px; --radius:6px; gap:8px;">
      <img src="/svg/sm_discord.svg" class="tab-icon-svg" style="width:18px; height:14px;" alt="">
      <span class="btn-label">Discord</span>
    </a>
  </div>
</div>
<script>
  (function(){
    const avatar = document.getElementById('author-avatar');
    if (avatar) {
      avatar.src = 'https://unavatar.io/twitch/zubikstyle';
    }
  })();
</script>