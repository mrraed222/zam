<div align="center">

# ☕ زام للقهوة المختصة — نظام التقييم الحديث

<p align="center">
  <img src="https://res.cloudinary.com/dr26mwbbx/image/upload/v1778529393/IMG_0212_p3klkw.png" alt="Zam Logo" width="120">
</p>

**منصة تقييم أداء الموظفين التفاعلية**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat&logo=google&logoColor=white)](https://developers.google.com/apps-script)

</div>

---

## 📋 وصف المشروع

نظام تقييم أداء موظفين متكامل وعصري لسلسلة **زام للقهوة المختصة**، يتيح للمشرفين:

- ✅ تقييم أداء الموظفين بدقة عالية (مقياس 1-10)
- ✅ تصدير تقارير PDF احترافية
- ✅ إرسال التقييمات عبر واتساب مباشرة
- ✅ داشبورد تحليلي تفاعلي (Chart.js)
- ✅ لوحة إدارة لإدارة بنود التقييم ديناميكياً
- ✅ مزامنة سحابية مع Google Sheets

---

## 🎯 المميزات الرئيسية

| الميزة | الوصف |
|--------|-------|
| 🎨 **تصميم عصري** | واجهة مستخدم احترافية بألوان القهوة الدافئة |
| 📊 **تقييم مرن** | دعم 4 فئات وظيفية (باريستا، ويتر، مطبخ، مشرف) |
| 📱 **تجاوب كامل** | يعمل على جميع الأجهزة (موبايل، تابلت، ديسكتوب) |
| 📄 **تصدير PDF** | تقارير مطبوعة احترافية جاهزة للتوقيع |
| 💬 **واتساب** | إرسال التقييم مباشرة للموظف |
| ☁️ **سحابي** | حفظ البيانات في Google Sheets |
| 🔐 **لوحة إدارة** | تعديل البنود وحماية بكلمة مرور |
| 📈 **داشبورد** | رسوم بيانية وتحليلات أداء |

---

## 🚀 طريقة التشغيل

### 1. تشغيل الواجهة الأمامية (Frontend)

```bash
# استنساخ المشروع
git clone https://github.com/اسمك/zam-evaluation-system.git
cd zam-evaluation-system

# فتح الملف في المتصفح
# أو استخدم Live Server في VS Code
```

> **ملاحظة:** الملف `index.html` يعمل مباشرة في أي متصفح حديث.

### 2. ربط Google Apps Script (Backend)

1. افتح [script.google.com](https://script.google.com) وانشئ مشروع جديد
2. انسخ محتوى `apps-script.gs` في المحرر
3. عدّل `SHEET_ID` بمعرف الـ Google Sheet الخاص بك
4. انشر كـ **Web App** (Execute as: Me, Access: Anyone)
5. انسخ رابط الـ Web App وضعه في `CONFIG.SCRIPT_URL` داخل `index.html`

### 3. إنشاء Google Sheet

أنشئ Sheet جديد وانسخ الـ ID من الرابط:
```
https://docs.google.com/spreadsheets/d/【SHEET_ID】/edit
```

---

## 📁 هيكل المشروع

```
zam-evaluation-system/
├── 📄 index.html          ← الواجهة الرئيسية (HTML + CSS + JS)
├── 📄 apps-script.gs      ← كود Google Apps Script (Backend)
├── 📄 README.md           ← هذا الملف
└── 📄 LICENSE             ← ترخيص المشروع
```

---

## 🛡️ الأمان

- لوحة الإدارة محمية بكلمة مرور (`2026`)
- البيانات تُحفظ في Google Sheets الخاصة بك
- لا يتم مشاركة البيانات مع أي طرف ثالث

---

## 🖼️ معاينة

<p align="center">
  <img src="https://via.placeholder.com/800x400/2C1810/F5EDD8?text=Zam+Evaluation+System+Preview" alt="Preview" width="80%">
</p>

---

## 🤝 المساهمة

نرحب بمساهماتكم! يمكنكم:
- 🐛 الإبلاغ عن مشاكل (Issues)
- 💡 اقتراح ميزات جديدة
- 🔧 إرسال تحسينات (Pull Requests)

---

## 📄 الترخيص

هذا المشروع مرخص بموجب [MIT License](LICENSE).

---

<div align="center">

**صنع بـ ❤️ لـ زام للقهوة المختصة**

☕ **Zam Specialty Coffee** — *نقيّم لنرتقي*

</div>
