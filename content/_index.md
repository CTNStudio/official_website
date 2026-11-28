---
title: 星屹工作室
layout: hextra-home
---
{{< hextra/hero-container cols="1" class="cw-hero-wrap" >}}

<div class="hx:mt-6 hx:mb-6">
{{< hextra/hero-headline >}}
  群「星」闪耀&nbsp;<br class="sm:hx-block hx:hidden" /> 始终如「屹」
{{< /hextra/hero-headline >}}
</div>

<div class="hx:mt-6 hx:mb-12">
{{< hextra/hero-subtitle >}}
  欢迎来到星屹工作室官方网站
{{< /hextra/hero-subtitle >}}
</div>
{{< /hextra/hero-container>}}

<div class="cw-hero not-prose" data-interval="5200">
  <p class="cw-eyebrow">工作室作品</p>
  <div class="cw-viewport">
    <div class="cw-item is-on">
      <a class="cw-media" href="/wiki/works/mods/hidden-years/" aria-label="隐藏之年²"><img src="https://s41.ax1x.com/2026/02/17/pZONYge.png" alt="隐藏之年² 封面" fetchpriority="high"></a>
      <div class="cw-info">
        <h3 class="cw-title">隐藏之年&#178;</h3>
        <p class="cw-desc">持续完善的开放世界冒险模组，从底层重构体验，随探索深入逐步揭开世界深处的秘密。</p>
        <a class="cw-link" href="/wiki/works/mods/hidden-years/">查看详情</a>
      </div>
    </div>
    <div class="cw-item">
      <a class="cw-media" href="/wiki/works/mods/stone-craft/" aria-label="石头工艺"><img src="https://cdn.modrinth.com/data/cached_images/1fc126789f92522a96d56cb6a23006bb6affe632.png" alt="石头工艺 封面" loading="lazy"></a>
      <div class="cw-info">
        <h3 class="cw-title">石头工艺</h3>
        <p class="cw-desc">以石头为主题的实用模组，让你背包里堆积的圆石不再浪费。</p>
        <a class="cw-link" href="/wiki/works/mods/stone-craft/">查看详情</a>
      </div>
    </div>
    <div class="cw-item">
      <a class="cw-media" href="/wiki/works/mods/stone-adventure/" aria-label="磐石之旅"><img src="https://i.imgs.ovh/2026/08/30/554c6f20aa88cd0a182c07706d298c49.png" alt="磐石之旅 封面" loading="lazy"></a>
      <div class="cw-info">
        <h3 class="cw-title">磐石之旅</h3>
        <p class="cw-desc">石头工艺的衍生冒险模组，用一块圆石开启一段全新的旅程。</p>
        <a class="cw-link" href="/wiki/works/mods/stone-adventure/">查看详情</a>
      </div>
    </div>
    <div class="cw-item">
      <a class="cw-media" href="/wiki/works/mods/chinese-weapon/" aria-label="中式甲兵"><img src="https://s41.ax1x.com/2026/07/29/pmfMty9.png" alt="中式甲兵 封面" loading="lazy"></a>
      <div class="cw-info">
        <h3 class="cw-title">中式甲兵</h3>
        <p class="cw-desc">新增多种中式盔甲、兵器与合成材料，还原古典甲胄的质感。</p>
        <a class="cw-link" href="/wiki/works/mods/chinese-weapon/">查看详情</a>
      </div>
    </div>
  </div>
  <div class="cw-ctrl">
    <button class="cw-nav cw-prev" type="button" aria-label="上一个作品">&#8249;</button>
    <div class="cw-dots" role="tablist" aria-label="作品切换">
      <button class="cw-dot is-on" type="button" role="tab" aria-selected="true" aria-label="第 1 个作品"></button>
      <button class="cw-dot" type="button" role="tab" aria-selected="false" aria-label="第 2 个作品"></button>
      <button class="cw-dot" type="button" role="tab" aria-selected="false" aria-label="第 3 个作品"></button>
      <button class="cw-dot" type="button" role="tab" aria-selected="false" aria-label="第 4 个作品"></button>
    </div>
    <button class="cw-nav cw-next" type="button" aria-label="下一个作品">&#8250;</button>
  </div>
</div>

<div class="cw-more">
{{< hextra/hero-button text="更多作品" link="wiki/works" >}}
</div>

