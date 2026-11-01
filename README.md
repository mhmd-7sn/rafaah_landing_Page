# صفحة هبوط رفاه

صفحة عربية باتجاه RTL بهوية رفاه الجديدة: زمردي #003D27، ذهبي #D8A649، عاجي #FDFCF8. مبنية باستخدام HTML5 وCSS وJavaScript دون إطار عمل أو خطوة بناء.

## الملفات

- `dist/index.html`: المحتوى والهيكل.
- `dist/styles.css`: الهوية والتصميم المتجاوب.
- `dist/script.js`: تبويبات المحفظة والفترات الزمنية ودعم لوحة المفاتيح.
- `dist/assets/`: الشعار والصورة المستخرجة من المرجع المرفق.
- `dist/CNAME`: النطاق المطلوب www.rafaah.ai.
- `dist/.nojekyll`: تقديم الملفات كما هي على GitHub Pages.

جميع أزرار البدء تفتح https://app.rafaah.ai. الأرقام والرسوم توضيحية. خصائص الصفحة مستمدة من الصورة التي زوّد بها صاحب المشروع؛ يلزم أن يطابق توفرها ما يقدمه التطبيق عند إطلاق الصفحة. الخطوط Noto Sans Arabic وEB Garamond تُحمّل من Google Fonts، مع خطوط بديلة إذا تعذّر الاتصال.

## الرفع إلى GitHub Pages

1. أنشئ مستودعًا على GitHub.
2. ارفع **محتويات مجلد dist** إلى جذر المستودع، بما فيها assets وCNAME و.nojekyll؛ لا ترفع مجلد dist وحده إلى الجذر.
3. افتح Settings → Pages، واختر Deploy from a branch، ثم main و/(root).
4. أدخل www.rafaah.ai في Custom domain واحفظه قبل تعديل DNS.
5. في إدارة DNS أضف سجل CNAME بالاسم www والقيمة YOUR-USERNAME.github.io؛ استبدل YOUR-USERNAME باسم حسابك أو مؤسستك على GitHub، دون https ودون اسم المستودع.
6. بعد التحقق من النطاق وتوفر الشهادة، فعّل Enforce HTTPS. قد يستغرق انتشار DNS وتوفر HTTPS حتى 24 ساعة.

لم يتم تغيير سجلات DNS أو رفع الملفات إلى حساب GitHub نيابة عنك. ملف CNAME يجهز النطاق فقط؛ لا يربطه بمفرده. أبقِ سجل app.rafaah.ai الخاص بالتطبيق كما هو.

لتحويل rafaah.ai أيضًا إلى www.rafaah.ai، أضف سجلات A للجذر @ بالقيم الأربع التالية بعد إعداد النطاق في GitHub:

185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

مرجع الإعداد الرسمي: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## التعديل

افتح index.html لتغيير النصوص، وstyles.css لتغيير الهوية. ابحث عن https://app.rafaah.ai لتغيير روابط الدعوة إلى البدء. بيانات العرض التفاعلي موجودة في script.js. لا توجد مفاتيح أو حسابات أو بيانات مستخدمين في الكود.
