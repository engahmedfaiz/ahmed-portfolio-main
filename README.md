# 🚀 Ahmed Faiz Mashrah - Professional Portfolio

## 📋 نظرة عامة
موقع شخصي احترافي لأحمد فايز مشرح - مطور ويب وتطبيقات محمولة متخصص في Laravel وFlutter والتقنيات الحديثة.

## ✨ المميزات
- 🎨 تصميم حديث ومتجاوب
- 🌐 دعم اللغتين العربية والإنجليزية
- 🌙 وضع مظلم/فاتح
- ⚡ أداء عالي مع Next.js 15.3.4
- 📱 متوافق مع جميع الأجهزة
- 🔒 خطوط محلية للخصوصية والأداء
- 📧 نظام تواصل متقدم
- 🎭 رسوم متحركة سلسة

## 🛠️ التقنيات المستخدمة
- **Framework:** Next.js 15.3.4
- **Styling:** Tailwind CSS
- **Animation:** Framer Motion
- **Icons:** Lucide React
- **Email:** Resend
- **Validation:** Zod
- **UI Components:** Radix UI
- **Font:** Cairo (Arabic) + Inter (English)

## 🚀 التثبيت والتشغيل

### المتطلبات
- Node.js 22.11.0 أو أحدث
- npm 10.0.0 أو أحدث

### خطوات التثبيت

1. **استنساخ المشروع:**
\`\`\`bash
git clone https://github.com/engahmedfaiz/portfolio.git
cd portfolio
\`\`\`

2. **تثبيت التبعيات:**
\`\`\`bash
npm install
\`\`\`

3. **إعداد المتغيرات البيئية:**
\`\`\`bash
cp .env.example .env.local
\`\`\`
ثم قم بتعديل `.env.local` وإضافة:
\`\`\`env
RESEND_API_KEY=your_resend_api_key_here
EMAIL_FROM_DOMAIN=yourdomain.com
\`\`\`

4. **تحميل الخطوط محلياً:**
\`\`\`bash
npm run setup-fonts
\`\`\`

5. **فحص المشروع:**
\`\`\`bash
npm run check
\`\`\`

6. **تشغيل المشروع:**
\`\`\`bash
npm run dev
\`\`\`

## 📁 هيكل المشروع

\`\`\`
├── app/                    # صفحات Next.js
│   ├── about/             # صفحة من أنا
│   ├── contact/           # صفحة التواصل
│   ├── projects/          # صفحة المشاريع
│   ├── skills/            # صفحة المهارات
│   ├── actions/           # Server Actions
│   ├── fonts.css          # تعريفات الخطوط المحلية
│   ├── globals.css        # الأنماط العامة
│   └── layout.tsx         # التخطيط الرئيسي
├── components/            # المكونات القابلة لإعادة الاستخدام
│   └── ui/               # مكونات واجهة المستخدم
├── contexts/             # React Contexts
├── hooks/                # Custom Hooks
├── lib/                  # المكتبات والأدوات
├── public/               # الملفات العامة
│   └── fonts/           # الخطوط المحلية
└── scripts/              # سكريبتات الأتمتة
\`\`\`

## 🎨 الخطوط المحلية

تم تحسين الأداء باستخدام خطوط محلية:

### تحميل الخطوط:
\`\`\`bash
npm run download-fonts
\`\`\`

### الخطوط المدعومة:
- **Cairo:** للنصوص العربية (400, 500, 600, 700)
- **Inter:** للنصوص الإنجليزية (400, 500, 600, 700)

### الفوائد:
- ⚡ تحميل فوري (لا توجد طلبات خارجية)
- 🔒 خصوصية أفضل (لا تتبع من Google)
- 📱 عمل بدون إنترنت
- 🎯 تحسين FOIT/FOUT

## 📧 إعداد البريد الإلكتروني

1. **إنشاء حساب Resend:**
   - اذهب إلى [resend.com](https://resend.com)
   - أنشئ حساب جديد
   - احصل على API Key

2. **إضافة المتغيرات البيئية:**
\`\`\`env
RESEND_API_KEY=re_xxxxxxxxxxxxxxxxxxxxxxxxxx
EMAIL_FROM_DOMAIN=yourdomain.com
\`\`\`

3. **اختبار النظام:**
\`\`\`bash
npm run dev
\`\`\`
ثم اذهب إلى صفحة التواصل واختبر إرسال رسالة.

## 🚀 النشر

### Vercel (موصى به):
\`\`\`bash
npm run build
vercel --prod
\`\`\`

### GitHub Pages:
\`\`\`bash
npm run build
npm run export
\`\`\`

### خادم مخصص:
\`\`\`bash
npm run build
npm start
\`\`\`

## 🔧 الأوامر المتاحة

\`\`\`bash
# التطوير
npm run dev              # تشغيل وضع التطوير
npm run build           # بناء للإنتاج
npm run start           # تشغيل الإنتاج
npm run preview         # معاينة البناء

# الجودة
npm run lint            # فحص وإصلاح الكود
npm run type-check      # فحص TypeScript
npm run check           # فحص شامل للمشروع

# الخطوط
npm run download-fonts  # تحميل الخطوط
npm run setup-fonts     # إعداد كامل للخطوط

# التحليل
npm run analyze         # تحليل حجم الحزمة
npm run clean           # تنظيف الملفات المؤقتة
\`\`\`

## 🎯 تحسينات الأداء

- ✅ **خطوط محلية** - تحميل فوري
- ✅ **تحسين الصور** - WebP + تحميل تدريجي
- ✅ **تقسيم الكود** - تحميل حسب الحاجة
- ✅ **ضغط الأصول** - أحجام أصغر
- ✅ **PWA جاهز** - عمل بدون إنترنت
- ✅ **SEO محسن** - فهرسة أفضل

## 🌐 الدعم متعدد اللغات

- 🇸🇦 العربية (افتراضي)
- 🇺🇸 الإنجليزية
- 🔄 تبديل سلس بين اللغات
- 📱 دعم RTL/LTR

## 📱 التوافق

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ جميع الأجهزة المحمولة

## 🤝 المساهمة

1. Fork المشروع
2. أنشئ فرع للميزة (`git checkout -b feature/amazing-feature`)
3. Commit التغييرات (`git commit -m 'Add amazing feature'`)
4. Push للفرع (`git push origin feature/amazing-feature`)
5. افتح Pull Request

## 📄 الترخيص

هذا المشروع مرخص تحت رخصة MIT - انظر ملف [LICENSE](LICENSE) للتفاصيل.

## 📞 التواصل

- **الموقع:** [engahmedfaiz.github.io/portfoli](https://engahmedfaiz.github.io/portfoli)
- **البريد:** engahmedfaiz5@gmail.com
- **GitHub:** [@engahmedfaiz](https://github.com/engahmedfaiz)
- **الهاتف:** +(967)780138083

## 🙏 شكر وتقدير

- [Next.js](https://nextjs.org/) - إطار العمل الرائع
- [Tailwind CSS](https://tailwindcss.com/) - للتصميم السريع
- [Framer Motion](https://framer.com/motion/) - للرسوم المتحركة
- [Radix UI](https://radix-ui.com/) - لمكونات الواجهة
- [Lucide](https://lucide.dev/) - للأيقونات الجميلة

---

**صنع بـ ❤️ في صنعاء، اليمن**
