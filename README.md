# 📺 CastDZ — اعرض شاشتك بلمسة واحدة
> **Cast your screen with one touch**

## ⬇️ تحميل التطبيق (APK)
👉 **[اضغط هنا لتحميل CastDZ-v1.0.0-debug.apk مباشرة](https://github.com/takieddinexx4-cmyk/DZCAST-android/releases/latest/download/CastDZ-v1.0.0-debug.apk)**

## 📋 البطاقة التقنية للتطبيق (مستخرجة تلقائياً)
| الخاصية | القيمة |
|---|---|
| **اسم التطبيق** | CastDZ |
| **المعرّف (Package ID)** | `com.castdz.app` |
| **الإصدار** | `v1.0.0` (Build `1`) |
| **أنظمة أندرويد المدعومة** | Android 8.0+ (`minSdk 26` → `targetSdk 36` / `compileSdk 36`) |
| **اللغات المدعومة** | ar, en, fr (مع دعم كامل لاتجاه RTL) |
| **بنية المشروع** | 52 ملف Kotlin + 3 ملفات اختبارات وحدات |

## ✨ شرح مختصر لمزايا التطبيق
- **اكتشاف فوري للشاشات (4 طبقات بالتوازي):** Google Cast و mDNS و SSDP/UPnP (DLNA و Roku) بالإضافة للإدخال اليدوي عبر IP، مع تشخيص تلقائي للأعطال بعد 8 ثوانٍ ووضع أجهزة وهمية للتجربة.
- **متصفح فيديوهات الويب:** تبويبات متعددة، إشارات مرجعية، واكتشاف تلقائي لروابط الفيديو (`.mp4`, `.m3u8`, `.mpd`, `.webm`) مع زر عائم للبث الفوري.
- **بث الوسائط المحلية:** خادم `NanoHTTPD` مدمج يدعم التقديم والترجيع (`HTTP Range 206`) ومعاينة محلية عبر Media3 ExoPlayer.
- **تحكم كامل وعكس الشاشة:** مشغل مصغّر وموسّع، تحكم من شاشة القفل، وفتح مباشر للوحة العرض اللاسلكي في أندرويد.
- **واجهة زجاجية بدون إعلانات:** Material 3 Glassmorphism وأيقونات ثلاثية الأبعاد ورسوم Lottie متحركة.

## 🔐 الأذونات المستخدمة
`ACCESS_FINE_LOCATION, ACCESS_NETWORK_STATE, ACCESS_WIFI_STATE, CHANGE_WIFI_MULTICAST_STATE, FOREGROUND_SERVICE, FOREGROUND_SERVICE_MEDIA_PLAYBACK, INTERNET, NEARBY_WIFI_DEVICES, POST_NOTIFICATIONS, READ_EXTERNAL_STORAGE, READ_MEDIA_AUDIO, READ_MEDIA_IMAGES, READ_MEDIA_VIDEO, WAKE_LOCK`