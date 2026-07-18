# نشر موقع TapFix على Firebase Hosting (ببلاش)

افتح التيرمينال بمجلد `tapfix-site` ونفّذ:

```bash
firebase deploy --only hosting
```

(تسجيل الدخول موجود، وموقع `tapfix` محجوز جاهز تحت مشروعك — ما في داعي تنشئه.)

بعدها الموقع لايف على: **https://tapfix.web.app**

## تذكير قبل النشر الأول

- عبّي بأول `index.html` (جوا `<script>`) سطرين الـCONFIG: رابط الـApp Store ورقم واتساب الفنيين.
- ✅ أيقونة `icon.png` صارت TapFix (تحدّثت مع الريبراند 2026-07-19).
- لما يكون في إيرادات وتشتري دومين tapfix.co.il — بينربط على نفس الموقع من Firebase Console ‏← Hosting ‏← Add custom domain.
