# 🚀 دليل نشر موقع MIDOOO على الإنترنت (Online Deployment)

تم تجهيز جميع إعدادات الموقع بالكامل ليصبح جاهزاً للنشر بضغطة زر (Production-Ready) على منصات الاستضافة السحابية العالمية.

---

## 🌟 الخيار الأسهل والموصى به: النشر المجاني عبر Render.com

منصة **Render** هي الخيار الأنسب والأسهل لاستضافة تطبيقات Node.js، وستمنحك رابطاً سريعاً ومجانياً ومحمياً بشهادة أمان SSL (مثل: `https://midooo.onrender.com`).

### 📌 الخطوات البسيطة (3 خطوات فقط):

### الخطوة 1: رفع المشروع إلى حسابك على GitHub
1. ادخل إلى [github.com](https://github.com) وأنشئ مستودعاً جديداً (New Repository) وسمّه مثلاً: `midooo-qcm`.
2. في مجلد المشروع في حاسوبك، افتح موجه الأوامر (Terminal أو PowerShell) ونفذ الأوامر التالية:
```bash
git init
git add .
git commit -m "Launch MIDOOO Platform"
git branch -M main
git remote add origin https://github.com/اسم-حسابك/midooo-qcm.git
git push -u origin main
```

---

### الخطوة 2: ربط المشروع مع Render
1. ادخل إلى موقع [render.com](https://render.com) وأنشئ حساباً مجانياً (عبر حسابك في GitHub).
2. اضغط على زر **« New + »** في الأعلى واختر **« Web Service »**.
3. اختر مستودع **`midooo-qcm`** الذي رفعته للتو.
4. املأ الإعدادات التالية (ستجد أغلبها معبأة تلقائياً بفضل ملف `render.yaml`):
   * **Name**: `midooo`
   * **Language**: `Node`
   * **Branch**: `main`
   * **Build Command**: `npm install && npm run build`
   * **Start Command**: `npm start`
   * **Plan**: `Free`
5. اضغط على **« Create Web Service »**.

---

### الخطوة 3: مبارك! موقعك أصبح حياً على الإنترنت 🎉
* في غضون دقيقتين، ستقوم المنصة ببناء الموقع وسيعطيك الرابط الرسمي مثل:
  `https://midooo.onrender.com`
* يمكنك مشاركة هذا الرابط مع الطلاب أو نشره في مجموعات الفيسبوك والواتساب!

---

## 🌐 ربط اسم نطاق خاص (Custom Domain مثل midooo.ma أو midooo.com)
إذا قمت بشراء دومين خاص (من مواقع مثل Hostinger أو GoDaddy أو Genious.ma):
1. في لوحة تحكم Render، اذهب إلى إعدادات مشروعك واضغط على **« Custom Domains »**.
2. أضف الدومين الخاص بك (مثلاً `midooo.ma`).
3. انسخ إعدادات الـ CNAME التي يعطيها لك Render وألصقها في لوحة تحكم الدومين.
4. سيصبح موقعك متاحاً مباشرة على: `https://midooo.ma`.

---

## 🔑 تذكير ببيانات المدير (Admin) بعد النشر:
* **البريد الإلكتروني**: `admin@midooo.ma`
* **كلمة المرور**: `admin`
*(يُرجى تغيير كلمة المرور فوراً من لوحة تحكم الأدمن بعد نشره على الإنترنت لضمان الأمان التام).*
