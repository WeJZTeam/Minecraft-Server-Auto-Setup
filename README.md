# 🎮 JZminSetup - Minecraft Server Auto-Setup Tool

<div align="center">

![Minecraft](https://img.shields.io/badge/Minecraft-Java%20%7C%20Bedrock-brightgreen)
![Python](https://img.shields.io/badge/Python-3.6+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

**أداة تلقائية لإعداد خوادم ماينكرافت بسهولة وسرعة**

</div>

---
# طريقتاالتثبيت وتشغيل
wget https://github.com/WeJZTeam/Minecraft-Server-Auto-Setup/blob/main/JZminSetup
## 📋 جدول المحتويات

- [🎯 نظرة عامة](#-نظرة-عامة)
- [✨ المميزات](#-المميزات)
- [🚀 التثبيت والاستخدام](#-التثبيت-والاستخدام)
- [📦 أنواع الخوادم المدعومة](#-أنواع-الخوادم-المدعومة)
- [⚙️ المتطلبات](#️-المتطلبات)
- [🔧 الاستخدام](#-الاستخدام)
- [📁 هيكل المشروع](#-هيكل-المشروع)
- [🤝 المساهمة](#-المساهمة)
- [📄 الترخيص](#-الترخيص)

---

## 🎯 نظرة عامة

**JZminSetup** هي أداة Python متقدمة لإعداد خوادم ماينكرافت تلقائياً. تم تصميمها لتسهيل عملية إنشاء وإدارة خوادم ماينكرافت من جميع الأنواع (Java و Bedrock) مع واجهة تفاعلية ملونة وسهلة الاستخدام.

### 🎨 المميزات البصرية
- واجهة تفاعلية ملونة مع رموز ANSI
- رسائل واضحة ومفهومة باللغة العربية
- تقدم مرئي لعمليات التحميل والبناء

---

## ✨ المميزات

### 🔥 المميزات الأساسية
- **إعداد تلقائي** لجميع أنواع خوادم ماينكرافت
- **تحميل تلقائي** لأحدث إصدارات الخوادم
- **بناء تلقائي** لخوادم Spigot و Bukkit باستخدام BuildTools
- **واجهة تفاعلية** سهلة الاستخدام
- **دعم متعدد اللغات** (عربي/إنجليزي)

### 🛠️ المميزات التقنية
- **إدارة الإصدارات** - اختيار من أحدث الإصدارات المتاحة
- **تحميل ذكي** - إعادة المحاولة التلقائية عند فشل التحميل
- **بناء ذكي** - استخدام BuildTools عند الحاجة
- **إعداد EULA** تلقائي
- **أوامر بدء التشغيل** محفوظة

---

## 🚀 التثبيت والاستخدام

### 📋 المتطلبات الأساسية


#### لنظام Linux/macOS/win:
```bash



---

## 📦 أنواع الخوادم المدعومة

### 🟢 خوادم Java Edition

| النوع | الوصف | المميزات |
|-------|-------|----------|
| **Vanilla** | الخادم الرسمي من Mojang | - مستقر وموثوق<br>- بدون تعديلات<br>- مناسب للمبتدئين |
| **Paper** | خادم محسن للأداء | - أداء محسن<br>- دعم البلاجنز<br>- تحديثات سريعة |
| **Spigot** | خادم شائع للبلاجنز | - دعم واسع للبلاجنز<br>- مجتمع كبير<br>- أداء جيد |
| **Bukkit** | الخادم الأساسي | - أساس لمعظم الخوادم<br>- دعم البلاجنز<br>- مرونة عالية |

### 🔵 خوادم Bedrock Edition

| النوع | الوصف | المميزات |
|-------|-------|----------|
| **Bedrock** | الخادم الرسمي للويندوز | - دعم الأجهزة المحمولة<br>- أداء محسن<br>- تحديثات تلقائية |

---

## ⚙️ المتطلبات

### 💻 متطلبات النظام
- **نظام التشغيل:** Windows 10/11, Linux, macOS
- **Python:** الإصدار 3.6 أو أحدث
- **Java:** JDK 8 أو أحدث (للخوادم الجافا)
- **الذاكرة:** 2GB RAM كحد أدنى
- **المساحة:** 1GB مساحة خالية

### 🌐 متطلبات الشبكة
- **اتصال إنترنت** مستقر
- **سرعة تحميل** 5 Mbps كحد أدنى
- **وصول مفتوح** للمنافذ (25565 للجافا، 19132 للبدروك)

---

## 🔧 الاستخدام

### 🎯 الخطوات الأساسية

1. **تشغيل الأداة:**
```bash
python JZminSetup.py
```

2. **اختيار نوع الخادم:**
   - Java Edition
   - Bedrock Edition

3. **اختيار نوع الخادم (للجافا):**
   - Vanilla
   - Paper
   - Spigot
   - Bukkit

4. **اختيار الإصدار:**
   - سيتم عرض أحدث 5 إصدارات متاحة

5. **انتظار الإعداد التلقائي:**
   - تحميل الملفات
   - بناء الخادم (إذا لزم الأمر)
   - إعداد EULA
   - تشغيل أولي

### 📁 الملفات المُنشأة

```
server_[type]_[version]/
├── server.jar (أو paper-*.jar, spigot-*.jar, etc.)
├── eula.txt
├── server.properties
├── START_COMMAND.txt
└── logs/
```

### 🚀 تشغيل الخادم

بعد الإعداد، يمكنك تشغيل الخادم باستخدام:

```bash
# للخوادم الجافا
java -Xmx1024M -Xms1024M -jar server.jar nogui

# للخوادم البدروك
bedrock_server.exe
```

---

## 📁 هيكل المشروع

```
JZminSetup/
├── JZminSetup.py          # الملف الرئيسي للأداة
├── JZminSetup             # ملف تنفيذي (Linux/macOS)
├── README.md              # ملف التوثيق
├── LICENSE                # رخصة المشروع
└── examples/              # أمثلة للاستخدام
    ├── server_configs/    # إعدادات الخوادم
    └── scripts/           # سكريبتات مساعدة
```

### 🔧 الملفات الرئيسية

| الملف | الوصف |
|-------|-------|
| `JZminSetup.py` | الكود الرئيسي للأداة |
| `JZminSetup` | ملف تنفيذي للأنظمة الشبيهة بـ Unix |
| `README.md` | ملف التوثيق الشامل |

---

## 🛠️ المميزات التقنية المتقدمة

### 🔄 إدارة الإصدارات
- **تحديث تلقائي** لأحدث الإصدارات
- **دعم الإصدارات القديمة** للتوافق
- **تحقق من التوافق** بين الإصدارات

### 🏗️ بناء الخوادم
- **BuildTools التلقائي** لـ Spigot/Bukkit
- **تحسين الأداء** أثناء البناء
- **معالجة الأخطاء** الذكية

### 📊 المراقبة والتتبع
- **تقدم مرئي** للعمليات
- **سجلات مفصلة** للعمليات
- **تقارير الأخطاء** المفصلة

---

## 🤝 المساهمة

نرحب بمساهماتكم! إليك كيفية المساهمة:

### 📝 كيفية المساهمة

1. **Fork المشروع**
2. **إنشاء فرع جديد** (`git checkout -b feature/AmazingFeature`)
3. **Commit التغييرات** (`git commit -m 'Add some AmazingFeature'`)
4. **Push للفرع** (`git push origin feature/AmazingFeature`)
5. **إنشاء Pull Request**

### 🐛 الإبلاغ عن الأخطاء

إذا وجدت خطأ، يرجى:
1. فتح Issue جديد
2. وصف المشكلة بالتفصيل
3. إرفاق سجلات الأخطاء
4. تحديد خطوات إعادة الإنتاج

### 💡 اقتراح المميزات

لاقتراح ميزات جديدة:
1. فتح Issue جديد
2. وصف الميزة المطلوبة
3. شرح الفائدة منها
4. اقتراح طريقة التنفيذ

---

## 📄 الترخيص

هذا المشروع مرخص تحت رخصة MIT. راجع ملف `LICENSE` للتفاصيل.

```
MIT License

Copyright (c) 2024 JZminSetup

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 الشكر والتقدير

- **Mojang Studios** - لتطوير ماينكرافت
- **PaperMC Team** - لخادم Paper
- **SpigotMC Team** - لخادم Spigot
- **Bukkit Team** - لخادم Bukkit
- **مجتمع ماينكرافت** - للدعم المستمر

---

## 📞 الدعم والاتصال

- **GitHub Issues:** للإبلاغ عن الأخطاء واقتراح المميزات
- **Discord:** للدعم المباشر والمحادثة
- **Email:** للاستفسارات العامة

---

<div align="center">

**⭐ إذا أعجبك المشروع، لا تنس إعطاءه نجمة! ⭐**

**🎮 استمتع بلعب ماينكرافت مع أصدقائك! 🎮**

</div> 