<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<meta name="color-scheme" content="dark" />
<title>RPBazzar — FiveM MLO Marketplace | ESX, QB & QBOX Optimized</title>
<meta name="description" content="RPBazzar is the FiveM mega mall — 660+ premium FiveM MLOs optimized for ESX, QB & QBOX. Instant download, drop & use on any FiveM server. Your FiveM MLO marketplace." />
<link rel="canonical" href="https://rpbazzar.com/" />

<!-- Open Graph -->
<meta property="og:type" content="website" />
<meta property="og:title" content="RPBazzar — FiveM MLO Marketplace | ESX, QB & QBOX Optimized" />
<meta property="og:description" content="660+ premium FiveM MLOs. Instant download, drop & use on any FiveM server. ESX, QB & QBOX optimized." />
<meta property="og:url" content="https://rpbazzar.com/" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="RPBazzar — FiveM MLO Marketplace" />
<meta name="twitter:description" content="660+ premium FiveM MLOs. Drop & use on any FiveM server. ESX, QB & QBOX optimized." />

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">

<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: {
      extend: {
        colors: {
          canvas:'#0b0c0e','canvas-dark':'#06070a',card:'#101115',elevated:'#15171a',deep:'#06070a',
          hairline:'#22262c','hairline-strong':'#2d3239','hairline-soft':'#1a1d22',
          ink:'#f5f6f8',body:'#d6d8dd',charcoal:'#d6d8dd',slate:'#a8acb4',mute:'#a8acb4',
          ash:'#8b9099',steel:'#8b9099',stone:'#6b7079',
          'accent-orange':'#d0b070','accent-yellow':'#f59e0b','accent-blue':'#3772cf',
          'accent-green':'#15a877','accent-red':'#e5484d',gold:'#d0b070','gold-deep':'#e6c889',
          ok:'#15a877',warn:'#f59e0b',bad:'#e5484d'
        },
        fontFamily: {
          serif:['Inter','-apple-system','system-ui','sans-serif'],
          sans:['Inter','-apple-system','system-ui','sans-serif'],
          mono:['"JetBrains Mono"','"SF Mono"','Menlo','Consolas','monospace']
        },
        letterSpacing: { display:'-0.025em', tightish:'-0.02em' }
      }
    }
  };
