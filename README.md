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

  <!-- Core Services Grid -->
  <section id="services" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-left rtl:text-right">
    <div class="text-center max-w-3xl mx-auto mb-14">
      <span class="text-xs font-bold uppercase tracking-widest text-electric" data-en="International Car Care Standards" data-ar="خدماتنا بمعايير عالمية">International Car Care Standards</span>
      <h2 class="text-3xl sm:text-5xl font-extrabold text-white mt-2" data-en="Bespoke Automotive Treatments" data-ar="حلول متكاملة للعناية بسيارتك وحمايتها">Bespoke Automotive Treatments</h2>
      <p class="text-titanium text-sm sm:text-base mt-3" data-en="Every vehicle undergoes a multi-point LED paint inspection and pH-neutral decontamination before treatment." data-ar="تخضع كل مركبة لفحص دقيق تحت إضاءة LED مخصصة وإزالة الشوائب بمواد متعادلة الحموضة قبل البدء بالعمل.">
        Every vehicle undergoes a multi-point LED paint inspection and pH-neutral decontamination before treatment.
      </p>
    </div>

    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-7">
      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-electric/15 border border-electric/30 flex items-center justify-center text-2xl mb-5">🛡️</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Surface Armor" data-ar="الدرع الواقي">Surface Armor</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Paint Protection Film (PPF)" data-ar="أفلام الحماية الشفافة (PPF)">Paint Protection Film (PPF)</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Aliphatic TPU film that absorbs rock chips, road debris, and minor abrasions with heat-activated self-healing technology." data-ar="أفلام حماية أمريكية أصلية (TPU) تحمي طلاء الوكالة من الحصى والخدوش والحكات مع خاصية المعالجة الذاتية بالحرارة.">
            Aliphatic TPU film that absorbs rock chips, road debris, and minor abrasions with heat-activated self-healing technology.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Full Body / Front Bikini" data-ar="حماية كاملة أو مقدمة السيارة">Full Body / Front Bikini</span>
          <a href="#ai-advisor" class="text-electric font-bold hover:underline" data-en="Configure →" data-ar="احسب التكلفة ←">Configure →</a>
        </div>
      </div>

      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-electric/15 border border-electric/30 flex items-center justify-center text-2xl mb-5">💎</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Liquid Glass" data-ar="اللمعان الزجاجي">Liquid Glass</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="9H Nano-Ceramic & Graphene" data-ar="نانو سيراميك وجرافين (9H)">9H Nano-Ceramic & Graphene</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Permanent chemical bond creating extreme hydrophobic water-beading, UV oxidation defense, and deep candy-like gloss." data-ar="طبقة زجاجية صلبة تحمي الطلاء من أشعة الشمس والأمطار الحمضية وفضلات الطيور، وتمنح السيارة لمعاناً مائياً فائقاً وسهولة في الغسيل.">
            Permanent chemical bond creating extreme hydrophobic water-beading, UV oxidation defense, and deep candy-like gloss.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Multi-Layer Application" data-ar="تطبيق متعدد الطبقات">Multi-Layer Application</span>
          <a href="#ai-advisor" class="text-electric font-bold hover:underline" data-en="Configure →" data-ar="احسب التكلفة ←">Configure →</a>
        </div>
      </div>

      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-electric/15 border border-electric/30 flex items-center justify-center text-2xl mb-5">✨</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Showroom Restoration" data-ar="استعادة لمعة الوكالة">Showroom Restoration</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Multi-Stage Paint Correction" data-ar="تصحيح الطلاء وبولش على عدة مراحل">Multi-Stage Paint Correction</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Precision machine compounding and jewel-polishing to safely eliminate up to 95% of swirl marks, holograms, and oxidation." data-ar="إزالة دوائر الغسيل والخدوش السطحية والبهتان بنسبة تصل إلى 95% باستخدام أجهزة الروتاري والـ Dual Action ومواد Koch-Chemie و Menzerna.">
            Precision machine compounding and jewel-polishing to safely eliminate up to 95% of swirl marks, holograms, and oxidation.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Digital Paint Gauge Safe" data-ar="فحص رقمي لسماكة الطلاء">Digital Paint Gauge Safe</span>
          <a href="#ai-advisor" class="text-electric font-bold hover:underline" data-en="Configure →" data-ar="احسب التكلفة ←">Configure →</a>
        </div>
      </div>

      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-electric/15 border border-electric/30 flex items-center justify-center text-2xl mb-5">🛋️</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Cabin Sanctuary" data-ar="العناية الداخلية">Cabin Sanctuary</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="VIP Interior Detailing & Steam" data-ar="دراي كلين تفصيلي وتعقيم بالبخار">VIP Interior Detailing & Steam</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Deep extraction of carpets, Alcantara & Nappa leather conditioning, AC vent ozone sterilization, and matte UV dashboard protection." data-ar="تنظيف عميق للمقاعد والأرضيات والسقف، تغذية الجلود الطبيعية لمنع التشقق، وتعقيم فتحات التكييف بالأوزون والبخار الجاف.">
            Deep extraction of carpets, Alcantara & Nappa leather conditioning, AC vent ozone sterilization, and matte UV dashboard protection.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Anti-Bacterial & Odor Free" data-ar="قضاء تام على البكتيريا والروائح">Anti-Bacterial & Odor Free</span>
          <a href="#ai-advisor" class="text-electric font-bold hover:underline" data-en="Configure →" data-ar="احسب التكلفة ←">Configure →</a>
        </div>
      </div>

      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-electric/15 border border-electric/30 flex items-center justify-center text-2xl mb-5">☀️</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Thermal Control" data-ar="العزل الحراري">Thermal Control</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Nano-Ceramic Window Tint" data-ar="تظليل عازل حراري نانو سيراميك">Nano-Ceramic Window Tint</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Blocks up to 99% of harmful UV rays and high infrared solar heat while maintaining crystal-clear night visibility and GPS signal." data-ar="عزل حراري فائق يحجب 99% من الأشعة فوق البنفسجية ويقلل حرارة المقصورة بشكل ملموس مع رؤية ليلية صافية وبدون التأثير على إشارات الهاتف.">
            Blocks up to 99% of harmful UV rays and high infrared solar heat while maintaining crystal-clear night visibility and GPS signal.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Jordan Traffic Law Compliant" data-ar="مطابق للمواصفات والنسب القانونية">Jordan Traffic Law Compliant</span>
          <a href="#ai-advisor" class="text-electric font-bold hover:underline" data-en="Configure →" data-ar="احسب التكلفة ←">Configure →</a>
        </div>
      </div>

      <div class="glass-panel rounded-3xl p-7 card-glow flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-2xl bg-electric/15 border border-electric/30 flex items-center justify-center text-2xl mb-5">⚙️</div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Precision Details" data-ar="التفاصيل الدقيقة">Precision Details</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Engine Bay, Rim & Caliper Care" data-ar="تنظيف المحرك، الجنطات والضواو">Engine Bay, Rim & Caliper Care</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Safe dielectric engine detailing, iron brake-dust decontamination on alloy wheels, and crystal headlight restoration." data-ar="تنظيف آمن لحجرة المحرك بدون مياه مضغوطة، إزالة برادة الحديد عن الجنطات، وتلميع وحماية الأضوية الأمامية.">
            Safe dielectric engine detailing, iron brake-dust decontamination on alloy wheels, and crystal headlight restoration.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Hybrid & EV Safe" data-ar="آمن تماماً لسيارات الهايبرد والكهرباء">Hybrid & EV Safe</span>
          <a href="#ai-advisor" class="text-electric font-bold hover:underline" data-en="Configure →" data-ar="احسب التكلفة ←">Configure →</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Intelligent Package Recommender & Estimator -->
  <section id="ai-advisor" class="py-20 bg-carbon border-y border-white/10 text-left rtl:text-right">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid lg:grid-cols-12 gap-10 items-center">
        
        <div class="lg:col-span-6 space-y-5">
          <span class="text-xs font-bold uppercase tracking-widest text-cyber" data-en="Intelligent Car Care Configurator" data-ar="المستشار الذكي لاختيار الباقة">Intelligent Car Care Configurator</span>
          <h2 class="text-3xl sm:text-4xl font-extrabold text-white" data-en="Find the Exact Treatment Your Car Needs" data-ar="صمّم باقة العناية المثالية لسيارتك خلال ثوانٍ">
            Find the Exact Treatment Your Car Needs
          </h2>

          <div class="space-y-4 pt-2">
            <div>
              <label class="block text-xs font-bold uppercase text-titanium mb-2" data-en="1. Select Vehicle Category:" data-ar="1. اختر فئة وحجم السيارة:">1. Select Vehicle Category:</label>
              <select id="car-size" onchange="calculateSmartQuote()" class="w-full p-3.5 rounded-xl bg-obsidian border border-white/15 text-white text-sm font-semibold focus:border-electric focus:outline-none">
                <option value="1.0">Sedan / Coupe / Hatchback (صالون / هاتشباك)</option>
                <option value="1.25">Mid-Size SUV / Crossover (جيب وسط / كروس أوفر)</option>
                <option value="1.45">Large SUV / 4x4 / Pickup (دفع رباعي كبير / بكب)</option>
              </select>
            </div>

            <div>
              <label class="block text-xs font-bold uppercase text-titanium mb-2" data-en="2. Select Primary Treatment:" data-ar="2. اختر الباقة أو الخدمة الأساسية:">2. Select Primary Treatment:</label>
              <select id="service-type" onchange="calculateSmartQuote()" class="w-full p-3.5 rounded-xl bg-obsidian border border-white/15 text-white text-sm font-semibold focus:border-electric focus:outline-none">
                <option value="detail">VIP Full Interior & Exterior Detailing (دراي كلين شاملة + بولش خارجي)</option>
                <option value="ceramic" selected>9H Nano-Ceramic Package + Paint Correction (نانو سيراميك + تصحيح طلاء)</option>
                <option value="ppf-front">Front-End Self-Healing PPF Package (أفلام حماية لمقدمة السيارة)</option>
                <option value="ppf-full">Full-Body Self-Healing PPF Armor (حماية شفافة كاملة للسيارة)</option>
                <option value="tint">Nano-Ceramic Thermal Window Tint (عازل حراري نانو سيراميك)</option>
              </select>
            </div>

            <div>
              <label class="block text-xs font-bold uppercase text-titanium mb-2" data-en="3. Your Vehicle Make & Model (Optional):" data-ar="3. نوع وموديل السيارة (اختياري):">3. Your Vehicle Make & Model (Optional):</label>
              <input id="car-model" type="text" placeholder="e.g., BMW X5 2025 / Kia EV6 / Mercedes E-Class" class="w-full p-3.5 rounded-xl bg-obsidian border border-white/15 text-white text-sm focus:border-electric focus:outline-none" />
            </div>
          </div>
        </div>

        <div class="lg:col-span-6">
          <div class="glass-panel rounded-3xl p-8 border-2 border-electric/40 space-y-6">
            <div class="flex justify-between items-start">
              <div>
                <span class="text-xs uppercase tracking-widest text-cyber font-bold" data-en="Recommended Protocol" data-ar="الباقة المقترحة لسيارتك">Recommended Protocol</span>
                <h3 id="quote-title" class="text-2xl font-extrabold text-white mt-1">9H Nano-Ceramic Shield</h3>
              </div>
              <span id="quote-time" class="bg-electric/20 text-cyber text-xs font-bold px-3 py-1 rounded-full">⏱️ 1–2 Days</span>
            </div>

            <p id="quote-desc" class="text-sm text-titanium leading-relaxed">
              Includes foam decontamination, clay-bar treatment, 2-stage machine polish to remove swirls, and multi-layer 9H ceramic coating on paint, rims, and glass.
            </p>

            <div class="p-5 rounded-2xl bg-obsidian border border-white/10 flex justify-between items-center">
              <div>
                <span class="text-xs text-titanium block" data-en="Estimated Starting Investment" data-ar="السعر التقديري يبدأ من">Estimated Starting Investment</span>
                <span id="quote-price" class="text-3xl font-extrabold text-cyber">150 JOD</span>
              </div>
              <div class="text-right text-xs text-emerald-400 font-semibold" data-en="✓ Free LED Paint Inspection" data-ar="✓ فحص مجاني للطلاء قبل البدء">
                ✓ Free LED Paint Inspection
              </div>
            </div>

            <div class="grid sm:grid-cols-2 gap-3">
              <button onclick="bookViaWhatsApp()" class="cyber-gradient text-white font-bold py-4 px-5 rounded-xl text-xs sm:text-sm shadow-lg hover:opacity-95 transition flex items-center justify-center gap-2">
                <span>💬</span>
                <span data-en="Book This Package on WhatsApp" data-ar="احجز هذه الباقة عبر واتساب">Book This Package on WhatsApp</span>
              </button>
              <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="bg-white/10 hover:bg-white/20 text-white font-bold py-4 px-5 rounded-xl text-xs sm:text-sm transition flex items-center justify-center gap-2">
                <span>📘</span>
                <span data-en="Inquire via Facebook" data-ar="استفسر عبر صفحة فيسبوك">Inquire via Facebook</span>
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Location & Direct Contact Section -->
  <section id="location" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-left rtl:text-right">
    <div class="grid lg:grid-cols-12 gap-8 items-stretch">
      
      <div class="lg:col-span-5 glass-panel rounded-3xl p-8 flex flex-col justify-between space-y-6">
        <div class="space-y-4">
          <span class="text-xs font-bold uppercase tracking-widest text-electric" data-en="Visit Our Studio" data-ar="تفضل بزيارة مركزنا">Visit Our Studio</span>
          <h2 class="text-3xl font-extrabold text-white" data-en="Location & Direct Contact" data-ar="الموقع وأرقام التواصل">Location & Direct Contact</h2>
          <p class="text-sm text-titanium" data-en="Drop by for a complimentary paint thickness check and consultation with our detailing specialists." data-ar="تفضل بزيارتنا لإجراء فحص مجاني لطلاء سيارتك واستشارة خبرائنا حول أفضل حلول الحناية والحماية.">
            Drop by for a complimentary paint thickness check and consultation with our detailing specialists.
          </p>

          <div class="space-y-4 pt-3 text-sm">
            <div class="flex items-start gap-3">
              <span class="text-electric text-lg">📍</span>
              <div>
                <div class="font-bold text-white" data-en="Studio Address" data-ar="العنوان">Studio Address</div>
                <div class="text-titanium" data-en="Amman, Jordan — Adaileh Car Care Center" data-ar="الأردن، عمّان — مركز العدايلة للعناية بالسيارات">Amman, Jordan — Adaileh Car Care Center</div>
              </div>
            </div>

            <div class="flex items-start gap-3">
              <span class="text-electric text-lg">📞</span>
              <div>
                <div class="font-bold text-white" data-en="Direct Phone & WhatsApp" data-ar="الهاتف والواتساب المباشر">Direct Phone & WhatsApp</div>
                <a href="tel:+962790000000" class="text-cyber font-bold hover:underline">+962 79 000 0000</a>
              </div>
            </div>

            <div class="flex items-start gap-3">
              <span class="text-electric text-lg">🕒</span>
              <div>
                <div class="font-bold text-white" data-en="Working Hours" data-ar="ساعات العمل">Working Hours</div>
                <div class="text-titanium" data-en="Saturday – Thursday: 9:00 AM – 8:00 PM" data-ar="السبت – الخميس: 9:00 صباحاً – 8:00 مساءً">Saturday – Thursday: 9:00 AM – 8:00 PM</div>
              </div>
            </div>

            <div class="flex items-start gap-3">
              <span class="text-electric text-lg">📘</span>
              <div>
                <div class="font-bold text-white" data-en="Official Facebook Page" data-ar="صفحتنا الرسمية على فيسبوك">Official Facebook Page</div>
                <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="text-cyber font-bold hover:underline">facebook.com/AdailehCarCare</a>
              </div>
            </div>
          </div>
        </div>

        <div class="pt-4 border-t border-white/10 flex flex-wrap gap-3">
          <a href="https://www.google.com/maps/search/?api=1&query=Adaileh+Car+Care+Jordan" target="_blank" rel="noopener noreferrer" class="w-full cyber-gradient text-center py-3.5 rounded-xl text-xs font-bold text-white shadow-lg" data-en="🗺️ Open Location in Google Maps" data-ar="🗺️ افتح الموقع على خرائط جوجل (Google Maps)">
            🗺️ Open Location in Google Maps
          </a>
        </div>
      </div>

      <div class="lg:col-span-7 glass-panel rounded-3xl overflow-hidden min-h-[380px] border border-white/10">
        <iframe
          title="Adaileh Car Care Map"
          src="https://www.google.com/maps?q=Amman,Jordan&output=embed"
          class="w-full h-full min-h-[380px] border-0 grayscale invert opacity-90 contrast-125"
          loading="lazy">
        </iframe>
      </div>

    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-obsidian border-t border-white/10 py-10 text-center text-xs text-titanium">
    <div class="max-w-7xl mx-auto px-4 flex flex-col sm:flex-row justify-between items-center gap-4">
      <div class="font-bold text-white">
        © 2026 ADAILEH CAR CARE CENTER (العدايلة للعناية بالسيارات). All Rights Reserved.
      </div>
      <div class="flex items-center gap-5">
        <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="hover:text-cyber transition">Facebook</a>
        <a href="tel:+962790000000" class="hover:text-cyber transition">+962 79 000 0000</a>
        <a href="#services" class="hover:text-cyber transition">Services</a>
      </div>
    </div>
  </footer>

  <script>
    let isArabic = false;
    const WHATSAPP_NUMBER = "962790000000";

    const packageData = {
      "detail": {
        enTitle: "VIP Full Interior & Exterior Detailing",
        arTitle: "باقة الدراي كلين الشاملة والبولش الخارجي VIP",
        enDesc: "Deep steam & ozone cabin sterilization, leather nourishment, clay-bar decontamination, and single-stage gloss enhancement.",
        arDesc: "تنظيف عميق للمقصورة بالبخار والأوزون، ترطيب الجلود، إزالة الخشونة عن الطلاء، وتلميع خارجي يعيد لمعة الوكالة.",
        basePrice: 65,
        enTime: "⏱️ 5–7 Hours",
        arTime: "⏱️ 5–7 ساعات"
      },
      "ceramic": {
        enTitle: "9H Nano-Ceramic & Paint Correction",
        arTitle: "باقة النانو سيراميك 9H وتصحيح الطلاء",
        enDesc: "Includes foam decontamination, 2-stage machine polish to remove swirls, and multi-layer 9H ceramic coating on paint, rims, and glass.",
        arDesc: "تشمل إزالة الشوائب، بولش على مرحلتين لإزالة الدوائر والخدوش، وتطبيق طبقات النانو سيراميك 9H للطلاء والجنطات والزجاج.",
        basePrice: 150,
        enTime: "⏱️ 1–2 Days",
        arTime: "⏱️ 1–2 يوم"
      },
      "ppf-front": {
        enTitle: "Front-End Self-Healing PPF Armor",
        arTitle: "باقة أفلام الحماية الشفافة لمقدمة السيارة (PPF)",
        enDesc: "Optical-clear TPU protection on front bumper, full hood, fenders, headlights, and side mirrors against highway stone chips.",
        arDesc: "حماية شفافة ذاتية المعالجة للصدام الأمامي، غطاء المحرك، الرفارف، الأضوية والمرايا ضد الحصى والخدوش.",
        basePrice: 380,
        enTime: "⏱️ 1–2 Days",
        arTime: "⏱️ 1–2 يوم"
      },
      "ppf-full": {
        enTitle: "Full-Body Self-Healing PPF Armor",
        arTitle: "حماية شفافة كاملة للسيارة (Full Body PPF)",
        enDesc: "Complete bumper-to-bumper aliphatic TPU protection film with 10-year warranty against yellowing, cracking, and road rash.",
        arDesc: "تغليف كامل لجسم السيارة بأفلام الحماية الأمريكية الشفافة مع كفالة لمدة 10 سنوات ضد الاصفرار والتشقق والخدوش.",
        basePrice: 1150,
        enTime: "⏱️ 3–4 Days",
        arTime: "⏱️ 3–4 أيام"
      },
      "tint": {
        enTitle: "Nano-Ceramic Thermal Window Tint",
        arTitle: "تظليل عازل حراري نانو سيراميك للزجاج",
        enDesc: "99% UV rejection and high infrared heat barrier across side and rear windows with crystal-clear night visibility.",
        arDesc: "عزل حراري بنسبة 99% من الأشعة الضارة وتقليل ملموس لحرارة الشمس مع رؤية ليلية فائقة الوضوح.",
        basePrice: 75,
        enTime: "⏱️ 2–3 Hours",
        arTime: "⏱️ 2–3 ساعات"
      }
    };

    function calculateSmartQuote() {
      const sizeMultiplier = parseFloat(document.getElementById('car-size').value);
      const serviceKey = document.getElementById('service-type').value;
      const pkg = packageData[serviceKey];

      const finalPrice = Math.round(pkg.basePrice * sizeMultiplier);
      document.getElementById('quote-title').textContent = isArabic ? pkg.arTitle : pkg.enTitle;
      document.getElementById('quote-desc').textContent = isArabic ? pkg.arDesc : pkg.enDesc;
      document.getElementById('quote-time').textContent = isArabic ? pkg.arTime : pkg.enTime;
      document.getElementById('quote-price').textContent = finalPrice + (isArabic ? " دينار" : " JOD");
    }

    function bookViaWhatsApp() {
      const serviceKey = document.getElementById('service-type').value;
      const pkg = packageData[serviceKey];
      const carModel = document.getElementById('car-model').value || (isArabic ? "غير محدد" : "Not specified");
      const priceText = document.getElementById('quote-price').textContent;

      const message = isArabic
        ? `مرحباً مركز العدايلة للعناية بالسيارات، أرغب بحجز موعد:\n- الخدمة: ${pkg.arTitle}\n- نوع السيارة: ${carModel}\n- السعر التقديري: ${priceText}`
        : `Hello Adaileh Car Care Center, I would like to book an appointment:\n- Package: ${pkg.enTitle}\n- Vehicle: ${carModel}\n- Estimated Quote: ${priceText}`;

      window.open(`https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(message)}`, '_blank');
    }

    function toggleLang() {
      isArabic = !isArabic;
      const root = document.getElementById('html-root');
      root.dir = isArabic ? 'rtl' : 'ltr';
      root.lang = isArabic ? 'ar' : 'en';
      document.getElementById('lang-btn').textContent = isArabic ? 'English' : 'العربية';

      document.querySelectorAll('[data-en]').forEach(el => {
        el.textContent = isArabic ? el.getAttribute('data-ar') : el.getAttribute('data-en');
      });

      calculateSmartQuote();
    }

    calculateSmartQuote();
  </script>
</body>
</html>
