<!DOCTYPE html>
<html lang="en" dir="ltr" id="html-root">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adaileh Car Care Center | العدايلة للعناية بالسيارات</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700;800&family=Noto+Kufi+Arabic:wght@400;600;700;800&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            obsidian: '#0B0D12',
            carbon: '#131722',
            slateCard: '#1C2230',
            electric: '#00A8FF',
            cyber: '#00E5FF',
            titanium: '#94A3B8'
          },
          fontFamily: {
            sans: ['"Outfit"', '"Noto Kufi Arabic"', 'sans-serif'],
            arabic: ['"Noto Kufi Arabic"', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    body { background-color: #0B0D12; color: #F8FAFC; font-family: 'Outfit', 'Noto Kufi Arabic', sans-serif; scroll-behavior: smooth; }
    .cyber-gradient { background: linear-gradient(135deg, #00A8FF 0%, #0062FF 100%); }
    .glass-panel { background: rgba(28, 34, 48, 0.75); backdrop-filter: blur(14px); border: 1px solid rgba(255, 255, 255, 0.08); }
    .card-glow { transition: all 0.3s ease; }
    .card-glow:hover { transform: translateY(-5px); border-color: rgba(0, 168, 255, 0.5); box-shadow: 0 15px 35px -10px rgba(0, 168, 255, 0.25); }

    .logo-crop-header { width: 48px; height: 48px; overflow: hidden; border-radius: 12px; background: #131722; display: flex; align-items: center; justify-content: center; box-shadow: 0 4px 14px rgba(0,0,0,0.5); border: 1px solid rgba(0,168,255,0.4); flex-shrink: 0; }
    .logo-crop-header img { width: 100%; height: 100%; object-fit: cover; }
    
    .logo-crop-hero { width: 100%; max-width: 280px; height: 180px; overflow: hidden; border-radius: 20px; background: #131722; margin: 0 auto; box-shadow: 0 12px 30px rgba(0,0,0,0.65); border: 2px solid rgba(0,168,255,0.5); display: flex; align-items: center; justify-content: center; }
    .logo-crop-hero img { width: 100%; height: 100%; object-fit: cover; }
  </style>
</head>
<body class="selection:bg-electric selection:text-white">

  <!-- Top Contact & Social Bar -->
  <div class="bg-carbon border-b border-white/10 text-xs py-2.5 px-4">
    <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center gap-4 text-titanium">
        <span>📍 <span data-en="Amman, Jordan" data-ar="عمّان، الأردن">Amman, Jordan</span></span>
        <span class="hidden sm:inline">|</span>
        <a href="tel:+962790000000" class="hover:text-cyber transition font-semibold text-white">📞 +962 79 000 0000</a>
      </div>
      <div class="flex items-center gap-4">
        <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="text-electric hover:text-cyber font-semibold flex items-center gap-1.5 transition">
          <span>📘</span>
          <span data-en="Follow us on Facebook" data-ar="تابعنا على فيسبوك">Follow us on Facebook</span>
        </a>
        <button onclick="toggleLang()" id="lang-btn" class="bg-white/10 hover:bg-white/20 text-white px-3 py-1 rounded-full text-xs font-bold transition">
          العربية
        </button>
      </div>
    </div>
  </div>

  <!-- Main Sticky Navigation -->
  <header class="sticky top-0 z-50 glass-panel border-b border-white/10">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-24 flex items-center justify-between">
      
      <a href="#" class="flex items-center gap-3.5 group">
        <div class="logo-crop-header">
          <img src="Adaileh_Car_Care_Center_Logo_Print_4800px.png" alt="Adaileh Car Care Center Logo" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/><circle cx=\'7.5\' cy=\'14.5\' r=\'1.5\'/><circle cx=\'16.5\' cy=\'14.5\' r=\'1.5\'/></svg>'" />
        </div>
        <div>
          <div class="font-extrabold text-lg sm:text-xl tracking-tight text-white" data-en="ADAILEH CAR CARE" data-ar="العدايلة للعناية بالسيارات">ADAILEH CAR CARE</div>
          <div class="text-[10px] uppercase tracking-widest text-electric font-semibold" data-en="International Detailing Studio" data-ar="استوديو العناية الفائقة بالسيارات">International Detailing Studio</div>
        </div>
      </a>

      <nav class="hidden md:flex items-center gap-7 text-sm font-semibold text-titanium">
        <a href="#services" class="hover:text-white transition" data-en="Services" data-ar="خدماتنا">Services</a>
        <a href="#ai-advisor" class="hover:text-white transition" data-en="Smart Price Estimator" data-ar="المستشار الذكي والأسعار">Smart Price Estimator</a>
        <a href="#location" class="hover:text-white transition" data-en="Location & Contact" data-ar="الموقع والتواصل">Location & Contact</a>
      </nav>

      <div class="flex items-center gap-3">
        <a href="#ai-advisor" class="cyber-gradient text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-full shadow-lg shadow-electric/25 hover:opacity-95 transition" data-en="Book Appointment" data-ar="احجز موعدك الآن">
          Book Appointment
        </a>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative overflow-hidden py-20 lg:py-28 border-b border-white/10" style="background: radial-gradient(circle at 80% 20%, rgba(0, 168, 255, 0.18), transparent 50%), linear-gradient(180deg, #0B0D12 0%, #131722 100%);">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid lg:grid-cols-12 gap-12 items-center">
      
      <div class="lg:col-span-7 space-y-6 text-left rtl:text-right">
        <div class="inline-flex items-center gap-2 bg-electric/15 border border-electric/40 text-cyber px-4 py-1.5 rounded-full text-xs uppercase tracking-widest font-bold">
          <span>⚡</span>
          <span data-en="Precision Automotive Aesthetics & Protection" data-ar="أحدث تقنيات الحماية والتلميع العالمية">Precision Automotive Aesthetics & Protection</span>
        </div>
        <h1 class="text-4xl sm:text-6xl font-extrabold leading-tight tracking-tight text-white" data-en="Uncompromising Gloss. Engineered Protection." data-ar="لمعان لا مثيل له. حماية هندسية فائقة لسيارتك.">
          Uncompromising Gloss. Engineered Protection.
        </h1>
        <p class="text-titanium text-base sm:text-lg max-w-2xl leading-relaxed" data-en="At Adaileh Car Care, we combine German & American surface chemistry, 9H Nano-Ceramic technology, and self-healing PPF with master craftsmanship to keep your vehicle in showroom condition." data-ar="في مركز العدايلة للعناية بالسيارات، نجمع بين أحدث تقنيات النانو سيراميك (9H)، وأفلام الحماية الشفافة (PPF) ذاتية المعالجة، والمواد الألمانية والأمريكية المعتمدة لنحافظ على سيارتك بحالة الوكالة.">
          At Adaileh Car Care, we combine German & American surface chemistry, 9H Nano-Ceramic technology, and self-healing PPF with master craftsmanship to keep your vehicle in showroom condition.
        </p>

        <div class="flex flex-wrap gap-4 pt-2">
          <a href="#ai-advisor" class="cyber-gradient text-white font-bold px-8 py-4 rounded-full shadow-xl shadow-electric/25 hover:opacity-95 transition" data-en="Launch Smart Package Advisor →" data-ar="ابدأ فحص الباقة الذكي لسيارتك ←">
            Launch Smart Package Advisor →
          </a>
          <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="bg-white/5 hover:bg-white/10 border border-white/15 text-white font-semibold px-7 py-4 rounded-full transition" data-en="View Our Work on Facebook" data-ar="شاهد أعمالنا على فيسبوك">
            View Our Work on Facebook
          </a>
        </div>

        <div class="grid grid-cols-3 gap-4 pt-6 border-t border-white/10 max-w-lg">
          <div>
            <div class="text-2xl sm:text-3xl font-extrabold text-cyber">9H+</div>
            <div class="text-xs text-titanium" data-en="Ceramic Hardness" data-ar="صلابة النانو سيراميك">Ceramic Hardness</div>
          </div>
          <div>
            <div class="text-2xl sm:text-3xl font-extrabold text-cyber">10 Yrs</div>
            <div class="text-xs text-titanium" data-en="PPF Warranty" data-ar="كفالة أفلام الحماية">PPF Warranty</div>
          </div>
          <div>
            <div class="text-2xl sm:text-3xl font-extrabold text-cyber">100%</div>
            <div class="text-xs text-titanium" data-en="Swirl-Free Guarantee" data-ar="ضمان خلو من الخدوش">Swirl-Free Guarantee</div>
          </div>
        </div>
      </div>

      <!-- Featured Emblem Card -->
      <div class="lg:col-span-5">
        <div class="glass-panel rounded-3xl p-7 shadow-2xl space-y-6 border border-electric/30 text-center">
          
          <div class="logo-crop-hero">
            <img src="Adaileh_Car_Care_Center_Logo_Print_4800px.png" alt="Adaileh Car Care Center Official Emblem" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\' width=\'80\' height=\'80\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/><circle cx=\'7.5\' cy=\'14.5\' r=\'1.5\'/><circle cx=\'16.5\' cy=\'14.5\' r=\'1.5\'/></svg>'" />
          </div>

          <div class="space-y-3 text-sm text-left rtl:text-right pt-2 border-t border-white/10">
            <div class="p-4 rounded-2xl bg-obsidian/80 border border-white/10 flex justify-between items-center">
              <div>
                <div class="font-bold text-white text-xs" data-en="9H Graphene & Ceramic Coating" data-ar="طبقات النانو سيراميك والجرافين 9H">9H Graphene & Ceramic Coating</div>
              </div>
              <span class="text-cyber font-bold text-xs" data-en="3–5 Yr Warranty" data-ar="كفالة 3-5 سنوات">3–5 Yr Warranty</span>
            </div>

            <div class="p-4 rounded-2xl bg-obsidian/80 border border-white/10 flex justify-between items-center">
              <div>
                <div class="font-bold text-white text-xs" data-en="Self-Healing PPF Armor" data-ar="أفلام الحماية الشفافة (PPF)">Self-Healing PPF Armor</div>
              </div>
              <span class="text-cyber font-bold text-xs" data-en="TPU Optical Clear" data-ar="شفافية مطلقة TPU">TPU Optical Clear</span>
            </div>
          </div>

          <div class="flex flex-col sm:flex-row gap-3">
            <a href="tel:+962790000000" class="flex-1 bg-white/10 hover:bg-white/15 text-center py-3 rounded-xl text-xs font-bold text-white transition" data-en="📞 Call Direct" data-ar="📞 اتصال مباشر">
              📞 Call Direct
            </a>
            <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="flex-1 cyber-gradient text-center py-3 rounded-xl text-xs font-bold text-white transition" data-en="📘 Message on Facebook" data-ar="📘 راسلنا على فيسبوك">
              📘 Message on Facebook
            </a>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- Core Services Grid with Embedded Professional Photos -->
  <section id="services" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-left rtl:text-right">
    <div class="text-center max-w-3xl mx-auto mb-14">
      <span class="text-xs font-bold uppercase tracking-widest text-electric" data-en="International Car Care Standards" data-ar="خدماتنا بمعايير عالمية">International Car Care Standards</span>
      <h2 class="text-3xl sm:text-5xl font-extrabold text-white mt-2" data-en="Bespoke Automotive Treatments" data-ar="حلول متكاملة للعناية بسيارتك وحمايتها">Bespoke Automotive Treatments</h2>
      <p class="text-titanium text-sm sm:text-base mt-3" data-en="Every vehicle undergoes a multi-point LED paint inspection and pH-neutral decontamination before treatment." data-ar="تخضع كل مركبة لفحص دقيق تحت إضاءة LED مخصصة وإزالة الشوائب بمواد متعادلة الحموضة قبل البدء بالعمل.">
        Every vehicle undergoes a multi-point LED paint inspection and pH-neutral decontamination before treatment.
      </p>
    </div>

    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-7">
      <!-- Service 1: PPF -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="https://images.unsplash.com/photo-1617814076367-b759c7d7e738?auto=format&fit=crop&w=800&q=80" alt="Paint Protection Film" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Surface Armor" data-ar="الدرع الواقي">Surface Armor</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Paint Protection Film (PPF)" data-ar="أفلام الحماية الشفافة (PPF)">Paint Protection Film (PPF)</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Aliphatic TPU film that absorbs rock chips, road debris, and minor abrasions with heat-activated self-healing technology." data-ar="أفلام حماية أمريكية أصلية (TPU) تحمي طلاء الوكالة من الحصى والخدوش والحكات مع خاصية المعالجة الذاتية بالحرارة.">
            Aliphatic TPU film that absorbs rock chips, road debris, and minor abrasions with heat-activated self-healing technology.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Full Body / Front Bikini" data-ar="حماية كاملة أو مقدمة السيارة">Full Body / Front Bikini</span>
          <a href="#ai-advisor" class="text
