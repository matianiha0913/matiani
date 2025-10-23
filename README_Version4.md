```markdown
# پروژهٔ فرم سفارش مبلمان

فایل index.html شامل یک فرم کامل برای ثبت سفارش مبلمان و تولید برگه‌های خروجی برای:
- رنگ چوب
- خیاطی
- نجاری
- روی‌کوبی
- برگهٔ تحویل

قابلیت‌های افزوده شده:
- اعتبارسنجی ساده (required) برای نام مشتری و شماره سفارش
- ذخیرهٔ خودکار به localStorage هر 4 ثانیه
- امکان ذخیرهٔ سفارش به فایل JSON و بارگذاری آن
- چاپ‌دوست (تنها خروجی هنگام چاپ نمایش داده می‌شود)
- دکمه‌های خروجی برای بخش‌های مختلف و چاپ

نحوهٔ استفاده محلی:
1. یک پوشه بساز و فایل `index.html` را در آن قرار بده.
2. در مرورگر فایل را باز کن یا با یک سرور ساده (مثلاً VSCode Live Server) اجرا کن.

نحوهٔ قرار دادن در GitHub:
1. اگر می‌خواهی با گیت در ترمینال انجام بدی:
   ```
   git init
   git add index.html README.md .gitignore
   git commit -m "Initial commit: add order form"
   git branch -M main
   git remote add origin https://github.com/matianiha0913/matiani.git
   git push -u origin main
   ```

2. یا از طریق رابط وب گیت‌هاب:
   - وارد صفحهٔ ریپو شو → Add file → Upload files → فایل‌ها را بکش و رها کن → Commit changes.

فعال کردن GitHub Pages (برای در دسترس عمومی گذاشتن فرم):
- به Settings → Pages برو، Branch = main و پوشه = / (root) را انتخاب کن، سپس Save.
- پس از چند دقیقه آدرس مشابه `https://matianiha0913.github.io/matiani/` فعال خواهد شد و می‌تونی لینک را به دوستان بدهی.

پیشنهادهای بعدی (در صورت تمایل من آماده‌سازی می‌کنم):
- اضافه کردن export PDF برای برگه‌ها (serverless یا کتابخانهٔ JS)
- فرم multi-user با ذخیره در سرور (API + DB)
- اضافه کردن زبان انگلیسی و ترجمهٔ خودکار
```