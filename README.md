# CONAN FILES — GitHub Pages

موقع Fan Site غير رسمي للمحقق كونان، جاهز للنشر مباشرة عبر GitHub Pages.

## النشر

1. أنشئ Repository جديدًا على GitHub.
2. ارفع `index.html` إلى المستودع.
3. افتح:
   **Settings → Pages**
4. تحت **Build and deployment** اختر:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
5. اضغط Save.
6. بعد اكتمال النشر سيظهر رابط الموقع في قسم Pages.

### لماذا هذه النسخة مناسبة لـ GitHub Pages؟
بيانات الشخصيات والأفلام مضمنة داخل `index.html`، لذلك الموقع لا يحتاج PHP أو Node.js أو خادمًا خاصًا، ولا يعتمد على `fetch()` لملفات محلية.

## الملفات
- `index.html` — الموقع الكامل.
- `characters.json` — نسخة قابلة للتحرير من بيانات الشخصيات.
- `movies.json` — بيانات الأفلام.

## ملاحظة الحقوق
هذا مشروع جماهيري غير رسمي. Detective Conan وشخصياته والعلامات المرتبطة به مملوكة لأصحاب الحقوق. لا تُضمّن في المستودع صورًا أو أعمال Fan Art لا تملك حق إعادة نشرها.
