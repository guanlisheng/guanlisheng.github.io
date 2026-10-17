---
layout: default
title: "Poker Terminal — Mobile Tournament Console"
description: "Blinds, levels and countdown on one screen. Native remote control on iPhone, with independent external display support for the big screen."
image: /assets/img/pokerterminal/hero.png
permalink: /marketing/pokerterminal/
---

<style>
.pt-hero{text-align:center;padding:2.5rem 1rem 1.5rem}
.pt-hero h1{font-size:2.2rem;margin:0 0 .6rem;line-height:1.25}
.pt-hero p.lead{font-size:1.12rem;opacity:.82;max-width:660px;margin:0 auto 1.6rem}
.pt-eyebrow{font-size:.85rem;letter-spacing:.12em;text-transform:uppercase;opacity:.6;margin-bottom:.8rem}
.pt-cta{display:inline-block;margin:.3rem}
.pt-cta img{height:52px;width:auto}
.pt-hero img.hero{max-width:100%;border-radius:16px;margin-top:2rem;
  box-shadow:0 12px 40px rgba(0,0,0,.2)}
.pt-lang{font-size:.9rem;opacity:.7;margin-bottom:1.5rem}
.pt-features{display:grid;gap:1.2rem;margin:2rem 0;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr))}
.pt-card{border:1px solid rgba(128,128,128,.25);border-radius:12px;
  padding:1.1rem 1.2rem}
.pt-card h3{margin:.2rem 0 .5rem;font-size:1.05rem}
.pt-card p{margin:0;font-size:.95rem;opacity:.85}
.pt-shots{display:grid;gap:1rem;margin:2rem 0;
  grid-template-columns:repeat(auto-fit,minmax(180px,1fr))}
.pt-shots img{width:100%;border-radius:12px;
  border:1px solid rgba(128,128,128,.25)}
.pt-faq dt{font-weight:600;margin-top:1.1rem}
.pt-faq dd{margin:.25rem 0 0;opacity:.85}
.pt-note{font-size:.9rem;opacity:.8;border-left:3px solid rgba(128,128,128,.4);
  padding:.2rem 0 .2rem 1rem;margin:1.2rem 0}
.pt-footer{margin-top:3rem;padding-top:1.2rem;font-size:.9rem;opacity:.7;
  border-top:1px solid rgba(128,128,128,.25)}
</style>

<div class="pt-hero" markdown="0">
  <p class="pt-lang"><a href="{{ '/marketing/pokerterminal-zh/' | relative_url }}">中文</a></p>
  <p class="pt-eyebrow">Mobile Tournament Console</p>
  <h1>Blinds, levels and countdown — on one screen.</h1>
  <p class="lead">
    Connect to a configurable HTTPS tournament terminal and follow the action
    on iPhone or iPad. When an independent external display is available, the
    tournament page goes full-screen on the TV while your phone keeps the controls.
  </p>
  <a class="pt-cta" href="https://apps.apple.com/app/idXXXXXXXXX">
    <img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us"
         alt="Download on the App Store">
  </a>
  <img class="hero" src="{{ '/assets/img/pokerterminal/hero.png' | relative_url }}"
       alt="Poker Terminal showing tournament info on iPhone while the tournament page is displayed full-screen on TV">
</div>

## Everything the table needs

<div class="pt-features" markdown="0">
  <div class="pt-card">
    <h3>⏱️ Key data at a glance</h3>
    <p>Current level, blinds, ante, countdown, entrant count and scoring data, all on one screen.</p>
  </div>
  <div class="pt-card">
    <h3>📺 Dual-screen workflow</h3>
    <p>With an independent external display, the tournament page fills the TV while iPhone keeps the control UI.</p>
  </div>
  <div class="pt-card">
    <h3>🎮 Native remote</h3>
    <p>Directional keys, menu, confirm and back — control a compatible tournament terminal directly from your phone.</p>
  </div>
  <div class="pt-card">
    <h3>🔗 Configurable HTTPS terminal</h3>
    <p>Replace the default demo address with any other HTTPS tournament page you operate.</p>
  </div>
  <div class="pt-card">
    <h3>🔄 Status &amp; refresh</h3>
    <p>Clear loading and connection error states, with manual refresh when you need it.</p>
  </div>
  <div class="pt-card">
    <h3>🔒 Privacy-first</h3>
    <p>The app itself collects no personal data; page content and tournament data come from the terminal you configure.</p>
  </div>
</div>

## Screenshots

<div class="pt-shots" markdown="0">
  <img src="{{ '/assets/img/pokerterminal/shot-1.png' | relative_url }}" alt="Tournament info screen">
  <img src="{{ '/assets/img/pokerterminal/shot-2.png' | relative_url }}" alt="Native remote control screen">
  <img src="{{ '/assets/img/pokerterminal/shot-3.png' | relative_url }}" alt="External display plus iPhone">
</div>

## Good to know

<p class="pt-note">
Poker Terminal is for tournament information display and terminal control.
It does not provide tournament registration or betting, and it does not host
tournament data. Page content and tournament actions are provided by the
configured terminal. Whether the TV gets an independent picture depends on iOS
and the receiving device; if the system only offers screen mirroring, the TV may
show the entire iPhone screen. A network connection is required. Remote control
requires the target page to expose a compatible TerminalRemote interface.
</p>

## FAQ

<dl class="pt-faq">
  <dt>Why don't the remote buttons respond?</dt>
  <dd>Remote control is enabled only when the target page exposes a compatible TerminalRemote interface. Incompatible pages still display, but the remote is unavailable.</dd>

  <dt>Why does the TV show the whole phone screen?</dt>
  <dd>An independent external display depends on iOS and the connected display providing a separate scene. If only screen mirroring is available, the TV mirrors the entire iPhone screen.</dd>

  <dt>How do I change the terminal address?</dt>
  <dd>Use the settings entry on the main screen. Only HTTPS terminal pages are supported.</dd>

  <dt>Does the app offer registration or betting?</dt>
  <dd>No. Poker Terminal is limited to tournament information display and terminal control. Registration, betting and payments happen outside this app.</dd>

  <dt>Do I need an account?</dt>
  <dd>No. There is no account system and the app collects no personal data.</dd>
</dl>

<div class="pt-footer" markdown="0">
  <p>
    <a href="{{ '/privacy/pokerterminal/' | relative_url }}">Privacy Policy</a> ·
    <a href="{{ '/support/pokerterminal/' | relative_url }}">Support</a> ·
    <a href="{{ '/marketing/' | relative_url }}">All apps</a>
  </p>
  <p>Poker Terminal is not affiliated with any poker brand, tournament operator or Apple Inc.
     App Store is a service mark of Apple Inc.</p>
</div>
