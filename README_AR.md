# تطبيق تقارير
تطبيق Android باسم «تقارير» لإنشاء تقارير منظمة على مقاس A4.
المزايا: البسملة، إلى، الموضوع، نص التقرير، الكاتب، التاريخ، التوقيع، معاينة، وطباعة A4.

## بناء APK
افتح المشروع في Android Studio، ثم اختر:
Build > Generate App Bundles or APKs > Generate APK.
الملف الناتج يكون داخل:
app/build/outputs/apk/


## البناء من الهاتف
هذا المشروع يحتوي على GitHub Actions في `.github/workflows/build.yml`.
بعد رفع محتويات المشروع إلى مستودع GitHub، افتح تبويب Actions وشغّل
`Build Taqareer APK`. عند انتهاء البناء، نزّل Artifact باسم
`Taqareer-debug-apk` وستجد داخله `app-debug.apk`.