</script>
<style>
  :root{
    color-scheme:dark;
    --canvas:#0b0c0e;--canvas-dark:#06070a;--surface:#15171a;--surface-soft:#101115;--surface-code:#06070a;
    --hairline:#22262c;--hairline-soft:#1a1d22;
    --ink:#f5f6f8;--charcoal:#d6d8dd;--slate:#a8acb4;--steel:#8b9099;--stone:#6b7079;--muted:#4a4f57;
    --brand-gold:#d0b070;--brand-gold-deep:#e6c889;--brand-gold-soft:rgba(208,176,112,0.12);
    --brand-tag:#3772cf;--brand-annotate:#15a877;--brand-warn:#f59e0b;--brand-error:#e5484d;
    --primary:#f5f6f8;--on-primary:#0a0d10;
    --sans:"Inter",-apple-system,system-ui,sans-serif;
    --mono:"JetBrains Mono","SF Mono",Menlo,Consolas,monospace;
    --r-xs:4px;--r-sm:6px;--r-md:8px;--r-lg:12px;--r-xl:16px;--r-full:9999px;
    --shadow-1:rgba(0,0,0,0.4) 0 1px 2px 0;
  }
  html,body{background:var(--canvas);}
  body{font-family:var(--sans);color:var(--ink);-webkit-font-smoothing:antialiased;text-rendering:optimizeLegibility;scroll-behavior:smooth;}
  .font-serif{font-family:var(--sans);font-weight:600;}

  .glow-orange{background:
    radial-gradient(ellipse 900px 320px at 15% 30%,rgba(208,176,112,0.22),transparent 60%),
    radial-gradient(ellipse 700px 280px at 85% 60%,rgba(208,176,112,0.10),transparent 60%),
    radial-gradient(ellipse 600px 220px at 50% 100%,rgba(208,176,112,0.06),transparent 60%);}

  *::-webkit-scrollbar{width:6px;height:6px;}
  *::-webkit-scrollbar-track{background:transparent;}
  *::-webkit-scrollbar-thumb{background:var(--hairline);border-radius:6px;}
  *::-webkit-scrollbar-thumb:hover{background:#2d3239;}

  .pill{display:inline-flex;align-items:center;font-size:11px;letter-spacing:0.02em;padding:3px 10px;border-radius:var(--r-full);font-weight:600;}

  .btn-primary{background:var(--primary);color:var(--on-primary);border:1px solid transparent;border-radius:var(--r-full);padding:11px 22px;font-size:14px;font-weight:600;line-height:1;display:inline-flex;align-items:center;justify-content:center;gap:8px;transition:background .12s ease;cursor:pointer;text-decoration:none;}
  .btn-primary:hover{background:#e8eaee;}
  .btn-gold{background:var(--brand-gold);color:#0a0a0a;border:1px solid transparent;border-radius:var(--r-full);padding:11px 22px;font-size:14px;font-weight:600;line-height:1;display:inline-flex;align-items:center;justify-content:center;gap:8px;transition:background .12s ease;cursor:pointer;text-decoration:none;}
  .btn-gold:hover{background:var(--brand-gold-deep);}
  .btn-ghost{background:var(--surface);color:var(--ink);border:1px solid var(--hairline);border-radius:var(--r-full);padding:11px 20px;font-size:14px;font-weight:500;line-height:1;transition:all .12s ease;cursor:pointer;text-decoration:none;display:inline-flex;align-items:center;gap:8px;}
  .btn-ghost:hover{border-color:var(--ink);}

  .card-base{background:var(--surface-soft);border:1px solid var(--hairline);border-radius:var(--r-lg);}
  .card-link{transition:border-color .12s,box-shadow .12s,transform .12s;text-decoration:none;display:block;}
  .card-link:hover{border-color:rgba(208,176,112,0.55);box-shadow:0 0 0 1px rgba(208,176,112,0.25) inset;transform:translateY(-2px);}

  .eyebrow{font-size:11px;text-transform:uppercase;letter-spacing:0.12em;color:var(--steel);}
  code.inline{font-family:var(--mono);font-size:12px;color:var(--brand-gold);background:rgba(208,176,112,0.08);padding:1px 6px;border-radius:4px;}
  .row-divider{border-top:1px solid var(--hairline);}
  a{color:inherit;}
</style>
</head>
<body class="min-h-screen">

<!-- ============ HERO ============ -->
<section class="relative overflow-hidden">
  <div class="glow-orange absolute inset-x-0 top-0 h-[600px] pointer-events-none"></div>
  <div class="relative px-6 sm:px-8 pt-8 pb-16 max-w-[1100px] mx-auto">

    <!-- top bar -->
    <header class="flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="font-serif text-2xl tracking-tight">RPBazzar<span class="text-accent-orange">.</span></div>
        <span class="text-xs text-ash hidden sm:inline">FiveM MLO Marketplace</span>
      </div>
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="btn-ghost text-[13px] py-2 px-4">Visit store →</a>
    </header>

    <!-- hero copy -->
    <div class="mt-16 max-w-3xl">
      <div class="flex flex-wrap items-center gap-2 mb-6">
        <span class="pill bg-bad/15 text-bad border border-bad/40">ESX</span>
        <span class="pill bg-accent-blue/15 text-accent-blue border border-accent-blue/40">QB</span>
        <span class="pill bg-accent-green/15 text-accent-green border border-accent-green/40">QBOX</span>
        <span class="pill bg-white/5 text-charcoal border border-hairline-strong">Drop &amp; Use</span>
      </div>
      <h1 class="font-serif text-[44px] sm:text-[64px] md:text-[76px] leading-[1.0] tracking-display">
        The FiveM<br/><span class="text-accent-orange">mega mall.</span>
      </h1>
      <p class="mt-6 max-w-xl text-body text-[17px] leading-[1.55]">
        660+ premium <strong class="text-ink">FiveM MLOs</strong> — banks, clubs, restaurants, gang hideouts, police stations &amp; more.
        Optimized for ESX, QB &amp; QBOX. Instant download, drop &amp; use on any FiveM server.
      </p>
      <div class="mt-9 flex flex-wrap items-center gap-3">
        <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="btn-gold">Browse all MLOs →</a>
        <a href="https://rpbazzar.com/collections" target="_blank" rel="noopener" class="btn-ghost">View collections</a>
      </div>
      <p class="mt-4 text-xs text-stone font-mono">// every MLO from <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="text-accent-orange hover:underline">rpbazzar.com</a></p>
    </div>
  </div>
</section>

<div class="px-6 sm:px-8 pb-28 max-w-[1100px] mx-auto space-y-20">

  <!-- ============ STATS ============ -->
  <section>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-3">
      <div class="bg-deep border border-hairline rounded-lg p-4">
        <div class="text-[10px] uppercase tracking-[0.1em] text-ash">FiveM MLOs</div>
        <div class="font-serif text-[34px] leading-none mt-1 tracking-tightish text-accent-orange">660+</div>
      </div>
      <div class="bg-deep border border-hairline rounded-lg p-4">
        <div class="text-[10px] uppercase tracking-[0.1em] text-ash">Collections</div>
        <div class="font-serif text-[34px] leading-none mt-1 tracking-tightish">100</div>
      </div>
      <div class="bg-deep border border-hairline rounded-lg p-4">
        <div class="text-[10px] uppercase tracking-[0.1em] text-ash">Frameworks</div>
        <div class="font-serif text-[34px] leading-none mt-1 tracking-tightish text-accent-green">3</div>
      </div>
      <div class="bg-deep border border-hairline rounded-lg p-4">
        <div class="text-[10px] uppercase tracking-[0.1em] text-ash">Delivery</div>
        <div class="font-serif text-[34px] leading-none mt-1 tracking-tightish text-accent-blue">Instant</div>
      </div>
    </div>
  </section>

  <!-- ============ WHY ============ -->
  <section class="space-y-8">
    <div class="border-b border-hairline pb-3">
      <div class="eyebrow">Why RPBazzar</div>
      <h2 class="font-serif text-[28px] leading-none mt-1 tracking-tightish">Built for FiveM server owners</h2>
    </div>
    <div class="grid sm:grid-cols-3 gap-4">
      <div class="card-base p-6">
        <div class="font-serif text-[18px] text-ink">⚡ Drop &amp; Use</div>
        <p class="mt-2 text-[14px] text-body leading-relaxed">No headaches. Download, drop into <code class="inline">resources/[mlos]</code>, and go live on any FiveM server.</p>
      </div>
      <div class="card-base p-6">
        <div class="font-serif text-[18px] text-ink">🚀 Performance-first</div>
        <p class="mt-2 text-[14px] text-body leading-relaxed">Every MLO is optimized for high performance so your server stays smooth under load.</p>
      </div>
      <div class="card-base p-6">
        <div class="font-serif text-[18px] text-ink">📦 Instant download</div>
        <p class="mt-2 text-[14px] text-body leading-relaxed">Pay once, download instantly. No waiting, no DMs — just your MLO, ready to deploy.</p>
      </div>
    </div>
  </section>

  <!-- ============ CATEGORIES ============ -->
  <section class="space-y-8">
    <div class="border-b border-hairline pb-3">
      <div class="eyebrow">Browse</div>
      <h2 class="font-serif text-[28px] leading-none mt-1 tracking-tightish">Popular MLO categories</h2>
    </div>
    <div class="grid grid-cols-2 md:grid-cols-3 gap-3">
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="card-base card-link p-5">
        <div class="font-serif text-[17px] text-ink">🏦 Banks &amp; Heists</div>
        <div class="text-[12px] text-ash mt-1">High-stakes robbery MLOs</div>
      </a>
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="card-base card-link p-5">
        <div class="font-serif text-[17px] text-ink">🍸 Nightclubs &amp; Bars</div>
        <div class="text-[12px] text-ash mt-1">Lounges, clubs, venues</div>
      </a>
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="card-base card-link p-5">
        <div class="font-serif text-[17px] text-ink">🍔 Restaurants &amp; Food</div>
        <div class="text-[12px] text-ash mt-1">Food court &amp; diners</div>
      </a>
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="card-base card-link p-5">
        <div class="font-serif text-[17px] text-ink">🚔 Police &amp; Gov</div>
        <div class="text-[12px] text-ash mt-1">Stations, training, MRPD</div>
      </a>
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="card-base card-link p-5">
        <div class="font-serif text-[17px] text-ink">🔫 Gang Hideouts</div>
        <div class="text-[12px] text-ash mt-1">Bases, exteriors, turf</div>
      </a>
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="card-base card-link p-5">
        <div class="font-serif text-[17px] text-ink">🏠 Apartments &amp; Homes</div>
        <div class="text-[12px] text-ash mt-1">Interiors &amp; living spaces</div>
      </a>
    </div>
    <p class="text-center text-[13px] text-stone">
      ...and 90+ more collections at <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="text-accent-orange hover:underline font-medium">rpbazzar.com</a>
    </p>
  </section>

  <!-- ============ COMPAT ============ -->
  <section class="space-y-8">
    <div class="border-b border-hairline pb-3">
      <div class="eyebrow">Compatibility</div>
      <h2 class="font-serif text-[28px] leading-none mt-1 tracking-tightish">Works with your framework</h2>
    </div>
    <div class="card-base p-8">
      <p class="text-body text-[15px] max-w-2xl">
        Every MLO on <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="text-accent-orange hover:underline">RPBazzar</a>
        is built and tested for the three frameworks running most FiveM roleplay servers:
      </p>
      <div class="mt-6 flex flex-wrap gap-3">
        <span class="pill bg-bad/15 text-bad border border-bad/40" style="font-size:13px;padding:6px 14px;">ESX</span>
        <span class="pill bg-accent-blue/15 text-accent-blue border border-accent-blue/40" style="font-size:13px;padding:6px 14px;">QB-Core</span>
        <span class="pill bg-accent-green/15 text-accent-green border border-accent-green/40" style="font-size:13px;padding:6px 14px;">QBOX</span>
      </div>
      <div class="mt-6 font-mono text-[13px] text-charcoal bg-deep border border-hairline rounded-md p-4 overflow-x-auto">
        <span class="text-stone"># drop into your server</span><br/>
        C:\fivem\server-data\resources\[mlos]\your_new_mlo<br/>
        <span class="text-stone"># then add to server.cfg</span><br/>
        <span class="text-accent-green">ensure</span> your_new_mlo
      </div>
    </div>
  </section>

  <!-- ============ CTA ============ -->
  <section>
    <div class="card-base p-10 text-center relative overflow-hidden">
      <div class="glow-orange absolute inset-0 pointer-events-none opacity-70"></div>
      <div class="relative">
        <h2 class="font-serif text-[32px] sm:text-[40px] leading-tight tracking-tightish">Ready to build your city?</h2>
        <p class="mt-4 text-body text-[16px] max-w-lg mx-auto">
          Browse 660+ optimized FiveM MLOs and deploy in minutes. Instant download, drop &amp; use.
        </p>
        <div class="mt-8 flex flex-wrap items-center justify-center gap-3">
          <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="btn-gold">Shop RPBazzar →</a>
          <a href="https://rpbazzar.com/collections" target="_blank" rel="noopener" class="btn-ghost">Explore collections</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ============ FOOTER ============ -->
  <footer class="row-divider pt-8 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs text-stone">
    <div>
      <span class="font-serif text-ink">RPBazzar<span class="text-accent-orange">.</span></span>
      &nbsp;— Your FiveM Mega Mall ·
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="text-accent-orange hover:underline">rpbazzar.com</a>
    </div>
    <div class="flex items-center gap-4">
      <a href="https://rpbazzar.com" target="_blank" rel="noopener" class="hover:text-ink">Store</a>
      <a href="https://rpbazzar.com/collections" target="_blank" rel="noopener" class="hover:text-ink">Collections</a>
    </div>
  </footer>

</div>
</body>
</html>
