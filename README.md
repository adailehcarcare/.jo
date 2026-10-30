<!DOCTYPE html>
<html lang="en" dir="ltr" id="html-root">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adaileh Car Care Center | العضايلة للعناية بالسيارات</title>
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

    .logo-crop-header { width: 56px; height: 50px; overflow: hidden; border-radius: 10px; background: #ffffff; display: flex; align-items: center; justify-content: center; box-shadow: 0 4px 14px rgba(0,0,0,0.5); border: 1px solid rgba(0,168,255,0.4); flex-shrink: 0; }
    .logo-crop-header img { width: 100%; height: 100%; object-fit: contain; background: #ffffff; }
    
    .logo-crop-hero { width: 100%; max-width: 280px; height: 180px; overflow: hidden; border-radius: 20px; background: #ffffff; margin: 0 auto; box-shadow: 0 12px 30px rgba(0,0,0,0.65); border: 2px solid rgba(0,168,255,0.5); display: flex; align-items: center; justify-content: center; }
    .logo-crop-hero img { width: 100%; height: 100%; object-fit: contain; background: #ffffff; }
  </style>
</head>
<body class="selection:bg-electric selection:text-white">

  <!-- Top Contact & Social Bar -->
  <div class="bg-carbon border-b border-white/10 text-xs py-2.5 px-4">
    <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center gap-4 text-titanium">
        <span>📍 <span data-en="Al-Karak, Jordan" data-ar="الكرك، الأردن">Al-Karak, Jordan</span></span>
        <span class="hidden sm:inline">|</span>
        <a href="tel:+962776999555" class="hover:text-cyber transition font-semibold text-white">📞 +962 77 699 9555</a>
      </div>
      <div class="flex items-center gap-4">
        <span class="text-cyber font-bold" data-en="Authorized Dealer for German Sampingko Products" data-ar="وكيل معتمد لمنتجات سينفنكو الألمانية">وكيل معتمد لمنتجات سينفنكو الألمانية</span>
        <span class="hidden sm:inline text-titanium">|</span>
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
          <img src="Chrome ADAILEH Car Care Emblem.png" alt="Adaileh Car Care Center Logo" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/><circle cx=\'7.5\' cy=\'14.5\' r=\'1.5\'/><circle cx=\'16.5\' cy=\'14.5\' r=\'1.5\'/></svg>'" />
        </div>
        <div>
          <div class="font-extrabold text-lg sm:text-xl tracking-tight text-white" data-en="ADAILEH CAR CARE" data-ar="العضايلة للعناية بالسيارات">العضايلة للعناية بالسيارات</div>
          <div class="text-[10px] uppercase tracking-widest text-electric font-semibold" data-en="Authorized Sampingko Dealer" data-ar="وكيل معتمد لمنتجات سينفنكو الألمانية">وكيل معتمد لمنتجات سينفنكو الألمانية</div>
        </div>
      </a>

      <nav class="hidden md:flex items-center gap-7 text-sm font-semibold text-titanium">
        <a href="#services" class="hover:text-white transition" data-en="Services" data-ar="خدماتنا">Services</a>
        <a href="#location" class="hover:text-white transition" data-en="Location & Contact" data-ar="الموقع والتواصل">Location & Contact</a>
      </nav>

      <div class="flex items-center gap-3">
        <a href="https://wa.me/962776999555" target="_blank" class="cyber-gradient text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-full shadow-lg shadow-electric/25 hover:opacity-95 transition" data-en="Book Appointment" data-ar="احجز موعدك الآن">
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
        <p class="text-titanium text-base sm:text-lg max-w-2xl leading-relaxed" data-en="At Adaileh Car Care, we provide top German & American automotive solutions including dry cleaning, oils, filters, performance additives, catalytic converter cleaning, and combustion system care." data-ar="في مركز العضايلة، نقدم أفضل خدمات الدراي كلين، الزيوت، الفلاتر، محسنات الأداء، تنظيف الكتلايزر، وصيانة منظومة الاحتراق بأعلى معايير الجودة والإتقان.">
          في مركز العضايلة، نقدم أفضل خدمات الدراي كلين، الزيوت، الفلاتر، محسنات الأداء، تنظيف الكتلايزر، وصيانة منظومة الاحتراق بأعلى معايير الجودة والإتقان.
        </p>

        <div class="flex flex-wrap gap-4 pt-2">
          <a href="#services" class="cyber-gradient text-white font-bold px-8 py-4 rounded-full shadow-xl shadow-electric/25 hover:opacity-95 transition" data-en="View Our Services →" data-ar="استعرض خدماتنا ←">
            استعرض خدماتنا ←
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
            <img src="Chrome ADAILEH Car Care Emblem.png" alt="Adaileh Car Care Center Official Emblem" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\' width=\'80\' height=\'80\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/><circle cx=\'7.5\' cy=\'14.5\' r=\'1.5\'/><circle cx=\'16.5\' cy=\'14.5\' r=\'1.5\'/></svg>'" />
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

  <!-- Core Services Grid (All services included) -->
  <section id="services" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-left rtl:text-right">
    <div class="text-center max-w-3xl mx-auto mb-14">
      <span class="text-xs font-bold uppercase tracking-widest text-electric" data-en="Professional Automotive Solutions" data-ar="خدماتنا المعتمدة">خدماتنا المعتمدة</span>
      <h2 class="text-3xl sm:text-5xl font-extrabold text-white mt-2" data-en="Our Specialized Services" data-ar="الخدمات التي نقدمها">الخدمات التي نقدمها</h2>
      <p class="text-titanium text-sm sm:text-base mt-3" data-en="Explore our comprehensive range of high-performance products and professional care services." data-ar="نقدم تشكيلة متكاملة من المنتجات وخدمات العناية الفائقة بسيارتك في الكرك.">
        Explore our comprehensive range of high-performance products and professional care services.
      </p>
    </div>

    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-7">
      
      <!-- Service 1: Dry Clean (دراي كلين) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="firstphoto1.png" alt="Dry Clean" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Cabin Care" data-ar="العناية الداخلية">العناية الداخلية</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Dry Clean" data-ar="دراي كلين">دراي كلين</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Deep interior steam cleaning and sanitization for seats, carpets, and dashboard to eliminate stains and odors." data-ar="تنظيف وتعقيم داخلي عميق بالبخار والأوزون للمقاعد، الأرضيات، والسقف لإزالة البقع الصعبة والروائح الكريهة.">
            تنظيف وتعقيم داخلي عميق بالبخار والأوزون للمقاعد، الأرضيات، والسقف لإزالة البقع الصعبة والروائح الكريهة.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Steam Sterilization" data-ar="تعقيم بالبخار">تعقيم بالبخار</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
        </div>
      </div>

      <!-- Service 2: Oils (زيوت) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="secondphoto2.png" alt="Oils" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="German Sampingko" data-ar="سينفنكو الألمانية">سينفنكو الألمانية</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Oils" data-ar="زيوت">زيوت</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Original German Sampingko high-performance motor oils designed to maximize engine protection and longevity." data-ar="توفير وفحص زيوت محركات سينفنكو الألمانية الأصلية لضمان أقصى حماية وعمر افتراضي للمحرك.">
            توفير وفحص زيوت محركات سينفنكو الألمانية الأصلية لضمان أقصى حماية وعمر افتراضي للمحرك.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Original German Products" data-ar="منتجات ألمانية أصلية">منتجات ألمانية أصلية</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
        </div>
      </div>

      <!-- Service 3: Filters (فلاتر) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="thirdphoto3.png" alt="Filters" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Engine Protection" data-ar="حماية المحرك">حماية المحرك</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Filters" data-ar="فلاتر">فلاتر</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="High-efficiency oil, air, and fuel filters to ensure pure airflow and clean fluid circulation." data-ar="فلاتر زيت، هواء، ووقود عالية الجودة لضمان نقاء دورة المحرك وحمايته.">
            فلاتر زيت، هواء، ووقود عالية الجودة لضمان نقاء دورة المحرك وحمايته.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="High Efficiency" data-ar="كفاءة عالية">كفاءة عالية</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
        </div>
      </div>

      <!-- Service 4: Performance Additives (محسنات أداء) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="firstphoto1.png" alt="Performance Additives" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Engine Boost" data-ar="رفع الكفاءة">رفع الكفاءة</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Performance Additives" data-ar="محسنات أداء">محسنات أداء</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Advanced performance additives to reduce friction, clean fuel systems, and enhance engine responsiveness." data-ar="مواد متطورة لتقليل الاحتكاك، تنظيف نظام الوقود، ورفع كفاءة استجابة المحرك.">
            مواد متطورة لتقليل الاحتكاك، تنظيف نظام الوقود، ورفع كفاءة استجابة المحرك.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Maximum Output" data-ar="أداء أقوى">أداء أقوى</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
        </div>
      </div>

      <!-- Service 5: Catalytic Converter Cleaning (تنظيف كتلايزر) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="secondphoto2.png" alt="Catalytic Converter Cleaning" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Exhaust Care" data-ar="نظام العادم">نظام العادم</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Catalytic Converter Cleaning" data-ar="تنظيف كتلايزر">تنظيف كتلايزر</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Specialized cleaning service for catalytic converters to remove carbon buildup and restore exhaust efficiency." data-ar="خدمة متخصصة لتنظيف وفك الترسبات الكربونية من الكتلايزر لتحسين عزم السيارة وتقليل الانبعاثات.">
            خدمة متخصصة لتنظيف وفك الترسبات الكربونية من الكتلايزر لتحسين عزم السيارة وتقليل الانبعاثات.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Carbon Removal" data-ar="إزالة الكربون">إزالة الكربون</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
        </div>
      </div>

      <!-- Service 6: Combustion System (منظومة احتراق) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="thirdphoto3.png" alt="Combustion System" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Combustion Care" data-ar="منظومة الاحتراق">منظومة الاحتراق</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Combustion System Service" data-ar="منظومة احتراق">منظومة احتراق</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Comprehensive cleaning and maintenance for valves, injectors, and the entire combustion chamber." data-ar="تنظيف وصيانة شاملة للبخاخات، الصمامات، وغرفة الاحتراق لضمان احتراق مثالي واستهلاك اقتصادي للوقود.">
            تنظيف وصيانة شاملة للبخاخات، الصمامات، وغرفة الاحتراق لضمان احتراق مثالي واستهلاك اقتصادي للوقود.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Optimal Efficiency" data-ar="احتراق مثالي">احتراق مثالي</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
        </div>
      </div>

      <!-- Service 7: Professional Polish (بولش احترافي) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="firstphoto1.png" alt="Professional Polish" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Paint Restoration" data-ar="استعادة اللمعان">استعادة اللمعان</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Professional Polish" data-ar="بولش احترافي">بولش احترافي</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Multi-stage professional machine polishing to remove wash swirls, surface scratches, and restore showroom finish." data-ar="تلميع ومعالجة خارجية على عدة مراحل لإزالة دوائر الغسيل، الخدوش السطحية، وإعادة لمعة الوكالة للطلاء.">
            تلميع ومعالجة خارجية على عدة مراحل لإزالة دوائر الغسيل، الخدوش السطحية، وإعادة لمعة الوكالة للطلاء.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="Mirror Finish" data-ar="لمعان مرآتي">لمعان مرآتي</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
        </div>
      </div>

      <!-- Service 8: Nano-Ceramic (نانوسيراميك) -->
      <div class="glass-panel rounded-3xl p-5 card-glow flex flex-col justify-between overflow-hidden">
        <div>
          <div class="overflow-hidden rounded-2xl mb-5 h-48 border border-white/10">
            <img src="secondphoto2.png" alt="Nano-Ceramic" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
          </div>
          <span class="text-[11px] font-bold uppercase tracking-wider text-cyber" data-en="Surface Protection" data-ar="حماية فائقة">حماية فائقة</span>
          <h3 class="text-xl font-bold text-white mt-1" data-en="Nano-Ceramic" data-ar="نانوسيراميك">نانوسيراميك</h3>
          <p class="text-sm text-titanium mt-3 leading-relaxed" data-en="Advanced 9H Nano-Ceramic crystal coating providing long-lasting gloss and resistance against oxidation and weather." data-ar="طبقة حماية كريستالية متطورة (9H) تمنح هيكل السيارة لمعاناً فائقاً ومقاومة عالية للأكسدة والعوامل الجوية.">
            طبقة حماية كريستالية متطورة (9H) تمنح هيكل السيارة لمعاناً فائقاً ومقاومة عالية للأكسدة والعوامل الجوية.
          </p>
        </div>
        <div class="mt-6 pt-4 border-t border-white/10 flex justify-between items-center text-xs">
          <span class="text-titanium" data-en="9H Hardness" data-ar="صلابة 9H">صلابة 9H</span>
          <a href="https://wa.me/962776999555" class="text-electric font-bold hover:underline" data-en="Inquire →" data-ar="استفسر ←">استفسر ←</a>
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
          <p class="text-sm text-titanium" data-en="Drop by for German Sampingko products and professional car care services in Al-Karak." data-ar="تفضل بزيارتنا للحصول على منتجات سينفنكو الألمانية وخدمات العناية بالسيارات في الكرك.">
            تفضل بزيارتنا للحصول على منتجات سينفنكو الألمانية وخدمات العناية بالسيارات في الكرك.
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
                <a href="tel:+962776999555" class="text-cyber font-bold hover:underline">+962 77 699 9555</a>
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
        <a href="#services" class="hover:text-cyber transition" data-en="Services" data-ar="الخدمات">Services</a>
      </div>
    </div>
  </footer>

  <script>
    let isArabic = false;
    const WHATSAPP_NUMBER = "962776999555";

    function toggleLang() {
      isArabic = !isArabic;
      const root = document.getElementById('html-root');
      root.dir = isArabic ? 'rtl' : 'ltr';
      root.lang = isArabic ? 'ar' : 'en';
      document.getElementById('lang-btn').textContent = isArabic ? 'English' : 'العربية';

      document.querySelectorAll('[data-en]').forEach(el => {
        el.textContent = isArabic ? el.getAttribute('data-ar') : el.getAttribute('data-en');
      });
    }
  </script>
</body>
</html>
