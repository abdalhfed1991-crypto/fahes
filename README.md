# FAHES PC Diagnostic (فاحص)

برنامج لويندوز يفحص اللابتوب أو الكمبيوتر ويعرض حالته، ويصدر تقريراً يمكن طباعته. واجهته بالعربية والإنجليزية.

## التحميل

**[تحميل FAHES_Setup_1.2.0.exe](https://github.com/abdalhfed1991-crypto/fahes/releases/latest/download/FAHES_Setup_1.2.0.exe)**

يعمل على ويندوز 11 وويندوز 10 (إصدار 1809 فأحدث) بنظام 64 بت.

## التثبيت

1. شغّل الملف بعد تحميله، ووافق على طلب صلاحيات المسؤول.
2. البرنامج غير موقّع رقمياً بعد، لذلك قد يظهر تحذير «حمى Windows جهاز الكمبيوتر الخاص بك». إذا كنت قد حمّلته من هذه الصفحة، اضغط «مزيد من المعلومات» ثم «التشغيل على أي حال».
3. أكمل خطوات التثبيت، وشغّل البرنامج من قائمة ابدأ أو من سطح المكتب.

لإزالته: إعدادات ويندوز ← التطبيقات ← FAHES PC Diagnostic.

## ماذا يعرض

- معلومات النظام والرقم التسلسلي.
- المعالج والرام واستخدامهما لحظة بلحظة.
- الأقراص: الحالة والمساحة، والحرارة والاستهلاك وساعات التشغيل إذا كان القرص يبلغ عنها.
- كرت الشاشة: الذاكرة والتعريف، والحرارة والاستخدام لكروت NVIDIA فقط.
- البطارية: الشحن والسعة ودورات الشحن ونسبة الصحة.
- نتيجة الفحص: لم تُكتشف مشاكل، أو يوجد تنبيهات، أو الفحص غير مكتمل، أو تعذّر الفحص.
- تقرير HTML فيه اسم المحل والفني والزبون، يُحفظ ويُطبع.

## حدود البرنامج

البرنامج يقرأ ما يبلغ عنه الجهاز، ولا يجري اختبار ضغط أو فحصاً فعلياً للقطع. لذلك فإن نتيجة «لم تُكتشف مشاكل» لا تثبت سلامة القطع.

بعض القراءات لا تتوفر في كل الأجهزة، مثل حرارة الجهاز وعدد دورات الشحن.

---

**English:** FAHES is a Windows PC diagnostic tool with an Arabic and English interface. It reads what the PC reports (system, CPU, RAM, disks, GPU, battery) and produces a printable HTML report. It does not run stress tests. [Download the installer](https://github.com/abdalhfed1991-crypto/fahes/releases/latest/download/FAHES_Setup_1.2.0.exe). The installer is not code-signed yet, so Windows SmartScreen may show a warning.

This repository hosts the downloads only. The source code is not published here.
