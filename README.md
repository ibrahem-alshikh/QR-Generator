<div align="center">

<img src="https://img.shields.io/badge/QR-Generator-637545?style=for-the-badge&labelColor=28301C" alt="QR Generator" height="46">

# ▦ QR Generator

### مولّد رموز QR — جميل، سريع، وبملف واحد

**Beautiful · Fast · Single-file · Arabic-ready**

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Canvas_API-637545?style=flat-square" alt="Canvas API">
  <img src="https://img.shields.io/badge/No_Build-Zero_Dependencies-455230?style=flat-square" alt="No build">
</p>
<p>
  <img src="https://img.shields.io/badge/العربية-RTL-9A7E3B?style=flat-square" alt="Arabic RTL">
  <img src="https://img.shields.io/badge/English-LTR-28301C?style=flat-square" alt="English">
  <img src="https://img.shields.io/badge/Dark_Mode-supported-343D2A?style=flat-square" alt="Dark mode">
  <img src="https://img.shields.io/badge/Mobile-friendly-637545?style=flat-square" alt="Mobile">
  <img src="https://img.shields.io/badge/GitHub_Pages-ready-181717?style=flat-square&logo=github" alt="GitHub Pages">
</p>

**[🌐 جرّبه الآن · Live Demo](#-النشر-على-github-pages--deploy)** &nbsp;|&nbsp; **[🇸🇦 العربية](#-العربية)** &nbsp;|&nbsp; **[🇬🇧 English](#-english)**

</div>

---

## 🇸🇦 العربية

### ✨ ما هو هذا المشروع؟

أداة لتوليد رموز QR تعمل بالكامل داخل المتصفح. تفتح الملف وتبدأ، بدون خادم ولا تثبيت ولا حساب، وبياناتك لا تغادر جهازك.

### 🎯 المميزات

| | الميزة | التفاصيل |
|---|---|---|
| 🔗 | **7 أنواع محتوى** | رابط، واي فاي، بريد، رسالة SMS، هاتف، موقع جغرافي، نص |
| 🔤 | **دعم كامل للعربية** | ترميز UTF-8، تم اختباره بفك الرمز والتحقق من النص العربي |
| 🎨 | **18 قالباً جاهزاً** | ألوان وأشكال شائعة (أزرق، أخضر، أحمر، ذهبي، وغيرها) في سطرين مرتبين |
| 🧩 | **تخصيص كامل** | شكل النقاط، إطار العيون، بؤبؤ العين، الألوان، الحجم والحشو |
| 🫧 | **نقاط متصلة** | في الأشكال المستديرة تلتحم النقاط المتجاورة وتظهر المنفردة مستديرة |
| 🛡️ | **تصحيح الأخطاء** | أربعة مستويات: 7% و15% و25% و30% |
| 🖼️ | **شعار داخل الرمز** | رفع صورة أو لصقها (Ctrl+V) مع التحكم بالحجم والهامش |
| 🪟 | **خلفية شفافة** | في التنزيل الفردي وفي التصدير الجماعي |
| 📦 | **تصدير جماعي** | ملف Excel/CSV ← ملف ZIP فيه صورة PNG لكل رمز (حتى 100) |
| 🌗 | **وضع فاتح وداكن** | يتبدل بضغطة واحدة |
| 🌍 | **عربي وإنجليزي** | واجهة RTL و LTR كاملة |
| 📱 | **يعمل على الجوال** | واجهة متجاوبة وأزرار مناسبة للّمس |

### 🚀 البدء السريع

```bash
# الطريقة الأسهل: افتح الملف في المتصفح
open index.html
```

لا يوجد `npm install` ولا خطوات بناء. الملف الواحد هو التطبيق كله.

### 🌐 النشر على GitHub Pages

1. ارفع `index.html` و`README.md` إلى مستودعك.
2. افتح **Settings ← Pages**.
3. اختر الفرع `main` والمجلد `/ (root)` ثم احفظ.
4. بعد دقيقة يعمل موقعك على:
   ```
   https://<username>.github.io/<repo>/
   ```

### 📊 التصدير الجماعي

جهّز ملف Excel أو CSV بهذا الشكل:

| URL | Label |
|---|---|
| `https://example.com` | Example |
| `https://google.com` | Google |
| `مرحبا` | عربي |

ثم افتح **تصدير مجموعة رموز QR** وارفع الملف واضغط **توليد ZIP**. يمكنك تنزيل نموذج جاهز من النافذة نفسها.

### 🧰 التقنيات والمكتبات

**اللغات**

| اللغة | الاستخدام |
|---|---|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square) | هيكل الصفحة |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat-square) | التصميم: CSS Variables، Grid، Flexbox، الوضع الداكن، التجاوب مع الجوال |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square) | المنطق بالكامل (Vanilla JS) بدون إطار عمل |

**المكتبات**

