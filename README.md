<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مركز العضايله للعناية بالمركبات - الكرك | Adaileh Car Care Center</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;900&display=swap" rel="stylesheet">
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
            sans: ['"Cairo"', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    body { font-family: 'Cairo', sans-serif; background-color: #0B0D12; color: #F8FAFC; }
    .cyber-gradient { background: linear-gradient(135deg, #00A8FF 0%, #0062FF 100%); }
    .glass-panel { background: rgba(28, 34, 48, 0.75); backdrop-filter: blur(14px); border: 1px solid rgba(255, 255, 255, 0.08); }
    .card-glow { transition: all 0.3s ease; }
    .card-glow:hover { transform: translateY(-5px); border-color: rgba(0, 168, 255, 0.5); box-shadow: 0 15px 35px -10px rgba(0, 168, 255, 0.25); }
  </style>
</head>
<body class="bg-obsidian text-slate-100 min-h-screen flex flex-col justify-between selection:bg-electric selection:text-white">

  <!-- Floating WhatsApp & Facebook Buttons -->
  <div class="fixed bottom-6 left-6 z-50 flex flex-col gap-3">
    <a href="https://wa.me/962776999555?text=مرحباً%20مركز%20العضايله،%20أود%20الاستفسار%20عن%20خدمات%20العناية%20بالسيارات" target="_blank" title="WhatsApp" class="bg-green-600 hover:bg-green-500 text-white p-3.5 rounded-full shadow-2xl transition transform hover:scale-110 flex items-center justify-center text-2xl">
      💬
    </a>
    <a href="https://www.facebook.com/YOUR_FACEBOOK_PAGE" target="_blank" title="Facebook" class="bg-blue-600 hover:bg-blue-500 text-white p-3.5 rounded-full shadow-2xl transition transform hover:scale-110 flex items-center justify-center text-2xl font-bold">
      f
    </a>
  </div>

  <!-- Header / Navigation Bar with Logo Only -->
  <header class="sticky top-0 z-40 glass-panel border-b border-white/10">
    <div class="max-w-7xl mx-auto px-4 h-20 flex justify-between items-center">
      <div class="flex items-center gap-3 text-sm">
        <span class="text-titanium">💬 واتساب / هاتف:</span>
        <a href="https://wa.me/962776999555" target="_blank" class="text-cyber font-bold hover:underline">0776999555</a>
      </div>

      <a href="#" class="flex items-center gap-2 group">
        <img src="logo.png.jpg" alt="Adaileh Car Care Center Logo" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 24 24\' fill=\'%2300A8FF\' width=\'50\' height=\'50\'><path d=\'M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.22.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99zM6.85 7h10.29l1.04 3H5.81l1.04-3zM19 17H5v-4.66l.12-.34h13.76l.12.34V17z\'/></svg>'" class="h-14 w-auto object-contain bg-carbon p-1 rounded-xl border border-electric/40">
      </a>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative py-20 px-4 text-center border-b border-white/10" style="background: radial-gradient(circle at 50% 20%, rgba(0, 168, 255, 0.15), transparent 50%), linear-gradient(180deg, #0B0D12 0%, #131722 100%);">
    <div class="max-w-4xl mx-auto space-y-6">
      <span class="inline-flex items-center gap-2 bg-electric/15 border border-electric/40 text-cyber px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-wider">
        <span>⚡</span> مركز العضايله للعناية بالمركبات — الكرك
      </span>
      <h1 class="text-4xl md:text-6xl font-black tracking-tight text-white leading-tight">أفضل خدمة للعناية بسيارتك في الكرك</h1>
      <p class="text-titanium text-lg md:text-xl max-w-2xl mx-auto leading-relaxed">
        نقدم أفضل خدمات التلميع، النانو سيراميك، وتنظيف المركبات الداخلي والخارجي بأعلى جودة وإتقان بأيدي متخصصين.
      </p>
      <div class="pt-4">
        <a href="#booking" class="cyber-gradient text-white font-bold px-8 py-4 rounded-xl shadow-lg shadow-electric/25 transition inline-block hover:opacity-95">
          احجز خدمتك الآن
        </a>
      </div>
    </div>
  </section>

  <!-- Statistics Section -->
  <section class="py-12 bg-carbon border-b border-white/10">
    <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div class="glass-panel p-6 rounded-2xl card-glow">
        <h4 class="text-3xl font-extrabold text-cyber">+1500</h4>
        <p class="text-titanium mt-2 font-medium">سيارة تم العناية بها</p>
      </div>
      <div class="glass-panel p-6 rounded-2xl card-glow">
        <h4 class="text-3xl font-extrabold text-cyber">100%</h4>
        <p class="text-titanium mt-2 font-medium">مواد أصلية ومضمونة</p>
      </div>
      <div class="glass-panel p-6 rounded-2xl card-glow">
        <h4 class="text-3xl font-extrabold text-cyber">+5</h4>
        <p class="text-titanium mt-2 font-medium">سنوات من الخبرة والتميز</p>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-20 max-w-7xl mx-auto px-4">
    <div class="text-center max-w-3xl mx-auto mb-16">
      <h2 class="text-3xl md:text-4xl font-black text-white">خدماتنا المتخصصة</h2>
      <div class="h-1 w-16 bg-electric mx-auto mt-3 rounded-full"></div>
    </div>

    <div class="grid lg:grid-cols-3 gap-8">
      
      <!-- Service 1 -->
      <div class="glass-panel rounded-3xl overflow-hidden card-glow flex flex-col">
        <div class="h-52 overflow-hidden border-b border-white/10">
          <img src="firstphoto1.png" alt="Nano Ceramic Coating" loading="lazy" class="w-full h-full object-cover hover:scale-105 transition duration-500">
        </div>
        <div class="p-6 flex-1 flex flex-col justify-between">
          <div>
            <h3 class="text-2xl font-bold text-white mb-3">حماية النانو سيراميك</h3>
            <p class="text-titanium text-sm leading-relaxed mb-4">تقنية درع الحماية الكريستالي التي تمنح هيكل السيارة مقاومة عالية وتزيد من العمر الافتراضي لطلاء المركبة.</p>
            <ul class="space-y-2 text-titanium text-xs list-disc list-inside">
              <li>حماية المينا من الأشعة فوق البنفسجية والأكسدة</li>
              <li>خاصية الهيدروفوبيك لمنع التصاق الماء والأتربة</li>
              <li>إعطاء لمعان وبريق كريستالي مستمر</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Service 2 -->
      <div class="glass-panel rounded-3xl overflow-hidden card-glow flex flex-col">
        <div class="h-52 overflow-hidden border-b border-white/10">
          <img src="secondphoto2.png" alt="Paint Correction Polish" loading="lazy" class="w-full h-full object-cover hover:scale-105 transition duration-500">
        </div>
        <div class="p-6 flex-1 flex flex-col justify-between">
          <div>
            <h3 class="text-2xl font-bold text-white mb-3">التلميع والبوليش الخارجي</h3>
            <p class="text-titanium text-sm leading-relaxed mb-4">معالجة متكاملة لطلاء السيارة لإرجاع لمعة الوكالة مع إزالة آثار الأكسدة الدقيقة ودوائر الغسيل.</p>
            <ul class="space-y-2 text-titanium text-xs list-disc list-inside">
              <li>معالجة الخدوش السطحية ودوائر التلميع</li>
              <li>إعادة توحيد لون الطلاء وتصحيح العيوب</li>
              <li>تلميع الأضواء الأمامية لإعادة وضوحها</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Service 3 -->
      <div class="glass-panel rounded-3xl overflow-hidden card-glow flex flex-col">
        <div class="h-52 overflow-hidden border-b border-white/10">
          <img src="thirdphoto3.png" alt="Interior Auto Detailing" loading="lazy" class="w-full h-full object-cover hover:scale-105 transition duration-500">
        </div>
        <div class="p-6 flex-1 flex flex-col justify-between">
          <div>
            <h3 class="text-2xl font-bold text-white mb-3">التنظيف والتفصيل الداخلي (Detailing)</h3>
            <p class="text-titanium text-sm leading-relaxed mb-4">تنظيف وتعقيم عميق لكافة مكونات المقصورة الداخلية للمركبة مع العناية بكافة التفاصيل الصغيرة.</p>
            <ul class="space-y-2 text-titanium text-xs list-disc list-inside">
              <li>تنظيف وتعقيم المقاعد بجهاز البخار</li>
              <li>إزالة البقع المستعصية والروائح الكريهة</li>
              <li>ترطيب وتغذية المقاعد الجلدية لحمايتها</li>
            </ul>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- Why Choose Us -->
  <section class="py-20 bg-carbon border-y border-white/10">
    <div class="max-w-7xl mx-auto px-4 text-center">
      <h2 class="text-3xl md:text-4xl font-black text-white mb-4">لماذا اختيار مركز العضايله للعناية بالمركبات؟</h2>
      <div class="h-1 w-16 bg-electric mx-auto mb-16 rounded-full"></div>

      <div class="grid md:grid-cols-3 gap-8">
        <div class="glass-panel p-8 rounded-3xl card-glow">
          <h4 class="text-xl font-bold text-cyber mb-3">جودة مواد عالية</h4>
          <p class="text-titanium text-sm leading-relaxed">نستخدم أرقى وأفضل المواد العالمية المعتمدة عالمياً لحماية طلاء السيارات.</p>
        </div>
        <div class="glass-panel p-8 rounded-3xl card-glow">
          <h4 class="text-xl font-bold text-cyber mb-3">فريق معتمد بشهادات عالمية</h4>
          <p class="text-titanium text-sm leading-relaxed">نخبة من الفنيين المحترفين والحاصلين على اعتمادات دولية في فن العناية بالمركبات والفارهات.</p>
        </div>
        <div class="glass-panel p-8 rounded-3xl card-glow">
          <h4 class="text-xl font-bold text-cyber mb-3">دقة في المواعيد</h4>
          <p class="text-titanium text-sm leading-relaxed">نلتزم بتسليم سيارتك في الوقت المحدد بدقة وبأعلى معايير الإتقان.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Booking Section -->
  <section id="booking" class="py-20 max-w-4xl mx-auto px-4 text-center">
    <div class="glass-panel p-8 md:p-12 rounded-3xl border border-electric/40 shadow-2xl">
      <h3 class="text-3xl font-black text-white mb-3">📅 احجز موعدك الآن</h3>
      <p class="text-titanium text-sm md:text-base mb-6">اختر الخدمة والوقت المناسب لك وسنتواصل معك فوراً لتأكيد الحجز</p>
      <a href="https://wa.me/962776999555?text=مرحباً%20أود%20حجز%20موعد%20لعناية%20بالسيارة" target="_blank" class="inline-block bg-green-600 hover:bg-green-500 text-white font-bold px-8 py-4 rounded-xl shadow-lg transition text-lg">
        تواصل معنا عبر واتساب للحجز 💬
      </a>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="py-20 bg-carbon border-t border-white/10">
    <div class="max-w-7xl mx-auto px-4 text-center">
      <h3 class="text-3xl font-black text-white mb-4">آراء عملائنا الكرام</h3>
      <div class="h-1 w-16 bg-electric mx-auto mb-16 rounded-full"></div>

      <div class="grid md:grid-cols-3 gap-8">
        <div class="glass-panel p-8 rounded-3xl text-right flex flex-col justify-between card-glow">
          <div class="text-amber-400 text-lg mb-3">★★★★★</div>
          <p class="text-titanium text-sm italic mb-6">"ما شاء الله شغل متقن جداً، رجعت السيارة وكالة من التلميع والنانو سيراميك. معاملة راقية جداً."</p>
          <strong class="text-cyber text-sm">- محمد الطراونة</strong>
        </div>
        <div class="glass-panel p-8 rounded-3xl text-right flex flex-col justify-between card-glow">
          <div class="text-amber-400 text-lg mb-3">★★★★★</div>
          <p class="text-titanium text-sm italic mb-6">"أفضل مركز عناية بالسيارات في الكرك، نظافة داخلية واستلام على الوقت المحدد بالضبط."</p>
          <strong class="text-cyber text-sm">- خالد المجالي</strong>
        </div>
        <div class="glass-panel p-8 rounded-3xl text-right flex flex-col justify-between card-glow">
          <div class="text-amber-400 text-lg mb-3">★★★★★</div>
          <p class="text-titanium text-sm italic mb-6">"خدمة ممتازة وأسعار منافسة جداً مقارنة بالجودة العالية للمواد المستخدمة."</p>
          <strong class="text-cyber text-sm">- عمر العبادي</strong>
        </div>
      </div>
    </div>
  </section>

  <!-- Location & Contact -->
  <section id="location" class="py-20 max-w-7xl mx-auto px-4 border-t border-white/10 w-full">
    <div class="text-center mb-12">
      <h3 class="text-3xl font-black text-white">موقعنا والتواصل المباشر</h3>
      <div class="h-1 w-16 bg-electric mx-auto mt-3 rounded-full"></div>
    </div>
    
    <div class="glass-panel p-8 md:p-12 rounded-3xl max-w-3xl mx-auto space-y-4 text-right border border-electric/30">
      <p class="text-titanium"><strong>المالك / Ownership:</strong> <span class="text-white">أحمد العضايلة (Ahmad Adaileh)</span></p>
      <p class="text-titanium"><strong>رقم الهاتف / الواتساب:</strong> <a href="https://wa.me/962776999555" class="text-cyber font-bold hover:underline">0776999555</a></p>
      <p class="text-titanium"><strong>البريد الإلكتروني:</strong> <a href="mailto:ahmadadaileh1995@gmail.com" class="text-cyber hover:underline">hmadadaileh1995@gmail.com</a></p>
      <p class="text-titanium"><strong>العنوان:</strong> <span class="text-white">الأردن - الكرك</span></p>
      <p class="text-titanium"><strong>ساعات العمل:</strong> <span class="text-white">يومياً من الساعة 9:00 صباحاً حتى 9:00 مساءً</span></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-obsidian py-8 text-center text-titanium text-xs border-t border-white/10 px-4">
    <p>© جميع الحقوق محفوظة - مركز العضايله للعناية بالمركبات - الكرك | ملكية أحمد العضايلة (Ownership: Ahmad Adaileh) | hmadadaileh1995@gmail.com</p>
  </footer>

</body>
</html>
