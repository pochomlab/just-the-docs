---
title: 絵書
nav_order: 2
---

<style>
.eg-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:24px;margin-top:24px}
.eg-card{background:#fff;border-radius:14px;overflow:hidden;box-shadow:0 8px 24px rgba(0,0,0,.08);transition:transform .2s ease}
.eg-card:hover{transform:translateY(-4px)}
.eg-card img{width:100%;display:block}
.eg-meta{padding:12px 14px;font-size:14px;color:#555}
.eg-badge{display:inline-block;background:#f3f3f3;border-radius:999px;padding:4px 10px;font-size:12px;margin-right:6px}
</style>

<div class="eg-grid">
  <a class="eg-card" href="{{ '/egaki-sho/ch1/' | relative_url }}">
    <img src="{{ '/assets/images/ch1.jpg' | relative_url }}" alt="第1章">
    <div class="eg-meta"><span class="eg-badge">第1章</span><span class="eg-badge">8灯</span>発売中</div>
  </a>
  <a class="eg-card" href="{{ '/egaki-sho/ch2/' | relative_url }}">
    <img src="{{ '/assets/images/ch2.jpg' | relative_url }}" alt="第2章">
    <div class="eg-meta"><span class="eg-badge">第2章</span><span class="eg-badge">8灯</span>発売中</div>
  </a>
  <a class="eg-card" href="{{ '/egaki-sho/ch3/' | relative_url }}">
    <img src="{{ '/assets/images/ch3.jpg' | relative_url }}" alt="第3章">
    <div class="eg-meta"><span class="eg-badge">第3章</span><span class="eg-badge">8灯</span>発売中</div>
  </a>
  <a class="eg-card" href="{{ '/egaki-sho/ch4/' | relative_url }}">
    <img src="{{ '/assets/images/ch4.jpg' | relative_url }}" alt="第4章">
    <div class="eg-meta"><span class="eg-badge">第4章</span><span class="eg-badge">11灯</span>発売中</div>
  </a>
</div>

<style>
.eg-wrap{background:linear-gradient(180deg,#fff 0%,#fff7fb 100%);padding:16px;border-radius:16px}
.eg-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px}
.eg-card{border-radius:16px;overflow:hidden;box-shadow:0 10px 28px rgba(0,0,0,.08)}
.eg-card img{width:100%;display:block}
.eg-bar{height:6px;background:#f5a873}
</style>

<div class="eg-wrap">
  <div class="eg-grid">
    <a class="eg-card" href="{{ '/egaki-sho/ch1/' | relative_url }}">
      <div class="eg-bar"></div>
      <img src="{{ '/assets/images/ch1.jpg' | relative_url }}" alt="第1章">
    </a>
    <a class="eg-card" href="{{ '/egaki-sho/ch2/' | relative_url }}">
      <div class="eg-bar" style="background:#a582aa"></div>
      <img src="{{ '/assets/images/ch2.jpg' | relative_url }}" alt="第2章">
    </a>
    <a class="eg-card" href="{{ '/egaki-sho/ch3/' | relative_url }}">
      <div class="eg-bar" style="background:#9bd0ff"></div>
      <img src="{{ '/assets/images/ch3.jpg' | relative_url }}" alt="第3章">
    </a>
    <a class="eg-card" href="{{ '/egaki-sho/ch4/' | relative_url }}">
      <div class="eg-bar" style="background:#c7f0a6"></div>
      <img src="{{ '/assets/images/ch4.jpg' | relative_url }}" alt="第4章">
    </a>
  </div>
</div>

<style>
.eg-row{display:flex;gap:20px;overflow-x:auto;padding:10px 4px}
.eg-item{min-width:260px;border-radius:16px;overflow:hidden;box-shadow:0 8px 24px rgba(0,0,0,.1)}
.eg-item img{width:100%;display:block}
</style>

<div class="eg-row">
  <a class="eg-item" href="{{ '/egaki-sho/ch1/' | relative_url }}"><img src="{{ '/assets/images/ch1.jpg' | relative_url }}" alt="第1章"></a>
  <a class="eg-item" href="{{ '/egaki-sho/ch2/' | relative_url }}"><img src="{{ '/assets/images/ch2.jpg' | relative_url }}" alt="第2章"></a>
  <a class="eg-item" href="{{ '/egaki-sho/ch3/' | relative_url }}"><img src="{{ '/assets/images/ch3.jpg' | relative_url }}" alt="第3章"></a>
  <a class="eg-item" href="{{ '/egaki-sho/ch4/' | relative_url }}"><img src="{{ '/assets/images/ch4.jpg' | relative_url }}" alt="第4章"></a>
</div>