| المكتبة | الدور | الترخيص | كيف تُحمَّل |
|---|---|---|---|
| [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) `1.4.4` | توليد مصفوفة الرمز مع ترميز UTF-8 | MIT | مدمجة داخل الملف |
| [JSZip](https://github.com/Stuk/jszip) `3.10.1` | إنشاء ملف ZIP في المتصفح | MIT | مدمجة داخل الملف |
| [SheetJS](https://sheetjs.com/) `0.18.5` | قراءة ملفات Excel وCSV وكتابة النموذج | Apache-2.0 | من CDN عند الحاجة |

**تقنيات المتصفح**

| التقنية | الاستخدام |
|---|---|
| Canvas 2D API | رسم النقاط والعيون والشعار والشفافية |
| FileReader و Clipboard API | رفع الصور ولصقها ونسخ الرمز |
| TextEncoder | ترميز النص العربي بصيغة UTF-8 |
| Blob و `toBlob()` | تصدير صور PNG |

**الخط:** [Firjar](https://fonts.google.com/specimen/Firjar) من Google Fonts.

### 🧱 كيف يعمل؟

```
المحتوى ──► بناء النص ──► qrcode-generator ──► مصفوفة 0/1
                                                   │
                       Canvas ◄── رسم النقاط والعيون والشعار
                          │
              PNG ◄───────┴───────► ZIP (JSZip)
```

### 📁 هيكل المشروع

```
📦 qr-generator
 ┣ 📄 index.html    ← التطبيق كامل (HTML + CSS + JS + المكتبات)
 ┗ 📄 README.md     ← هذا الملف
```

### ⚠️ نصائح قبل الطباعة

- جرّب مسح الرمز بجوالك قبل الطباعة، خصوصاً الأشكال الدائرية والمعيّنة.
- حافظ على تباين عالٍ بين لون الرمز والخلفية (الأغمق على الأفتح).
- عند إضافة شعار كبير ارفع مستوى تصحيح الأخطاء إلى 25% أو 30%.
- التصدير الجماعي يحتاج اتصالاً بالإنترنت لتحميل SheetJS.

---

## 🇬🇧 English

### ✨ What is this?

A QR code generator that runs entirely in your browser. Open the file and go: no server, no install, no account, and your data never leaves your device.

### 🎯 Features

| | Feature | Details |
|---|---|---|
| 🔗 | **7 content types** | URL, Wi-Fi, Email, SMS, Phone, Geo location, Text |
| 🔤 | **Full Arabic support** | UTF-8 encoding, verified by decoding the generated codes |
| 🎨 | **18 presets** | Common colors and shapes, laid out in two tidy rows |
| 🧩 | **Deep customization** | Dot shape, eye frame, eye pupil, colors, size and padding |
| 🫧 | **Connected dots** | In rounded styles neighbors merge, isolated dots stay round |
| 🛡️ | **Error correction** | Four levels: 7%, 15%, 25%, 30% |
| 🖼️ | **Center logo** | Upload or paste (Ctrl+V), with size and margin control |
| 🪟 | **Transparent background** | Works in single download and batch export |
| 📦 | **Batch export** | Excel/CSV → ZIP with one PNG per code (up to 100) |
| 🌗 | **Light and dark mode** | One-click toggle |
| 🌍 | **Arabic and English** | Full RTL and LTR interface |
| 📱 | **Mobile friendly** | Responsive layout with touch-sized controls |

### 🚀 Quick start

```bash
# Easiest way: just open the file in your browser
open index.html
```

No `npm install`, no build step. The single file is the whole app.

### 🌐 Deploy

1. Push `index.html` and `README.md` to your repository.
2. Open **Settings → Pages**.
3. Choose branch `main` and folder `/ (root)`, then save.
4. After a minute your site is live at:
   ```
   https://<username>.github.io/<repo>/
   ```

### 📊 Batch export

Prepare an Excel or CSV file like this:

| URL | Label |
|---|---|
| `https://example.com` | Example |
| `https://google.com` | Google |

Open **Export a set of QR codes**, upload the file, and click **Generate ZIP**. A ready-made template can be downloaded from the same dialog.

### 🧰 Tech stack

**Languages**

| Language | Used for |
|---|---|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square) | Page structure |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat-square) | Styling: CSS variables, Grid, Flexbox, dark mode, mobile layout |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square) | All logic (vanilla JS, no framework) |

**Libraries**

| Library | Role | License | Loading |
|---|---|---|---|
| [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) `1.4.4` | Builds the QR matrix with UTF-8 support | MIT | Bundled in the file |
| [JSZip](https://github.com/Stuk/jszip) `3.10.1` | Creates ZIP files in the browser | MIT | Bundled in the file |
| [SheetJS](https://sheetjs.com/) `0.18.5` | Reads Excel/CSV and writes the template | Apache-2.0 | CDN, on demand |

**Browser APIs**

| API | Used for |
|---|---|
| Canvas 2D | Drawing dots, eyes, logo and transparency |
| FileReader and Clipboard | Uploading and pasting images, copying the code |
| TextEncoder | Encoding Arabic text as UTF-8 |
| Blob and `toBlob()` | Exporting PNG images |

**Font:** [Firjar](https://fonts.google.com/specimen/Firjar) from Google Fonts.

### ⚠️ Print tips

- Test-scan with a phone before printing, especially round and diamond shapes.
- Keep strong contrast between the code color and the background (dark on light).
- With a large logo, raise error correction to 25% or 30%.
- Batch export needs an internet connection to load SheetJS.

---

## 🤝 الشكر والتقدير · Credits

تم بناء هذا المشروع بالتعاون مع مساعدين من الذكاء الاصطناعي:

- 🟠 **[Claude](https://www.anthropic.com/claude)** من Anthropic: كتابة الكود، إصلاح الأخطاء، تحسين التصميم والتجاوب مع الجوال، والاختبار الشامل.
- 🔵 **[DeepSeek](https://www.deepseek.com/)**: المساعدة في التطوير والأفكار.

This project was built together with AI assistants: **Claude** (code, bug fixes, design polish, mobile layout, and testing) and **DeepSeek** (development help and ideas).

---

<div align="center">

### صُنع بـ ❤️ و ☕ وقليل من الصبر
### Made with ❤️, ☕ and a little patience

⭐ إذا أعجبك المشروع فلا تنسَ نجمة على GitHub · If you like it, give it a star

</div>