<style>
.cw-hero-wrap{grid-template-columns:1fr!important;--hextra-feature-grid-cols:1;text-align:center;justify-items:center}
.cw-hero-wrap h1,.cw-hero-wrap p{text-align:center}
.cw-hero{display:flex;flex-direction:column;align-items:center;text-align:center;width:100%;max-width:760px;margin:0 auto 2.4rem}
.cw-eyebrow{margin:0 0 1.1rem;font-size:.75rem;font-weight:600;letter-spacing:.2em;text-transform:uppercase;opacity:.55}
.cw-viewport{display:grid;width:100%;max-width:760px;min-height:clamp(320px,52vh,560px)}
.cw-item{grid-area:1/1;position:relative;z-index:1;display:flex;flex-direction:column;align-items:center;justify-content:flex-start;opacity:0;transform:rotate(5deg) scale(.94);pointer-events:none;backface-visibility:hidden;will-change:transform,opacity;transition:opacity .9s cubic-bezier(.22,.61,.36,1),transform .9s cubic-bezier(.22,.61,.36,1)}
.cw-item.is-on{z-index:2;opacity:1;transform:rotate(0deg) scale(1);pointer-events:auto}
.cw-media{display:flex;align-items:center;justify-content:center;width:100%;height:clamp(200px,40vh,400px);overflow:hidden;border-radius:12px}
.cw-media img{display:block;max-width:100%;max-height:100%;width:auto;height:auto;object-fit:contain;border-radius:12px;transform:scale(1.04);transition:transform 1.2s cubic-bezier(.22,.61,.36,1)}
.cw-item.is-on .cw-media img{transform:scale(1)}
.cw-info{margin-top:1rem;max-width:620px;text-align:center;opacity:0;transform:translateY(10px);transition:opacity .7s ease .12s,transform .7s cubic-bezier(.22,.61,.36,1) .12s}
.cw-item.is-on .cw-info{opacity:1;transform:none}
.cw-title{margin:0 0 .35rem;font-size:1.15rem;font-weight:700;letter-spacing:.02em}
.cw-desc{margin:0 0 .6rem;font-size:.9rem;line-height:1.75;opacity:.76}
.cw-link{display:inline-block;font-size:.84rem;font-weight:600;color:inherit;text-decoration:none;border-bottom:1px solid currentColor;padding-bottom:1px;opacity:.85}
.cw-link:hover{opacity:1}
.cw-ctrl{display:flex;align-items:center;justify-content:center;gap:.7rem;margin-top:1.5rem}
.cw-nav{width:30px;height:30px;display:flex;align-items:center;justify-content:center;padding:0;border:1px solid rgba(128,128,128,.35);border-radius:999px;background:transparent;color:inherit;font-size:1rem;line-height:1;cursor:pointer;opacity:.7;transition:opacity .25s,transform .25s,background-color .25s}
.cw-nav:hover{opacity:1;transform:scale(1.08);background:rgba(128,128,128,.12)}
.cw-dots{display:flex;align-items:center;justify-content:center;gap:7px}
.cw-dot{width:8px;height:8px;padding:0;border:0;border-radius:999px;background:rgba(128,128,128,.45);cursor:pointer;transition:width .35s,background-color .35s}
.cw-dot.is-on{width:22px;background:currentColor;opacity:.85}
.cw-more{display:flex;justify-content:center;align-items:center;width:100%;margin:0 auto 2rem;text-align:center}
.cw-more>a{margin:0 auto}
@media (prefers-reduced-motion:reduce){.cw-item,.cw-media img,.cw-info,.cw-nav,.cw-dot{transition:none}.cw-item{transform:none;opacity:1}.cw-info{opacity:1;transform:none}}
</style>
<script>
(function(){
  var root=document.querySelector('.cw-hero');
  if(!root)return;
  var items=[].slice.call(root.querySelectorAll('.cw-item'));
  var dots=[].slice.call(root.querySelectorAll('.cw-dot'));
  var n=items.length;
  if(!n)return;
  var i=0,dir=1,timer=null;
  var iv=parseInt(root.getAttribute('data-interval'),10)||5200;
  var reduce=window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  function show(k){
    i=((k%n)+n)%n;
    items.forEach(function(el,x){var on=x===i;el.classList.toggle('is-on',on);el.setAttribute('aria-hidden',on?'false':'true');});
    dots.forEach(function(d,x){var on=x===i;d.classList.toggle('is-on',on);d.setAttribute('aria-selected',on?'true':'false');});
  }
  function tick(){
    if(i>=n-1)dir=-1;else if(i<=0)dir=1;
    show(i+dir);
  }
  function start(){if(reduce||timer!==null)return;timer=setInterval(tick,iv);}
  function stop(){if(timer!==null){clearInterval(timer);timer=null;}}
  root.addEventListener('mouseenter',stop);
  root.addEventListener('mouseleave',start);
  root.addEventListener('focusin',stop);
  root.addEventListener('focusout',start);
  var prev=root.querySelector('.cw-prev'),next=root.querySelector('.cw-next');
  if(prev)prev.addEventListener('click',function(){stop();show(i-1);start();});
  if(next)next.addEventListener('click',function(){stop();show(i+1);start();});
  dots.forEach(function(d,x){d.addEventListener('click',function(){stop();show(x);start();});});
  show(0);start();
})();
</script>
