````markdown
# Saudi2030x

Saudi2030X — منصة ذكية تربط اللوجستيات، المعدات الثقيلة، الطاقة الشمسية، وتداول الذهب المدعوم بالذكاء الاصطناعي.

هذا المستودع يحتوي على صفحة هبوط (landing page) بسيطة مع دعم للغة العربية والإنجليزية.

## نشر (Deploy)

نوصي باستخدام Netlify لتشغيل النماذج (forms) دون إعداد خادم.
1. سجّل دخولك إلى https://app.netlify.com/
2. اختر "New site from Git" واختر مستودع `abd11011/Saudi2030x`.
3. اترك التكوين الافتراضي (Branch to deploy: `feature/site-improvements` أو `main`) واضغط Deploy site.

### Netlify Forms
تم تهيئة النماذج في `index.html` لاستخدام Netlify (attribute `data-netlify="true"` و `form-name`). بعد النشر، سترى الإدخالات في لوحة Netlify Forms.

## الملفات
- `index.html` — صفحة الهبوط (EN/AR).
- `styles.css` — أنماط الصفحة مفصولة لتسهيل الصيانة.
- `assets/` — يحتوي على `favicon.svg` و `preview.svg` (preview للصورة الاجتماعية).

## ترخيص
مرخّص بموجب رخصة MIT.
````