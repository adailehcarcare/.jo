<!DOCTYPE html>
<html lang="ar" dir="rtl" id="html-root">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>مركز العضايلة للعناية بالسيارات | Adaileh Car Care Center</title>
  <meta name="description" content="مركز العضايلة للعناية بالسيارات في الكرك - وكيل معتمد لمنتجات سينفنكو الألمانية. خدمات دراي كلين، نانوسيراميك 9H، بولش احترافي، تنظيف كتلايزر ومنظومة احتراق." />
  <meta name="keywords" content="دراي كلين سيارات, زيوت سينفنكو الألمانية, محسنات أداء السيارات, تنظيف الكتلايزر, منظومة الاحتراق, بولش سيارات احترافي, نانوسيراميك 9H, مركز العضايلة الكرك" />
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700;800&family=Noto+Kufi+Arabic:wght@400;600;700;800;900&display=swap" rel="stylesheet">
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
            sans: ['"Noto Kufi Arabic"', '"Outfit"', 'sans-serif'],
            arabic: ['"Noto Kufi Arabic"', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    body { background-color: #0B0D12; color: #F8FAFC; font-family: 'Noto Kufi Arabic', 'Outfit', sans-serif; scroll-behavior: smooth; }
    .cyber-gradient { background: linear-gradient(135deg, #00A8FF 0%, #0062FF 100%); }
    .glass-panel { background: rgba(19, 23, 34, 0.82); backdrop-filter: blur(16px); border: 1px solid rgba(255, 255, 255, 0.1); }
    .card-glow { transition: all 0.35s ease; cursor: pointer; }
    .card-glow:hover { transform: translateY(-6px); border-color: rgba(0, 229, 255, 0.55); box-shadow: 0 18px 40px -12px rgba(0, 168, 255, 0.3); }
    .card-active { border-color: #00E5FF !important; background: rgba(0, 229, 255, 0.15) !important; transform: scale(1.03); box-shadow: 0 0 25px rgba(0, 229, 255, 0.45); }

    select, input {
      background-color: #0B0D12 !important;
      color: #FFFFFF !important;
      border: 1px solid rgba(0, 168, 255, 0.35) !important;
    }
    select option {
      background-color: #131722 !important;
      color: #FFFFFF !important;
      padding: 12px;
    }

    .logo-crop-header { width: 58px; height: 52px; overflow: hidden; border-radius: 12px; background: #ffffff; display: flex; align-items: center; justify-content: center; box-shadow: 0 4px 14px rgba(0,0,0,0.5); border: 1px solid rgba(0,168,255,0.45); flex-shrink: 0; }
    .logo-crop-header img { width: 100%; height: 100%; object-fit: contain; background: #ffffff; }

    .hero-bg-section {
      position: relative;
      background-color: #0B0D12;
      background-image: 
        linear-gradient(to bottom, rgba(11, 13, 18, 0.55) 0%, rgba(11, 13, 18, 0.78) 65%, #0B0D12 100%),
        radial-gradient(circle at 50% 35%, rgba(0, 168, 255, 0.18), transparent 65%),
        url('hero-bg.jpg'),
        url('watermarked_img_5315418272674494559.jpg');
      background-size: cover;
      background-position: center center;
      background-repeat: no-repeat;
    }
  </style>
</head>
<body class="selection:bg-electric selection:text-white">

  <!-- Top Contact Bar -->
  <div class="bg-carbon border-b border-white/10 text-xs py-2.5 px-4">
    <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center gap-4 text-titanium">
        <span>📍 <span data-en="Al-Karak, Jordan" data-ar="الكرك، الأردن">الكرك، الأردن</span></span>
        <span class="hidden sm:inline">|</span>
        <a href="tel:+962776999555" class="hover:text-cyber transition font-semibold text-white" dir="ltr">📞 +962 77 699 9555</a>
      </div>
      <div class="flex items-center gap-4">
        <button onclick="toggleLang()" id="lang-btn" class="bg-electric/20 hover:bg-electric/30 border border-electric/40 text-cyber px-3.5 py-1 rounded-full text-xs font-bold transition">
          English
        </button>
      </div>
    </div>
  </div>

  <!-- Main Sticky Navigation -->
  <header class="sticky top-0 z-50 glass-panel border-b border-white/10">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-24 flex items-center justify-between">
      
      <a href="#" class="flex items-center gap-3.5 group">
        <div class="logo-crop-header">
          <img src="Chrome ADAILEH Car Care Emblem.png" alt="Adaileh Car Care Center Logo" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/><circle cx=\'7.5\' cy=\'14.5\' r=\'1.5\'/><circle cx=\'16.5\' cy=\'14.5\' r=\'1.5\'/></svg>'" />
        </div>
        <div>
          <div class="font-extrabold text-lg sm:text-xl tracking-tight text-white" data-en="ADAILEH CAR CARE" data-ar="العضايلة للعناية بالسيارات">العضايلة للعناية بالسيارات</div>
          <div class="text-[11px] tracking-wide text-cyber font-semibold" data-en="Authorized German Senfineco Dealer" data-ar="وكيل معتمد لمنتجات سينفنكو الألمانية">وكيل معتمد لمنتجات سينفنكو الألمانية</div>
        </div>
      </a>

      <nav class="hidden md:flex items-center gap-8 text-sm font-bold text-titanium">
        <a href="#services" class="hover:text-cyber transition" data-en="Services" data-ar="خدماتنا">خدماتنا</a>
        <a href="#ai-advisor" class="hover:text-cyber transition" data-en="Smart Estimator" data-ar="المستشار الذكي والأسعار">المستشار الذكي والأسعار</a>
        <a href="#location" class="hover:text-cyber transition" data-en="Location & Contact" data-ar="الموقع والتواصل">الموقع والتواصل</a>
      </nav>

      <div class="flex items-center gap-3">
        <a href="#ai-advisor" class="cyber-gradient text-white text-xs sm:text-sm font-bold px-6 py-3 rounded-full shadow-lg shadow-electric/30 hover:opacity-95 transition" data-en="Book Now" data-ar="احجز موعدك الآن">
          احجز موعدك الآن
        </a>
      </div>
    </div>
  </header>

  <!-- Hero Section with Custom "العضايلة" License Plate Car Background -->
  <section class="hero-bg-section min-h-[82vh] flex items-center justify-center py-24 lg:py-32 border-b border-white/10">
    <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-7">
      
      <div class="inline-flex items-center gap-2 bg-obsidian/80 backdrop-blur-md border border-cyber/40 text-cyber px-5 py-2 rounded-full text-xs sm:text-sm font-bold shadow-lg">
        <span>⚡</span>
        <span data-en="Precision German Engineering • Showroom Perfection" data-ar="دقة الهندسة الألمانية • لمعان الوكالة الفائق">دقة الهندسة الألمانية • لمعان الوكالة الفائق</span>
      </div>

      <h1 class="text-4xl sm:text-6xl lg:text-7xl font-black leading-tight tracking-tight text-white drop-shadow-[0_5px_25px_rgba(0,0,0,0.9)]" data-en="Uncompromising Gloss. Maximum Engine Power." data-ar="فخامة اللمعان.. وقوة الأداء الألماني لسيارتك في الكرك">
        فخامة اللمعان.. وقوة الأداء الألماني لسيارتك في الكرك
      </h1>

      <p class="text-gray-200 text-base sm:text-xl max-w-3xl mx-auto leading-relaxed font-medium drop-shadow-[0_2px_12px_rgba(0,0,0,0.9)]" data-en="From 9H Nano-Ceramic armor and mirror-gloss polishing to original German Senfineco oils, catalytic cleaning, and combustion tuning—we treat your car like a masterpiece." data-ar="من درع النانوسيراميك 9H والبولش الاحترافي، إلى زيوت ومحسنات سينفنكو الألمانية وتنظيف الكتلايزر ومنظومة الاحتراق — نمنح سيارتك عناية استثنائية بأيدي محترفين.">
        من درع النانوسيراميك 9H والبولش الاحترافي، إلى زيوت ومحسنات سينفنكو الألمانية وتنظيف الكتلايزر ومنظومة الاحتراق — نمنح سيارتك عناية استثنائية بأيدي محترفين.
      </p>

      <!-- Hero Call To Action Buttons -->
      <div class="flex flex-wrap items-center justify-center gap-4 pt-4">
        <a href="#ai-advisor" class="cyber-gradient text-white text-base sm:text-lg font-extrabold px-9 py-4 rounded-full shadow-2xl shadow-electric/40 hover:scale-105 transition duration-300" data-en="Book Your Service Now →" data-ar="احجز خدمتك الآن ←">
          احجز خدمتك الآن ←
        </a>
        <a href="https://wa.me/962776999555" target="_blank" class="glass-panel hover:bg-white/15 border border-cyber/40 text-white text-base sm:text-lg font-bold px-8 py-4 rounded-full transition duration-300 flex items-center gap-2" data-en="💬 Direct WhatsApp" data-ar="💬 تواصل عبر واتساب">
          💬 تواصل عبر واتساب
        </a>
      </div>

    </div>
  </section>

  <!-- Interactive Statistics Section -->
  <section class="py-16 bg-carbon border-b border-white/10 -mt-10 relative z-10 max-w-6xl mx-auto rounded-3xl shadow-2xl px-4">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
      
      <!-- Stat Card 1 -->
      <div onclick="triggerStatAction(this)" class="glass-panel p-9 rounded-2xl card-glow border border-white/10 relative overflow-hidden group">
        <h4 class="text-5xl sm:text-6xl font-black text-cyber tracking-tight">5+</h4>
        <p class="text-white mt-3 font-extrabold text-lg sm:text-xl" data-en="Years of Excellence & Experience" data-ar="سنوات من الخبرة والتميز">سنوات من الخبرة والتميز</p>
        <span class="text-xs text-electric block mt-3 font-semibold opacity-80" data-en="⚡ Click to Calculate Price" data-ar="⚡ اضغط لحساب تكلفة باقتك">⚡ اضغط لحساب تكلفة باقتك</span>
      </div>

      <!-- Stat Card 2 -->
      <div onclick="triggerStatAction(this)" class="glass-panel p-9 rounded-2xl card-glow border border-white/10 relative overflow-hidden group">
        <h4 class="text-5xl sm:text-6xl font-black text-cyber tracking-tight">100%</h4>
        <p class="text-white mt-3 font-extrabold text-lg sm:text-xl" data-en="Original German Materials" data-ar="مواد ألمانية أصلية ومضمونة">مواد ألمانية أصلية ومضمونة</p>
        <span class="text-xs text-electric block mt-3 font-semibold opacity-80" data-en="⚡ Click to Calculate Price" data-ar="⚡ اضغط لحساب تكلفة باقتك">⚡ اضغط لحساب تكلفة باقتك</span>
      </div>

      <!-- Stat Card 3 -->
      <div onclick="triggerStatAction(this)" class="glass-panel p-9 rounded-2xl card-glow border border-white/10 relative overflow-hidden group">
        <h4 class="text-5xl sm:text-6xl font-black text-cyber tracking-tight">1500+</h4>
        <p class="text-white mt-3 font-extrabold text-lg sm:text-xl" data-en="Vehicles Cared For" data-ar="سيارة تم العناية بها">سيارة تم العناية بها</p>
        <span class="text-xs text-electric block mt-3 font-semibold opacity-80" data-en="⚡ Click to Calculate Price" data-ar="⚡ اضغط لحساب تكلفة باقتك">⚡ اضغط لحساب تكلفة باقتك</span>
      </div>

    </div>
  </section>

  <!-- Core Services Grid (With All Custom Service Photos Integrated) -->
  <section id="services" class="py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-left rtl:text-right">
    <div class="text-center max-w-3xl mx-auto mb-16">
      <span class="text-xs font-bold uppercase tracking-widest text-cyber" data-en="Professional Automotive Solutions" data-ar="خدماتنا المتخصصة">خدماتنا المتخصصة</span>
      <h2 class="text-3xl sm:text-5xl font-extrabold text-white mt-2" data-en="Our Specialized Services" data-ar="خدمات العناية الفائقة بالمركبات">خدمات العناية الفائقة بالمركبات</h2>
      <p class="text-titanium text-sm sm:text-base mt-3" data-en="Explore our complete range of German engine care and showroom detailing services." data-ar="نقدم تشكيلة متكاملة من خدمات العناية بالمحرك والتفصيل الداخلي والخارجي بأعلى المعايير العالمية.">
        نقدم تشكيلة متكاملة من خدمات العناية بالمحرك والتفصيل الداخلي والخارجي بأعلى المعايير العالمية.
      </p>
    </div>

    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
      
      <!-- Service 1: Dry Clean (دراي كلين وتعقيم داخلي فاخر) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-64 border border-white/10 bg-carbon">
            <img src="watermarked_img_16156778816188013572.jpg" onerror="this.onerror=null; this.src='dryclean.jpg';" alt="VIP Interior Dry Clean" class="w-full h-full object-cover object-center hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="VIP Cabin Sanctuary" data-ar="العناية الفاخرة بالمقصورة">العناية الفاخرة بالمقصورة</span>
          <h3 class="text-xl font-extrabold text-white mt-1" data-en="VIP Interior Dry Clean & Sterilization" data-ar="دراي كلين وتعقيم داخلي فاخر">دراي كلين وتعقيم داخلي فاخر</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Deep multi-stage steam and ozone extraction for seats, carpets, headliners, and dashboard to eliminate stubborn stains and odors." data-ar="تنظيف وتعقيم داخلي عميق بالبخار والأوزون للمقاعد، الأرضيات، والسقف لإزالة البقع الصعبة والروائح الكريهة واستعادة انتعاش الوكالة.">
            تنظيف وتعقيم داخلي عميق بالبخار والأوزون للمقاعد، الأرضيات، والسقف لإزالة البقع الصعبة والروائح الكريهة واستعادة انتعاش الوكالة.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium font-semibold" data-en="Steam & Ozone Sterilization" data-ar="تعقيم شامل بالبخار والأوزون">تعقيم شامل بالبخار والأوزون</span>
          <a href="#ai-advisor" onclick="selectServiceInAdvisor('detail')" class="text-cyber font-bold hover:underline" data-en="Book Now →" data-ar="احجز الآن ←">احجز الآن ←</a>
        </div>
      </div>

      <!-- Service 2: German Senfineco Oils (زيوت سينفنكو الألمانية المعتمدة) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-64 border border-white/10 bg-carbon">
            <img src="watermarked_img_546972973034933559.jpg" onerror="this.onerror=null; this.src='oils.jpg';" alt="German Senfineco Motor Oils" class="w-full h-full object-cover object-center hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="German Engineering" data-ar="الهندسة الألمانية الأصلية">الهندسة الألمانية الأصلية</span>
          <h3 class="text-xl font-extrabold text-white mt-1" data-en="German Senfineco Motor Oils" data-ar="زيوت سينفنكو الألمانية المعتمدة">زيوت سينفنكو الألمانية المعتمدة</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Original German Senfineco synthetic motor oils engineered for extreme thermal stability, reduced friction, and maximum engine lifespan." data-ar="توفير وفحص زيوت محركات سينفنكو الألمانية الأصلية لضمان ثبات حراري فائق، تقليل الاحتكاك، وأقصى حماية وعمر افتراضي للمحرك.">
            توفير وفحص زيوت محركات سينفنكو الألمانية الأصلية لضمان ثبات حراري فائق، تقليل الاحتكاك، وأقصى حماية وعمر افتراضي للمحرك.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium font-semibold" data-en="100% German Import" data-ar="وكيل معتمد - ألماني أصلي">وكيل معتمد - ألماني أصلي</span>
          <a href="#ai-advisor" onclick="selectServiceInAdvisor('oils')" class="text-cyber font-bold hover:underline" data-en="Book Now →" data-ar="احجز الآن ←">احجز الآن ←</a>
        </div>
      </div>

      <!-- Service 3: Performance Additives (محسنات أداء وعزم المحرك) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-64 border border-white/10 bg-carbon">
            <img src="watermarked_img_6931112452009587996.jpg" onerror="this.onerror=null; this.src='additives.jpg';" alt="Performance Additives" class="w-full h-full object-cover object-center hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Power & Efficiency Boost" data-ar="طاقة وكفاءة مضاعفة">طاقة وكفاءة مضاعفة</span>
          <h3 class="text-xl font-extrabold text-white mt-1" data-en="Advanced Performance Additives" data-ar="محسنات أداء وعزم المحرك">محسنات أداء وعزم المحرك</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Advanced German chemical additives designed to reduce friction, clean fuel systems, and boost engine horsepower and responsiveness." data-ar="مواد وإضافات ألمانية متطورة لتقليل الاحتكاك، تنظيف نظام الوقود، واستعادة عزم وسرعة استجابة المحرك مع توفير استهلاك الوقود.">
            مواد وإضافات ألمانية متطورة لتقليل الاحتكاك، تنظيف نظام الوقود، واستعادة عزم وسرعة استجابة المحرك مع توفير استهلاك الوقود.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium font-semibold" data-en="Maximum Horsepower" data-ar="استعادة عزم وسرعة السيارة">استعادة عزم وسرعة السيارة</span>
          <a href="#ai-advisor" onclick="selectServiceInAdvisor('additives')" class="text-cyber font-bold hover:underline" data-en="Book Now →" data-ar="احجز الآن ←">احجز الآن ←</a>
        </div>
      </div>

      <!-- Service 4: Catalytic Converter Cleaning (تنظيف وعلاج الكتلايزر المتطور) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-64 border border-white/10 bg-carbon">
            <img src="watermarked_img_10286483525483324879.jpg" onerror="this.onerror=null; this.src='catalytic.jpg';" alt="Catalytic Converter Cleaning" class="w-full h-full object-cover object-center hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Exhaust & Emission Care" data-ar="صيانة نظام العادم والبيئة">صيانة نظام العادم والبيئة</span>
          <h3 class="text-xl font-extrabold text-white mt-1" data-en="Catalytic Converter Deep Cleaning" data-ar="تنظيف وعلاج الكتلايزر المتطور">تنظيف وعلاج الكتلايزر المتطور</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Specialized machine and chemical cleaning to dissolve carbon deposits from the catalytic converter, restoring torque and lowering emissions." data-ar="خدمة متخصصة لتنظيف وتفكيك الترسبات الكربونية من الكتلايزر ودبة البيئة لتحسين عزم السيارة، تقليل الانبعاثات، وحل مشاكل Check Engine.">
            خدمة متخصصة لتنظيف وتفكيك الترسبات الكربونية من الكتلايزر ودبة البيئة لتحسين عزم السيارة، تقليل الانبعاثات، وحل مشاكل Check Engine.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium font-semibold" data-en="Carbon Removal" data-ar="إزالة الكربون واستعادة العزم">إزالة الكربون واستعادة العزم</span>
          <a href="#ai-advisor" onclick="selectServiceInAdvisor('catalytic')" class="text-cyber font-bold hover:underline" data-en="Book Now →" data-ar="احجز الآن ←">احجز الآن ←</a>
        </div>
      </div>

      <!-- Service 5: Combustion System Service (خدمة منظومة الاحتراق الشاملة) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-64 border border-white/10 bg-carbon">
            <img src="watermarked_img_14695952003525036368.jpg" onerror="this.onerror=null; this.src='combustion.jpg';" alt="Combustion Chamber Service" class="w-full h-full object-cover object-center hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Engine Chamber Tuning" data-ar="تنقية غرفة الاحتراق">تنقية غرفة الاحتراق</span>
          <h3 class="text-xl font-extrabold text-white mt-1" data-en="Combustion Chamber & Valve Service" data-ar="خدمة منظومة الاحتراق الشاملة">خدمة منظومة الاحتراق الشاملة</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Comprehensive cleaning and maintenance for injectors, valves, and the combustion chamber to ensure smooth performance and fuel economy." data-ar="تنظيف وصيانة شاملة للبخاخات، الصمامات، وغرفة الاحتراق بأحدث الأجهزة لضمان احتراق مثالي وأداء سلس واستهلاك اقتصادي للوقود.">
            تنظيف وصيانة شاملة للبخاخات، الصمامات، وغرفة الاحتراق بأحدث الأجهزة لضمان احتراق مثالي وأداء سلس واستهلاك اقتصادي للوقود.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium font-semibold" data-en="Optimal Fuel Economy" data-ar="احتراق مثالي وتوفير وقود">احتراق مثالي وتوفير وقود</span>
          <a href="#ai-advisor" onclick="selectServiceInAdvisor('combustion')" class="text-cyber font-bold hover:underline" data-en="Book Now →" data-ar="احجز الآن ←">احجز الآن ←</a>
        </div>
      </div>

      <!-- Service 6: Professional Polish (بولش وتصحيح طلاء احترافي) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-64 border border-white/10 bg-carbon">
            <img src="firstphoto1.png" onerror="this.onerror=null; this.src='secondphoto2.png';" alt="Professional Polish" class="w-full h-full object-cover object-center hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Showroom Paint Restoration" data-ar="استعادة لمعة الوكالة">استعادة لمعة الوكالة</span>
          <h3 class="text-xl font-extrabold text-white mt-1" data-en="Multi-Stage Professional Polish" data-ar="بولش وتصحيح طلاء احترافي">بولش وتصحيح طلاء احترافي</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Multi-stage exterior machine polishing and paint correction to remove wash swirls, surface scratches, and restore deep showroom gloss." data-ar="تلميع ومعالجة خارجية احترافية على عدة مراحل لإزالة دوائر الغسيل، الخدوش السطحية، والأكسدة وإعادة لمعة المرآة الأصلية للطلاء.">
            تلميع ومعالجة خارجية احترافية على عدة مراحل لإزالة دوائر الغسيل، الخدوش السطحية، والأكسدة وإعادة لمعة المرآة الأصلية للطلاء.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium font-semibold" data-en="Mirror Gloss Finish" data-ar="لمعان مرآتي خالٍ من الدوائر">لمعان مرآتي خالٍ من الدوائر</span>
          <a href="#ai-advisor" onclick="selectServiceInAdvisor('polish')" class="text-cyber font-bold hover:underline" data-en="Book Now →" data-ar="احجز الآن ←">احجز الآن ←</a>
        </div>
      </div>

      <!-- Service 7: Nano-Ceramic (نانوسيراميك حماية طلاء 9H) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden lg:col-span-3 lg:max-w-2xl lg:mx-auto">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-72 border border-white/10 bg-carbon">
            <img src="thirdphoto3.png" alt="9H Nano-Ceramic Shield" class="w-full h-full object-cover object-center hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Ultimate Liquid Glass Armor" data-ar="الدرع الكريستالي الفائق">الدرع الكريستالي الفائق</span>
          <h3 class="text-2xl font-extrabold text-white mt-1" data-en="9H Nano-Ceramic Armor Coating" data-ar="نانوسيراميك حماية طلاء 9H">نانوسيراميك حماية طلاء 9H</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Advanced 9H crystalline protection layer giving your car's body ultra-high gloss, hydrophobic water-repellency, and extreme resistance against oxidation and harsh weather." data-ar="طبقة حماية كريستالية متطورة (9H) تمنح هيكل السيارة لمعاناً فائقاً، خاصية طرد المياه والأوساخ (هيدروفوبيك)، ومقاومة عالية للأكسدة والعوامل الجوية.">
            طبقة حماية كريستالية متطورة (9H) تمنح هيكل السيارة لمعاناً فائقاً، خاصية طرد المياه والأوساخ (هيدروفوبيك)، ومقاومة عالية للأكسدة والعوامل الجوية.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium font-semibold" data-en="9H Hydrophobic Armor" data-ar="حماية كريستالية 9H ومقاومة للمياه">حماية كريستالية 9H ومقاومة للمياه</span>
          <a href="#ai-advisor" onclick="selectServiceInAdvisor('ceramic')" class="text-cyber font-bold hover:underline" data-en="Book Now →" data-ar="احجز الآن ←">احجز الآن ←</a>
        </div>
      </div>

    </div>
  </section>

  <!-- Intelligent Package Recommender & Estimator Section -->
  <section id="ai-advisor" class="py-24 bg-carbon border-y border-white/10 text-left rtl:text-right">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-16">
        <span class="text-xs font-bold uppercase tracking-widest text-cyber" data-en="Smart Configurator" data-ar="المستشار الذكي لاختيار الباقة">المستشار الذكي لاختيار الباقة</span>
        <h2 class="text-3xl sm:text-5xl font-extrabold text-white mt-3" data-en="Design the Ideal Care Package for Your Car in Seconds" data-ar="صمّم باقة العناية المثالية لسيارتك خلال ثوانٍ">
          صمّم باقة العناية المثالية لسيارتك خلال ثوانٍ
        </h2>
      </div>

      <div class="grid lg:grid-cols-12 gap-10 items-center">
        
        <!-- Inputs -->
        <div class="lg:col-span-6 space-y-6 glass-panel p-8 sm:p-10 rounded-3xl border border-white/15 shadow-2xl">
          <div>
            <label class="block text-sm font-bold uppercase text-titanium mb-3" data-en="1. Select Vehicle Category:" data-ar="1. اختر فئة وحجم السيارة:">1. اختر فئة وحجم السيارة:</label>
            <select id="car-size" onchange="calculateSmartQuote()" class="w-full p-4 rounded-2xl bg-obsidian text-white text-base font-semibold focus:border-electric focus:outline-none">
              <option value="1.0" data-en="Sedan / Coupe / Hatchback" data-ar="صالون / هاتشباك (Sedan / Hatchback)">صالون / هاتشباك (Sedan / Hatchback)</option>
              <option value="1.25" data-en="Mid-Size SUV / Crossover" data-ar="جيب وسط / كروس أوفر (Mid-Size SUV)">جيب وسط / كروس أوفر (Mid-Size SUV)</option>
              <option value="1.45" data-en="Large SUV / 4x4 / Pickup" data-ar="دفع رباعي كبير / بكب (Large SUV / 4x4)">دفع رباعي كبير / بكب (Large SUV / 4x4)</option>
            </select>
          </div>

          <div>
            <label class="block text-sm font-bold uppercase text-titanium mb-3" data-en="2. Select Primary Treatment:" data-ar="2. اختر الباقة أو الخدمة الأساسية:">2. اختر الباقة أو الخدمة الأساسية:</label>
            <select id="service-type" onchange="calculateSmartQuote()" class="w-full p-4 rounded-2xl bg-obsidian text-white text-base font-semibold focus:border-electric focus:outline-none">
              <option value="detail" data-en="VIP Interior Dry Clean & Sterilization" data-ar="دراي كلين وتعقيم داخلي فاخر">دراي كلين وتعقيم داخلي فاخر</option>
              <option value="oils" data-en="German Senfineco Motor Oils" data-ar="زيوت سينفنكو الألمانية المعتمدة">زيوت سينفنكو الألمانية المعتمدة</option>
              <option value="additives" data-en="Advanced Performance Additives" data-ar="محسنات أداء وعزم المحرك">محسنات أداء وعزم المحرك</option>
              <option value="catalytic" data-en="Catalytic Converter Deep Cleaning" data-ar="تنظيف وعلاج الكتلايزر المتطور">تنظيف وعلاج الكتلايزر المتطور</option>
              <option value="combustion" data-en="Combustion Chamber & Valve Service" data-ar="خدمة منظومة الاحتراق الشاملة">خدمة منظومة الاحتراق الشاملة</option>
              <option value="polish" data-en="Multi-Stage Professional Polish" data-ar="بولش وتصحيح طلاء احترافي">بولش وتصحيح طلاء احترافي</option>
              <option value="ceramic" selected data-en="9H Nano-Ceramic Armor Coating" data-ar="نانوسيراميك حماية طلاء 9H">نانوسيراميك حماية طلاء 9H</option>
            </select>
          </div>

          <div>
            <label class="block text-sm font-bold uppercase text-titanium mb-3" data-en="3. Your Vehicle Make & Model (Optional):" data-ar="3. نوع وموديل السيارة (اختياري):">3. نوع وموديل السيارة (اختياري):</label>
            <input id="car-model" type="text" placeholder="e.g., BMW X5 / Mercedes E-Class / Toyota Camry" class="w-full p-4 rounded-2xl bg-obsidian text-white text-base focus:border-electric focus:outline-none placeholder:text-gray-500" />
          </div>
        </div>

        <!-- Result Card -->
        <div class="lg:col-span-6">
          <div class="glass-panel rounded-3xl p-8 sm:p-10 border-2 border-electric/40 space-y-6 shadow-2xl">
            <div class="flex justify-between items-start gap-4">
              <div>
                <span class="text-xs uppercase tracking-widest text-cyber font-bold" data-en="Recommended Protocol" data-ar="الباقة المقترحة لسيارتك">الباقة المقترحة لسيارتك</span>
                <h3 id="quote-title" class="text-2xl sm:text-3xl font-extrabold text-white mt-1">نانوسيراميك حماية طلاء 9H</h3>
              </div>
              <span id="quote-time" class="bg-electric/20 text-cyber text-xs font-bold px-3.5 py-1.5 rounded-full whitespace-nowrap">⏱️ 1–2 يوم</span>
            </div>

            <p id="quote-desc" class="text-base text-titanium leading-relaxed">
              طبقة نانوسيراميك جزيئية صلبة (9H) توفر درع حماية هيدروفوبيك دائم ضد أشعة الشمس، الأمطار الحمضية، والعوامل البيئية القاسية.
            </p>

            <div class="p-5 rounded-2xl bg-obsidian border border-white/10 flex justify-between items-center">
              <div>
                <span class="text-xs text-titanium block" data-en="Estimated Starting Investment" data-ar="السعر التقديري يبدأ من">السعر التقديري يبدأ من</span>
                <span id="quote-price" class="text-3xl sm:text-4xl font-extrabold text-cyber">150 دينار</span>
              </div>
              <div class="text-right text-xs sm:text-sm text-emerald-400 font-semibold" data-en="✓ Free Inspection Before Start" data-ar="✓ فحص مجاني للسيارة قبل البدء">
                ✓ فحص مجاني للسيارة قبل البدء
              </div>
            </div>

            <div class="grid sm:grid-cols-2 gap-3 pt-2">
              <button onclick="bookViaWhatsApp()" class="cyber-gradient text-white font-bold py-4 px-5 rounded-2xl text-sm shadow-lg hover:opacity-95 transition flex items-center justify-center gap-2">
                <span>💬</span>
                <span data-en="Book Package via WhatsApp" data-ar="احجز هذه الباقة عبر واتساب">احجز هذه الباقة عبر واتساب</span>
              </button>
              <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="bg-white/10 hover:bg-white/20 text-white font-bold py-4 px-5 rounded-2xl text-sm transition flex items-center justify-center gap-2">
                <span>📘</span>
                <span data-en="Inquire via Facebook" data-ar="استفسر عبر صفحة فيسبوك">استفسر عبر صفحة فيسبوك</span>
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Location, Hours & Direct Contact Section -->
  <section id="location" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-left rtl:text-right">
    <div class="grid lg:grid-cols-12 gap-8 items-stretch">
      
      <div class="lg:col-span-5 glass-panel rounded-3xl p-8 flex flex-col justify-between space-y-6">
        <div class="space-y-4">
          <span class="text-xs font-bold uppercase tracking-widest text-electric" data-en="Visit Our Studio" data-ar="تفضل بزيارة مركزنا">تفضل بزيارة مركزنا</span>
          <h2 class="text-3xl font-extrabold text-white" data-en="Location & Direct Contact" data-ar="الموقع وأرقام التواصل">الموقع وأرقام التواصل</h2>
          <p class="text-sm text-titanium" data-en="Drop by for German Senfineco products and professional car care services in Al-Karak." data-ar="تفضل بزيارتنا للحصول على منتجات سينفنكو الألمانية وخدمات العناية الشاملة بالسيارات في الكرك.">
            تفضل بزيارتنا للحصول على منتجات سينفنكو الألمانية وخدمات العناية الشاملة بالسيارات في الكرك.
          </p>

          <div class="space-y-4 pt-3 text-sm">
            <div class="flex items-start gap-3">
              <span class="text-electric text-lg">📍</span>
              <div>
                <div class="font-bold text-white" data-en="Studio Address" data-ar="العنوان">العنوان</div>
                <div class="text-titanium" data-en="Al-Karak, Jordan — Adaileh Car Care Center" data-ar="الأردن، الكرك — مركز العضايلة للعناية بالسيارات">الأردن، الكرك — مركز العضايلة للعناية بالسيارات</div>
              </div>
            </div>

            <div class="flex items-start gap-3">
              <span class="text-electric text-lg">📞</span>
              <div>
                <div class="font-bold text-white" data-en="Direct Phone & WhatsApp" data-ar="الهاتف والواتساب المباشر">الهاتف والواتساب المباشر</div>
                <a href="tel:+962776999555" class="text-cyber font-bold hover:underline" dir="ltr">+962 77 699 9555</a>
              </div>
            </div>

            <div class="flex items-start gap-3">
              <span class="text-electric text-lg">🕒</span>
              <div>
                <div class="font-bold text-white" data-en="Working Hours" data-ar="ساعات العمل">ساعات العمل</div>
                <div class="text-titanium" data-en="Saturday – Thursday: 9:00 AM – 9:00 PM" data-ar="يومياً من الساعة 9:00 صباحاً حتى 9:00 مساءً">يومياً من الساعة 9:00 صباحاً حتى 9:00 مساءً</div>
              </div>
            </div>
          </div>
        </div>

        <div class="pt-4 border-t border-white/10 flex flex-wrap gap-3">
          <a href="https://wa.me/962776999555?text=مرحباً%20مركز%20العضايلة،%20أود%20الاستفسار" target="_blank" class="w-full cyber-gradient text-center py-3.5 rounded-xl text-xs font-bold text-white shadow-lg" data-en="💬 Contact via WhatsApp" data-ar="💬 تواصل عبر واتساب">
            💬 تواصل عبر واتساب
          </a>
        </div>
      </div>

      <div class="lg:col-span-7 glass-panel rounded-3xl overflow-hidden min-h-[380px] border border-white/10">
        <iframe
          title="Adaileh Car Care Map"
          src="https://www.google.com/maps?q=Al-Karak,Jordan&output=embed"
          class="w-full h-full min-h-[380px] border-0 grayscale invert opacity-90 contrast-125"
          loading="lazy">
        </iframe>
      </div>

    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-obsidian border-t border-white/10 py-10 text-center text-xs text-titanium">
    <div class="max-w-7xl mx-auto px-4 flex flex-col sm:flex-row justify-between items-center gap-4">
      <div class="font-bold text-white" data-en="© 2026 ADAILEH CAR CARE CENTER. All Rights Reserved." data-ar="© 2026 مركز العضايلة للعناية بالمركبات - الكرك. جميع الحقوق محفوظة.">
        © 2026 مركز العضايلة للعناية بالمركبات - الكرك. جميع الحقوق محفوظة.
      </div>
      <div class="flex items-center gap-5">
        <a href="tel:+962776999555" class="hover:text-cyber transition">0776999555</a>
        <a href="#services" class="hover:text-cyber transition" data-en="Services" data-ar="الخدمات">الخدمات</a>
      </div>
    </div>
  </footer>

  <script>
    let isArabic = true;
    const WHATSAPP_NUMBER = "962776999555";

    const packageData = {
      "detail": {
        enTitle: "VIP Interior Dry Clean & Sterilization",
        arTitle: "دراي كلين وتعقيم داخلي فاخر",
        enDesc: "Deep multi-stage steam and ozone extraction for seats, carpets, headliners, and dashboard to eliminate stubborn stains and restore freshness.",
        arDesc: "تنظيف وتعقيم داخلي عميق بالبخار والأوزون للمقاعد، الأرضيات، والسقف لإزالة البقع الصعبة والروائح الكريهة واستعادة انتعاش الوكالة.",
        basePrice: 65,
        enTime: "⏱️ 5–7 Hours",
        arTime: "⏱️ 5–7 ساعات"
      },
      "oils": {
        enTitle: "German Senfineco Motor Oils",
        arTitle: "زيوت سينفنكو الألمانية المعتمدة",
        enDesc: "Official German Senfineco synthetic motor oils engineered for extreme thermal stability, reduced friction, and maximum engine lifespan.",
        arDesc: "توفير وفحص زيوت محركات سينفنكو الألمانية الأصلية لضمان ثبات حراري فائق، تقليل الاحتكاك، وأقصى حماية وعمر افتراضي للمحرك.",
        basePrice: 45,
        enTime: "⏱️ 1 Hour",
        arTime: "⏱️ ساعة واحدة"
      },
      "additives": {
        enTitle: "Advanced Performance Additives",
        arTitle: "محسنات أداء وعزم المحرك",
        enDesc: "High-grade German chemical additives designed to clean fuel injectors, boost horsepower, and optimize fuel economy instantly.",
        arDesc: "مواد وإضافات ألمانية متطورة لتقليل الاحتكاك، تنظيف نظام الوقود، واستعادة عزم وسرعة استجابة المحرك.",
        basePrice: 30,
        enTime: "⏱️ 30 Mins",
        arTime: "⏱️ 30 دقيقة"
      },
      "catalytic": {
        enTitle: "Catalytic Converter Deep Cleaning",
        arTitle: "تنظيف وعلاج الكتلايزر المتطور",
        enDesc: "Specialized chemical and steam treatment to dissolve carbon buildup, clear exhaust restrictions, and resolve check-engine issues.",
        arDesc: "خدمة متخصصة لتنظيف وتفكيك الترسبات الكربونية من الكتلايزر لتحسين عزم السيارة وتقليل الانبعاثات.",
        basePrice: 50,
        enTime: "⏱️ 2 Hours",
        arTime: "⏱️ ساعتان"
      },
      "combustion": {
        enTitle: "Combustion Chamber & Valve Service",
        arTitle: "خدمة منظومة الاحتراق الشاملة",
        enDesc: "Professional carbon decarbonization for intake valves, combustion chambers, and fuel systems to ensure optimal engine performance.",
        arDesc: "تنظيف وصيانة شاملة للبخاخات، الصمامات، وغرفة الاحتراق لضمان احتراق مثالي واستهلاك اقتصادي للوقود.",
        basePrice: 40,
        enTime: "⏱️ 1–2 Hours",
        arTime: "⏱️ 1–2 ساعة"
      },
      "polish": {
        enTitle: "Multi-Stage Professional Polish",
        arTitle: "بولش وتصحيح طلاء احترافي",
        enDesc: "Precision multi-stage machine compounding to eliminate swirl marks, oxidation, and scratches, bringing back a deep mirror gloss.",
        arDesc: "تلميع ومعالجة خارجية على عدة مراحل لإزالة دوائر الغسيل، الخدوش السطحية، وإعادة لمعة الوكالة للطلاء.",
        basePrice: 90,
        enTime: "⏱️ 1 Day",
        arTime: "⏱️ يوم واحد"
      },
      "ceramic": {
        enTitle: "9H Nano-Ceramic Armor Coating",
        arTitle: "نانوسيراميك حماية طلاء 9H",
        enDesc: "Permanent 9H molecular bond providing extreme hydrophobic protection against UV rays, acid rain, bird droppings, and harsh weather.",
        arDesc: "طبقة حماية كريستالية متطورة (9H) تمنح هيكل السيارة لمعاناً فائقاً ومقاومة عالية للأكسدة والعوامل الجوية.",
        basePrice: 150,
        enTime: "⏱️ 1–2 Days",
        arTime: "⏱️ 1–2 يوم"
      }
    };

    function selectServiceInAdvisor(serviceKey) {
      const selectEl = document.getElementById('service-type');
      selectEl.value = serviceKey;
      calculateSmartQuote();
    }

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
      const pkg
