<!DOCTYPE html>
<html lang="en" dir="ltr" id="html-root">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adaileh Car Care Center | العدايلة للعناية بالسيارات</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800&family=Outfit:wght@300;400;600;700;800&family=Noto+Kufi+Arabic:wght@400;600;700;800&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            navy: '#0f172a',
            navyDark: '#070b14',
            navyCard: '#162038',
            silver: '#c0c4cc',
            crimson: '#e11d48',
            crimsonDark: '#be123c'
          },
          fontFamily: {
            crest: ['"Cinzel"', '"Noto Kufi Arabic"', 'serif'],
            sans: ['"Outfit"', '"Noto Kufi Arabic"', 'sans-serif'],
            arabic: ['"Noto Kufi Arabic"', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    body { background-color: #070b14; color: #F8FAFC; font-family: 'Outfit', 'Noto Kufi Arabic', sans-serif; scroll-behavior: smooth; }
    .crimson-gradient { background: linear-gradient(135deg, #e11d48 0%, #9f1239 100%); }
    .silver-text { background: linear-gradient(180deg, #FFFFFF 0%, #c0c4cc 60%, #8b92a0 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
    .glass-panel { background: rgba(22, 32, 56, 0.75); backdrop-filter: blur(14px); border: 1px solid rgba(192, 196, 204, 0.14); }
    .card-glow { transition: all 0.3s ease; }
    .card-glow:hover { transform: translateY(-5px); border-color: rgba(225, 29, 72, 0.6); box-shadow: 0 15px 35px -10px rgba(225, 29, 72, 0.3); }
  </style>
</head>
<body class="selection:bg-crimson selection:text-white">

  <!-- Reusable SVG Defs for Metallic Gradients -->
  <svg width="0" height="0" class="absolute">
    <defs>
      <linearGradient id="chromeGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#ffffff" />
        <stop offset="35%" stop-color="#d8dce3" />
        <stop offset="50%" stop-color="#7d8492" />
        <stop offset="75%" stop-color="#f1f5f9" />
        <stop offset="100%" stop-color="#94a3b8" />
      </linearGradient>
      <linearGradient id="shieldBg" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#1e293b" />
        <stop offset="100%" stop-color="#090d16" />
      </linearGradient>
      <linearGradient id="redAccent" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#e11d48" />
        <stop offset="100%" stop-color="#fb7185" />
      </linearGradient>
    </defs>
  </svg>

  <!-- Top Contact & Social Bar -->
  <div class="bg-navy border-b border-silver/15 text-xs py-2.5 px-4">
    <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center gap-4 text-silver">
        <span>📍 <span data-en="Amman, Jordan" data-ar="عمّان، الأردن">Amman, Jordan</span></span>
        <span class="hidden sm:inline">|</span>
        <a href="tel:+962790000000" class="hover:text-crimson transition font-semibold text-white">📞 +962 79 000 0000</a>
      </div>
      <div class="flex items-center gap-4">
        <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="text-silver hover:text-white font-semibold flex items-center gap-1.5 transition">
          <span class="text-crimson">📘</span>
          <span data-en="Follow us on Facebook" data-ar="تابعنا على فيسبوك">Follow us on Facebook</span>
        </a>
        <button onclick="toggleLang()" id="lang-btn" class="bg-white/10 hover:bg-crimson text-white px-3 py-1 rounded-full text-xs font-bold transition">
          العربية
        </button>
      </div>
    </div>
  </div>

  <!-- Main Sticky Navigation with Top-Left Winged Crest Logo -->
  <header class="sticky top-0 z-50 glass-panel border-b border-silver/15">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-24 flex items-center justify-between">
      
      <!-- Top-Left Winged Shield Logo -->
      <a href="#" class="flex items-center gap-3 group">
        <svg viewBox="0 0 260 150" class="h-16 sm:h-20 w-auto drop-shadow-[0_4px_12px_rgba(0,0,0,0.8)]">
          <!-- Left Wing -->
          <polygon points="82,42 12,42 22,55 82,55" fill="url(#chromeGrad)" />
          <polygon points="82,60 24,60 34,73 82,73" fill="url(#chromeGrad)" />
          <polygon points="82,78 38,78 48,90 82,90" fill="url(#chromeGrad)" />
          <!-- Right Wing -->
          <polygon points="178,42 248,42 238,55 178,55" fill="url(#chromeGrad)" />
          <polygon points="178,60 236,60 226,73 178,73" fill="url(#chromeGrad)" />
          <polygon points="178,78 222,78 212,90 178,90" fill="url(#chromeGrad)" />
          <!-- Outer Metallic Shield -->
          <path d="M130,12 L182,26 L182,72 C182,102 130,124 130,124 C130,124 78,102 78,72 L78,26 Z" fill="url(#chromeGrad)" />
          <!-- Inner Dark Navy Shield -->
          <path d="M130,17 L176,29 L176,71 C176,97 130,117 130,117 C130,117 84,97 84,71 L84,29 Z" fill="url(#shieldBg)" />
          <!-- Crimson Inner Shield Outline -->
          <path d="M130,21 L172,32 L172,70 C172,93 130,112 130,112 C130,112 88,93 88,70 L88,32 Z" fill="none" stroke="#e11d48" stroke-width="2.2" />
          <!-- Stylized Silver 'A' -->
          <path d="M130,30 L102,96 L115,96 L130,56 L145,96 L158,96 Z" fill="url(#chromeGrad)" />
          <!-- Dynamic Car Silhouette Swoosh Across Shield -->
          <path d="M74,84 C98,64 156,63 186,78 C164,71 106,72 78,90 Z" fill="url(#chromeGrad)" />
          <path d="M84,90 C112,76 154,75 182,84 C156,81 114,82 88,95 Z" fill="url(#redAccent)" />
          <!-- Sparkle Stars -->
          <path d="M158,50 L160,56 L166,58 L160,60 L158,66 L156,60 L150,58 L156,56 Z" fill="#ffffff" />
          <path d="M180,20 L181.5,24.5 L186,26 L181.5,27.5 L180,32 L178.5,27.5 L174,26 L178.5,24.5 Z" fill="#ffffff" />
        </svg>

        <div class="flex flex-col">
          <span class="font-crest text-xl sm:text-2xl font-extrabold tracking-widest silver-text leading-none" data-en="ADAILEH" data-ar="العدايلة">ADAILEH</span>
          <div class="flex items-center gap-1.5 mt-1">
            <span class="h-[2px] w-3 sm:w-5 bg-crimson inline-block"></span>
            <span class="text-[9px] sm:text-[10px] uppercase tracking-[0.22em] text-silver font-semibold" data-en="CAR CARE CENTER" data-ar="للعناية بالسيارات">CAR CARE CENTER</span>
            <span class="h-[2px] w-3 sm:w-5 bg-crimson inline-block"></span>
          </div>
        </div>
      </a>

      <nav class="hidden lg:flex items-center gap-7 text-sm font-semibold text-silver">
        <a href="#services" class="hover:text-white transition" data-en="Services" data-ar="خدماتنا">Services</a>
        <a href="#ai-advisor" class="hover:text-white transition" data-en="Smart Price Estimator" data-ar="المستشار الذكي والأسعار">Smart Price Estimator</a>
        <a href="#pillars" class="hover:text-white transition" data-en="Our Standards" data-ar="معاييرنا">Our Standards</a>
        <a href="#location" class="hover:text-white transition" data-en="Location & Contact" data-ar="الموقع والتواصل">Location & Contact</a>
      </nav>

      <div class="flex items-center gap-3">
        <a href="#ai-advisor" class="crimson-gradient text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-full shadow-lg shadow-crimson/30 hover:opacity-95 transition" data-en="Book Appointment" data-ar="احجز موعدك الآن">
          Book Appointment
        </a>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative overflow-hidden py-16 lg:py-24 border-b border-silver/15" style="background: radial-gradient(circle at 80% 20%, rgba(225, 29, 72, 0.16), transparent 50%), linear-gradient(180deg, #070b14 0%, #0f172a 100%);">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid lg:grid-cols-12 gap-12 items-center">
      
      <div class="lg:col-span-7 space-y-6">
        <div class="inline-flex items-center gap-2 bg-crimson/15 border border-crimson/40 text-silver px-4 py-1.5 rounded-full text-xs uppercase tracking-widest font-bold">
          <span class="text-crimson">✦</span>
          <span data-en="CLEANER • SHINIER • LONGER" data-ar="نظافة أعمق • لمعان أقوى • حماية أطول">CLEANER • SHINIER • LONGER</span>
        </div>
        <h1 class="text-4xl sm:text-6xl font-extrabold leading-tight tracking-tight text-white" data-en="Executive Automotive Protection & Detailing." data-ar="حماية وتلميع احترافي بمعايير عالمية.">
          Executive Automotive Protection & Detailing.
        </h1>
        <p class="text-silver text-base sm:text-lg max-w-2xl leading-relaxed" data-en="At Adaileh Car Care Center, we combine German & American surface chemistry, 9H Nano-Ceramic technology, and self-healing PPF armor with master craftsmanship to keep your vehicle in showroom condition." data-ar="في مركز العدايلة للعناية بالسيارات، نجمع بين أحدث تقنيات النانو سيراميك (9H)، وأفلام الحماية الشفافة (PPF) ذاتية المعالجة، والمواد الألمانية والأمريكية المعتمدة لنحافظ على سيارتك بحالة الوكالة.">
          At Adaileh Car Care Center, we combine German & American surface chemistry, 9H Nano-Ceramic technology, and self-healing PPF armor with master craftsmanship to keep your vehicle in showroom condition.
        </p>

        <div class="flex flex-wrap gap-4 pt-2">
          <a href="#ai-advisor" class="crimson-gradient text-white font-bold px-8 py-4 rounded-full shadow-xl shadow-crimson/30 hover:opacity-95 transition" data-en="Launch Smart Package Advisor →" data-ar="ابدأ فحص الباقة الذكي لسيارتك ←">
            Launch Smart Package Advisor →
          </a>
          <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="bg-white/5 hover:bg-white/10 border border-silver/25 text-white font-semibold px-7 py-4 rounded-full transition" data-en="View Our Work on Facebook" data-ar="شاهد أعمالنا على فيسبوك">
            View Our Work on Facebook
          </a>
        </div>

        <!-- 5 Brand Pillars from Design Sheet -->
        <div id="pillars" class="grid grid-cols-5 gap-2 pt-6 border-t border-silver/15 max-w-xl text-center">
          <div class="p-2 rounded-xl bg-white/5 border border-white/10">
            <div class="text-crimson text-lg">✦</div>
            <div class="text-[10px] font-bold tracking-wider uppercase text-silver mt-1" data-en="CLEAN" data-ar="تنظيف">CLEAN</div>
          </div>
          <div class="p-2 rounded-xl bg-white/5 border border-white/10">
            <div class="text-crimson text-lg">🛡️</div>
            <div class="text-[10px] font-bold tracking-wider uppercase text-silver mt-1" data-en="PROTECT" data-ar="حماية">PROTECT</div>
          </div>
          <div class="p-2 rounded-xl bg-white/5 border border-white/10">
            <div class="text-crimson text-lg">🚘</div>
            <div class="text-[10px] font-bold tracking-wider uppercase text-silver mt-1" data-en="DETAIL" data-ar="تفصيل">DETAIL</div>
          </div>
          <div class="p-2 rounded-xl bg-white/5 border border-white/10">
            <div class="text-crimson text-lg">💎</div>
            <div class="text-[10px] font-bold tracking-wider uppercase text-silver mt-1" data-en="PREMIUM" data-ar="فخامة">PREMIUM</div>
          </div>
          <div class="p-2 rounded-xl bg-white/5 border border-white/10">
            <div class="text-crimson text-lg">🤝</div>
            <div class="text-[10px] font-bold tracking-wider uppercase text-silver mt-1" data-en="TRUST" data-ar="ثقة">TRUST</div>
          </div>
        </div>
      </div>

      <!-- Large Featured Crest Showcase Card -->
      <div class="lg:col-span-5">
        <div class="glass-panel rounded-3xl p-8 shadow-2xl space-y-6 border border-silver/25 text-center relative overflow-hidden">
          <!-- Large Winged Crest Emblem -->
          <div class="flex flex-col items-center justify-center py-2">
            <svg viewBox="0 0 260 140" class="w-64 sm:w-72 h-auto drop-shadow-[0_10px_25px_rgba(0,0,0,0.9)]">
              <polygon points="82,42 12,42 22,55 82,55" fill="url(#chromeGrad)" />
              <polygon points="82,60 24,60 34,73 82,73" fill="url(#chromeGrad)" />
              <polygon points="82,78 38,78 48,90 82,90" fill="url(#chromeGrad)" />
              <polygon points="178,42 248,42 238,55 178,55" fill="url(#chromeGrad)" />
              <polygon points="178,60 236,60 226,73 178,73" fill="url(#chromeGrad)" />
              <polygon points="178,78 222,78 212,90 178,90" fill="url(#chromeGrad)" />
              <path d="M130,12 L182,26 L182,72 C182,102 130,124 130,124 C130,124 78,102 78,72 L78,26 Z" fill="url(#chromeGrad)" />
              <path d="M130,17 L176,29 L176,71 C176,97 130,117 130,117 C130,117 84,97 84,71 L84,29 Z" fill="url(#shieldBg)" />
              <path d="M130,21 L172,32 L172,70 C172,93 130,112 130,112 C130,112 88,93 88,70 L88,32 Z" fill="none" stroke="#e11d48" stroke-width="2.5" />
              <path d="M130,30 L102,96 L115,96 L130,56 L145,96 L158,96 Z" fill="url(#chromeGrad)" />
              <path d="M74,84 C98,64 156,63 186,78 C164,71 106,72 78,90 Z" fill="url(#chromeGrad)" />
              <path d="M84,90 C112,76 154,75 182,84 C156,81 114,82 88,95 Z" fill="url(#redAccent)" />
              <path d="M158,50 L160,56 L166,58 L160,60 L158,66 L156,60 L150,58 L156,56 Z" fill="#ffffff" />
              <path d="M180,20 L181.5,24.5 L186,26 L181.5,27.5 L180,32 L178.5,27.5 L174,26 L178.5,24.5 Z" fill="#ffffff" />
            </svg>
            <div class="font-crest text-3xl font-extrabold tracking-widest silver-text mt-2">ADAILEH</div>
            <div class="flex items-center justify-center gap-2 mt-1">
              <span class="h-[2px] w-8 bg-crimson"></span>
              <span class="text-xs tracking-[0.25em] text-silver font-semibold">CAR CARE CENTER</span>
              <span class="h-[2px] w-8 bg-crimson"></span>
            </div>
          </div>

          <div class="space-y-2.5 text-left rtl:text-right text-sm pt-2 border-t border-silver/15">
            <div class="p-3.5 rounded-2xl bg-navyDark/90 border border-white/10 flex justify-between items-center">
              <span class="font-bold text-white" data-en="9H Graphene & Ceramic" data-ar="نانو سيراميك وجرافين 9H">9H Graphene & Ceramic</span>
              <span class="text-crimson font-bold text-xs" data-en="5-Yr Warranty" data-ar="كفالة 5 سنوات">5-Yr Warranty</span>
            </div>
            <div class="p-3.5 rounded-2xl bg-navyDark/90 border border-white/10 flex justify-between items-center">
              <span class="font-bold text-white" data-en="Self-Healing PPF Armor" data-ar="أفلام حماية شفافة PPF">Self-Healing PPF Armor</span>
              <span class="text-crimson font-bold text-xs" data-en="10-Yr Warranty" data-ar="كفالة 10 سنوات">10-Yr Warranty</span>
            </div>
          </div>

          <div class="flex flex-col sm:flex-row gap-3">
            <a href="tel:+962790000000" class="flex-1 bg-white/10 hover:bg-white/15 text-center py-3 rounded-xl text-xs font-bold text-white transition" data-en="📞 Call Center" data-ar="📞 اتصال مباشر">
              📞 Call Center
            </a>
            <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="flex-1 crimson-gradient text-center py-3 rounded-xl text-xs font-bold text-white transition" data-en="📘 Facebook Page" data-ar="📘 صفحتنا على فيسبوك">
              📘 Facebook Page
            </a>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- Core International Services Grid -->
  <section id="services" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center max-w-3xl mx-auto mb-14">
      <span class="text-xs font-bold uppercase tracking-widest text-crimson" data-en="Professional Auto Detailing & Car Care" data-ar="خدمات العناية الفائقة بالسيارات">Professional Auto Detailing & Car Care</span>
      <h2 class="text-3xl sm:text-5xl font-extrabold text-white mt-2" data-en="Engineered Surface Treatments" data-ar="حلول متكاملة لحماية وتلميع سيارتك">Engineered Surface Treatments</h2>
    </div>

    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-7">
      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-crimson/15 border border-crimson/40 flex items-center justify-center text-2xl mb-5">🛡️</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-crimson" data-en="Surface Armor" data-ar="الدرع الواقي">Surface Armor</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Paint Protection Film (PPF)" data-ar="أفلام الحماية الشفافة (PPF)">Paint Protection Film (PPF)</h3>
          <p class="text-sm text-silver mt-3 leading-relaxed" data-en="Optical-clear TPU film that absorbs stone chips, road rash, and scratches with heat-activated self-healing technology." data-ar="أفلام حماية أمريكية أصلية (TPU) تحمي طلاء الوكالة من الحصى والخدوش مع خاصية المعالجة الذاتية بالحرارة.">
            Optical-clear TPU film that absorbs stone chips, road rash, and scratches with heat-activated self-healing technology.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-silver" data-en="10-Year Official Warranty" data-ar="كفالة رسمية 10 سنوات">10-Year Official Warranty</span>
          <a href="#ai-advisor" class="text-crimson font-bold hover:underline" data-en="Get Quote →" data-ar="احسب التكلفة ←">Get Quote →</a>
        </div>
      </div>

      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-crimson/15 border border-crimson/40 flex items-center justify-center text-2xl mb-5">💎</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-crimson" data-en="Liquid Glass" data-ar="اللمعان الزجاجي">Liquid Glass</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="9H Nano-Ceramic & Graphene" data-ar="نانو سيراميك وجرافين (9H)">9H Nano-Ceramic & Graphene</h3>
          <p class="text-sm text-silver mt-3 leading-relaxed" data-en="Super-hydrophobic coating delivering mirror-like depth, UV oxidation defense, and effortless self-cleaning properties." data-ar="طبقة زجاجية صلبة تحمي الطلاء من أشعة الشمس والأمطار الحمضية وتمنح السيارة لمعاناً مائياً فائقاً.">
            Super-hydrophobic coating delivering mirror-like depth, UV oxidation defense, and effortless self-cleaning properties.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-silver" data-en="Multi-Layer Application" data-ar="تطبيق متعدد الطبقات">Multi-Layer Application</span>
          <a href="#ai-advisor" class="text-crimson font-bold hover:underline" data-en="Get Quote →" data-ar="احسب التكلفة ←">Get Quote →</a>
        </div>
      </div>

      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-crimson/15 border border-crimson/40 flex items-center justify-center text-2xl mb-5">✨</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-crimson" data-en="Paint Restoration" data-ar="استعادة لمعة الوكالة">Paint Restoration</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Multi-Stage Paint Correction" data-ar="تصحيح الطلاء وبولش احترافي">Multi-Stage Paint Correction</h3>
          <p class="text-sm text-silver mt-3 leading-relaxed" data-en="Safe machine compounding and polishing to remove up to 95% of swirl marks, holograms, and clear-coat defects." data-ar="إزالة دوائر الغسيل والخدوش السطحية والبهتان بنسبة تصل إلى 95% بأحدث أجهزة التلميع والمواد الألمانية.">
            Safe machine compounding and polishing to remove up to 95% of swirl marks, holograms, and clear-coat defects.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-silver" data-en="Swirl-Free Finish" data-ar="لمعة خالية من الدوائر">Swirl-Free Finish</span>
          <a href="#ai-advisor" class="text-crimson font-bold hover:underline" data-en="Get Quote →" data-
