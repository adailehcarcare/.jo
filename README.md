
<html lang="en" dir="ltr" id="html-root">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adaileh Car Care Center | العضايلة للعناية بالسيارات</title>
  <meta name="keywords" content="دراي كلين سيارات, زيوت سينفنكو الألمانية, محسنات أداء السيارات, تنظيف الكتلايزر, بولش سيارات احترافي, نانوسيراميك 9H, مركز العضايلة الكرك" />
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
    .card-glow { transition: all 0.3s ease; cursor: pointer; }
    .card-glow:hover { transform: translateY(-5px); border-color: rgba(0, 168, 255, 0.5); box-shadow: 0 15px 35px -10px rgba(0, 168, 255, 0.25); }
    .card-active { border-color: #00E5FF !important; background: rgba(0, 229, 255, 0.15) !important; transform: scale(1.03); box-shadow: 0 0 25px rgba(0, 229, 255, 0.4); }

    .logo-crop-header { width: 56px; height: 50px; overflow: hidden; border-radius: 10px; background: #ffffff; display: flex; align-items: center; justify-content: center; box-shadow: 0 4px 14px rgba(0,0,0,0.5); border: 1px solid rgba(0,168,255,0.4); flex-shrink: 0; }
    .logo-crop-header img { width: 100%; height: 100%; object-fit: contain; background: #ffffff; }
    
    .logo-crop-hero { width: 100%; max-width: 280px; height: 180px; overflow: hidden; border-radius: 20px; background: #ffffff; margin: 0 auto; box-shadow: 0 12px 30px rgba(0,0,0,0.65); border: 2px solid rgba(0,168,255,0.5); display: flex; align-items: center; justify-content: center; }
    .logo-crop-hero img { width: 100%; height: 100%; object-fit: contain; background: #ffffff; }
  </style>
</head>
<body class="selection:bg-electric selection:text-white">

  <!-- Top Contact Bar -->
  <div class="bg-carbon border-b border-white/10 text-xs py-2.5 px-4">
    <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center gap-4 text-titanium">
        <span>📍 <span data-en="Al-Karak, Jordan" data-ar="الكرك، الأردن">Al-Karak, Jordan</span></span>
        <span class="hidden sm:inline">|</span>
        <a href="tel:+962776999555" class="hover:text-cyber transition font-semibold text-white">📞 +962 77 699 9555</a>
      </div>
      <div class="flex items-center gap-4">
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
          <img src="Chrome ADAILEH Car Care Emblem.png" alt="Adaileh Car Care Center Logo" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/><circle cx=\'7.5\' cy=\'14.5\' r=\'1.5\'/><circle cx=\'16.5\' cy=\'14.5\' r=\'1.5\'/></svg>'"[cite: 3] />
        </div>
        <div>
          <div class="font-extrabold text-lg sm:text-xl tracking-tight text-white" data-en="ADAILEH CAR CARE" data-ar="العضايلة للعناية بالسيارات">العضايلة للعناية بالسيارات</div>
          <div class="text-[10px] uppercase tracking-widest text-electric font-semibold" data-en="Authorized Sampingko Dealer" data-ar="وكيل معتمد لمنتجات سينفنكو الألمانية">وكيل معتمد لمنتجات سينفنكو الألمانية</div>
        </div>
      </a>

      <nav class="hidden md:flex items-center gap-7 text-sm font-semibold text-titanium">
        <a href="#services" class="hover:text-white transition" data-en="Services" data-ar="خدماتنا">Services</a>
        <a href="#ai-advisor" class="hover:text-white transition" data-en="Smart Estimator" data-ar="المستشار الذكي">المستشار الذكي</a>
        <a href="#location" class="hover:text-white transition" data-en="Location & Contact" data-ar="الموقع والتواصل">الموقع والتواصل</a>
      </nav>

      <div class="flex items-center gap-3">
        <a href="#ai-advisor" class="cyber-gradient text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-full shadow-lg shadow-electric/25 hover:opacity-95 transition" data-en="Book Appointment" data-ar="احجز موعدك الآن">
          احجز موعدك الآن
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
          <span data-en="Authorized Dealer for German Sampingko Products" data-ar="وكيل معتمد لمنتجات سينفنكو الألمانية">وكيل معتمد لمنتجات سينفنكو الألمانية</span>
        </div>
        <h1 class="text-4xl sm:text-6xl font-extrabold leading-tight tracking-tight text-white" data-en="Uncompromising Gloss. Engineered Protection." data-ar="أفضل خدمة للعناية بسيارتك في الكرك">
          أفضل خدمة للعناية بسيارتك في الكرك
        </h1>
        <p class="text-titanium text-base sm:text-lg max-w-2xl leading-relaxed" data-en="At Adaileh Car Care, we provide top German & American automotive solutions including premium dry cleaning, German Sampingko motor oils, advanced performance boosters, catalytic cleaning, and professional detailing." data-ar="في مركز العضايلة، نقدم أرقى خدمات الدراي كلين الفاخرة، زيوت سينفنكو الألمانية الأصلية، محسنات الأداء المتقدمة، تنظيف الكتلايزر، والبولش والنانوسيراميك الاحترافي.">
          في مركز العضايلة، نقدم أرقى خدمات الدراي كلين الفاخرة، زيوت سينفنكو الألمانية الأصلية، محسنات الأداء المتقدمة، تنظيف الكتلايزر، والبولش والنانوسيراميك الاحترافي.
        </p>

        <div class="flex flex-wrap gap-4 pt-2">
          <a href="#ai-advisor" class="cyber-gradient text-white font-bold px-8 py-4 rounded-full shadow-xl shadow-electric/25 hover:opacity-95 transition" data-en="Launch Smart Estimator →" data-ar="جرب المستشار الذكي ←">
            جرب المستشار الذكي ←
          </a>
          <a href="https://wa.me/962776999555" target="_blank" class="bg-white/5 hover:bg-white/10 border border-white/15 text-white font-semibold px-7 py-4 rounded-full transition" data-en="Contact via WhatsApp" data-ar="تواصل عبر واتساب">
            تواصل عبر واتساب
          </a>
        </div>
      </div>

      <!-- Featured Emblem Card -->
      <div class="lg:col-span-5">
        <div class="glass-panel rounded-3xl p-7 shadow-2xl space-y-6 border border-electric/30 text-center">
          
          <div class="logo-crop-hero">
            <img src="Chrome ADAILEH Car Care Emblem.png" alt="Adaileh Car Care Center Official Emblem" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\' width=\'80\' height=\'80\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/><circle cx=\'7.5\' cy=\'14.5\' r=\'1.5\'/><circle cx=\'16.5\' cy=\'14.5\' r=\'1.5\'/></svg>'"[cite: 3] />
          </div>

          <div class="space-y-3 text-sm text-left rtl:text-right pt-2 border-t border-white/10">
            <div class="p-4 rounded-2xl bg-obsidian/80 border border-white/10 flex justify-between items-center">
              <div>
                <div class="font-bold text-white text-xs" data-en="German Sampingko Products" data-ar="منتجات سينفنكو الألمانية الأصلية">منتجات سينفنكو الألمانية الأصلية</div>
              </div>
              <span class="text-cyber font-bold text-xs" data-en="Authorized Dealer" data-ar="وكيل معتمد">وكيل معتمد</span>
            </div>

            <div class="p-4 rounded-2xl bg-obsidian/80 border border-white/10 flex justify-between items-center">
              <div>
                <div class="font-bold text-white text-xs" data-en="Professional Car Care in Al-Karak" data-ar="العناية الشاملة بالسيارات في الكرك">العناية الشاملة بالسيارات في الكرك</div>
              </div>
              <span class="text-cyber font-bold text-xs" data-en="Top Quality" data-ar="جودة فائقة">جودة فائقة</span>
            </div>
          </div>

          <div class="flex flex-col sm:flex-row gap-3">
            <a href="tel:+962776999555" class="flex-1 bg-white/10 hover:bg-white/15 text-center py-3 rounded-xl text-xs font-bold text-white transition" data-en="📞 Call Direct" data-ar="📞 اتصال مباشر">
              📞 اتصال مباشر
            </a>
            <a href="https://wa.me/962776999555" target="_blank" class="flex-1 cyber-gradient text-center py-3 rounded-xl text-xs font-bold text-white transition" data-en="💬 WhatsApp" data-ar="💬 واتساب">
              💬 واتساب
            </a>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- Interactive Statistics Section -->
  <section class="py-12 bg-carbon border-b border-white/10">
    <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      
      <!-- Stat Card 1 -->
      <div onclick="triggerStatAction(this, 'experience')" class="glass-panel p-8 rounded-3xl card-glow border border-white/10 relative overflow-hidden group">
        <div class="absolute inset-0 bg-cyber/5 opacity-0 group-hover:opacity-100 transition"></div>
        <h4 class="text-4xl font-black text-cyber tracking-tight">5+</h4>
        <p class="text-titanium mt-2 font-bold text-sm" data-en="Years of Excellence & Experience" data-ar="سنوات من الخبرة والتميز">سنوات من الخبرة والتميز</p>
        <span class="text-[10px] text-electric block mt-3 opacity-70" data-en="⚡ Click to Explore" data-ar="⚡ اضغط للاستكشاف">⚡ اضغط للاستكشاف</span>
      </div>

      <!-- Stat Card 2 -->
      <div onclick="triggerStatAction(this, 'materials')" class="glass-panel p-8 rounded-3xl card-glow border border-white/10 relative overflow-hidden group">
        <div class="absolute inset-0 bg-cyber/5 opacity-0 group-hover:opacity-100 transition"></div>
        <h4 class="text-4xl font-black text-cyber tracking-tight">100%</h4>
        <p class="text-titanium mt-2 font-bold text-sm" data-en="Original & Guaranteed Materials" data-ar="مواد أصلية ومضمونة">مواد أصلية ومضمونة</p>
        <span class="text-[10px] text-electric block mt-3 opacity-70" data-en="⚡ Click to Explore" data-ar="⚡ اضغط للاستكشاف">⚡ اضغط للاستكشاف</span>
      </div>

      <!-- Stat Card 3 -->
      <div onclick="triggerStatAction(this, 'cars')" class="glass-panel p-8 rounded-3xl card-glow border border-white/10 relative overflow-hidden group">
        <div class="absolute inset-0 bg-cyber/5 opacity-0 group-hover:opacity-100 transition"></div>
        <h4 class="text-4xl font-black text-cyber tracking-tight">1500+</h4>
        <p class="text-titanium mt-2 font-bold text-sm" data-en="Vehicles Cared For" data-ar="سيارة تم العناية بها">سيارة تم العناية بها</p>
        <span class="text-[10px] text-electric block mt-3 opacity-70" data-en="⚡ Click to Explore" data-ar="⚡ اضغط للاستكشاف">⚡ اضغط للاستكشاف</span>
      </div>

    </div>
  </section>

  <!-- Intelligent Package Recommender & Estimator Section -->
  <section id="ai-advisor" class="py-20 bg-carbon border-b border-white/10 text-left rtl:text-right">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-14">
        <span class="text-xs font-bold uppercase tracking-widest text-cyber" data-en="Smart Configurator" data-ar="المستشار الذكي لاختيار الباقة">المستشار الذكي لاختيار الباقة</span>
        <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-2" data-en="Design the Ideal Care Package for Your Car in Seconds" data-ar="صمّم باقة العناية المثالية لسيارتك خلال ثوانٍ">
          صمّم باقة العناية المثالية لسيارتك خلال ثوانٍ
        </h2>
      </div>

      <div class="grid lg:grid-cols-12 gap-10 items-center">
        
        <!-- Left Side: Inputs -->
        <div class="lg:col-span-6 space-y-5 glass-panel p-8 rounded-3xl border border-white/10">
          <div>
            <label class="block text-xs font-bold uppercase text-titanium mb-2" data-en="1. Select Vehicle Category:" data-ar="1. اختر فئة وحجم السيارة:">1. اختر فئة وحجم السيارة:</label>
            <select id="car-size" onchange="calculateSmartQuote()" class="w-full p-3.5 rounded-xl bg-obsidian border border-white/15 text-white text-sm font-semibold focus:border-electric focus:outline-none">
              <option value="1.0">Sedan / Coupe / Hatchback (صالون / هاتشباك)</option>
              <option value="1.25">Mid-Size SUV / Crossover (جيب وسط / كروس أوفر)</option>
              <option value="1.45">Large SUV / 4x4 / Pickup (دفع رباعي كبير / بكب)</option>
            </select>
          </div>

          <div>
            <label class="block text-xs font-bold uppercase text-titanium mb-2" data-en="2. Select Primary Treatment:" data-ar="2. اختر الباقة أو الخدمة الأساسية:">2. اختر الباقة أو الخدمة الأساسية:</label>
            <select id="service-type" onchange="calculateSmartQuote()" class="w-full p-3.5 rounded-xl bg-obsidian border border-white/15 text-white text-sm font-semibold focus:border-electric focus:outline-none">
              <option value="detail">VIP Interior Dry Clean & Sterilization (دراي كلين وتعقيم داخلي فاخر)</option>
              <option value="oils">German Sampingko Motor Oils (زيوت سينفنكو الألمانية)</option>
              <option value="additives">Advanced Performance Additives (محسنات أداء وعزم المحرك)</option>
              <option value="catalytic">Catalytic Converter Deep Cleaning (تنظيف وعلاج الكتلايزر)</option>
              <option value="combustion">Combustion Chamber & Valve Service (خدمة منظومة الاحتراق)</option>
              <option value="polish">Multi-Stage Professional Polish (بولش وتصحيح طلاء احترافي)</option>
              <option value="ceramic" selected>9H Nano-Ceramic Armor Coating (نانوسيراميك حماية طلاء 9H)</option>
            </select>
          </div>

          <div>
            <label class="block text-xs font-bold uppercase text-titanium mb-2" data-en="3. Your Vehicle Make & Model (Optional):" data-ar="3. نوع وموديل السيارة (اختياري):">3. نوع وموديل السيارة (اختياري):</label>
            <input id="car-model" type="text" placeholder="e.g., BMW X5 2025 / Kia EV6 / Mercedes E-Class" class="w-full p-3.5 rounded-xl bg-obsidian border border-white/15 text-white text-sm focus:border-electric focus:outline-none" />
          </div>
        </div>

        <!-- Right Side: Result Card -->
        <div class="lg:col-span-6">
          <div class="glass-panel rounded-3xl p-8 border-2 border-electric/40 space-y-6">
            <div class="flex justify-between items-start">
              <div>
                <span class="text-xs uppercase tracking-widest text-cyber font-bold" data-en="Recommended Protocol" data-ar="الباقة المقترحة لسيارتك">الباقة المقترحة لسيارتك</span>
                <h3 id="quote-title" class="text-2xl font-extrabold text-white mt-1">9H Nano-Ceramic Shield</h3>
              </div>
              <span id="quote-time" class="bg-electric/20 text-cyber text-xs font-bold px-3 py-1 rounded-full">⏱️ 1–2 Days</span>
            </div>

            <p id="quote-desc" class="text-sm text-titanium leading-relaxed">
              Permanent 9H molecular bond providing extreme hydrophobic protection against UV rays, acid rain, and harsh weather.
            </p>

            <div class="p-5 rounded-2xl bg-obsidian border border-white/10 flex justify-between items-center">
              <div>
                <span class="text-xs text-titanium block" data-en="Estimated Starting Investment" data-ar="السعر التقديري يبدأ من">السعر التقديري يبدأ من</span>
                <span id="quote-price" class="text-3xl font-extrabold text-cyber">150 دينار</span>
              </div>
              <div class="text-right text-xs text-emerald-400 font-semibold" data-en="✓ Free Inspection Before Start" data-ar="✓ فحص مجاني للسيارة قبل البدء">
                ✓ فحص مجاني للسيارة قبل البدء
              </div>
            </div>

            <div class="grid sm:grid-cols-2 gap-3">
              <button onclick="bookViaWhatsApp()" class="cyber-gradient text-white font-bold py-4 px-5 rounded-xl text-xs sm:text-sm shadow-lg hover:opacity-95 transition flex items-center justify-center gap-2">
                <span>💬</span>
                <span data-en="Book This Package on WhatsApp" data-ar="احجز هذه الباقة عبر واتساب">احجز هذه الباقة عبر واتساب</span>
              </button>
              <a href="https://www.facebook.com/AdailehCarCare" target="_blank" rel="noopener noreferrer" class="bg-white/10 hover:bg-white/20 text-white font-bold py-4 px-5 rounded-xl text-xs sm:text-sm transition flex items-center justify-center gap-2">
                <span>📘</span>
                <span data-en="Inquire via Facebook" data-ar="استفسر عبر صفحة فيسبوك">استفسر عبر صفحة فيسبوك</span>
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Core Services Grid -->
  <section id="services" class="py-20 max
