# نجوم الملعب — مشروع Android

هذا مجلد مشروع Android Studio يحتوي على غلاف Android أصلي (Java + WebView) يشغّل لعبة `index.html` المضمنة داخل التطبيق. ليس ملف APK بحد ذاته.

## طريقة إنشاء APK على الكمبيوتر
1. ثبّت Android Studio الرسمي.
2. افتح Android Studio واختر **Open** ثم اختر مجلد `Nujoom_AlMalaeb_Android_Project` بعد فك ضغط ZIP.
3. وافق على تثبيت مكونات SDK المطلوبة. إذا طلب Android Studio تنزيل Gradle أو Android Gradle Plugin فاسمح له بذلك.
4. انتظر انتهاء Gradle Sync.
5. اختر **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. عند نجاح البناء اضغط رابط **locate** في الإشعار. عادةً سيكون الملف في:
   `app/build/outputs/apk/debug/app-debug.apk`
7. انقل `app-debug.apk` إلى هاتف Android وافتحه لتثبيته. قد يطلب الهاتف السماح بالتثبيت من هذا المصدر.

## إعدادات
- اسم التطبيق: نجوم الملعب
- Application ID: `com.nujoomalmalaeb.game`
- الاتجاه: أفقي
- الحد الأدنى: Android 6.0 (API 23)
- نسخة التطبيق: 1.0

## ملاحظات صريحة
- لم يُرفق APK جاهز لأن بيئة الإنشاء الحالية لا تحتوي على Android SDK أو Gradle مثبتين، لذلك لا يمكن تأكيد ملف APK مبني ومختبر هنا.
- استخدم Android Studio مع اتصال بالإنترنت في أول بناء لتنزيل أدوات البناء المطلوبة.
- هذه نسخة أولية؛ اختبرها على هاتفك قبل نشرها. لا تستخدم شعارات الأندية أو أسماءها التجارية دون إذن.
