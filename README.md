# چگونه با هوش مصنوعی حرفه‌ای کار کنیم؟

وب‌سایت آموزشی استاتیک و فارسی (RTL) دربارهٔ مهندسی پرامپت، ساخته‌شده برای نمایش هنگام ضبط ویدئوی آموزشی.
مدرس: دکتر مهدی باقری‌زاده

## امکانات
- هشت فصل آموزشی با مثال‌های مرتبط با دستیار ارزیابی ایده‌های استارتاپی
- بلوک‌های پرامپت با دکمهٔ کپی
- فهرست فصل‌ها، نوار پیشرفت و حالت تمام‌صفحه
- بدون پایگاه داده، API و سرویس خارجی (فقط فونت Vazirmatn از Google Fonts؛ در نبود آن Tahoma نمایش داده می‌شود)

## پیش‌نیازها
فقط یک مرورگر. برای اجرای محلی اختیاری: Node.js نسخهٔ ۱۸ یا بالاتر.

## نصب و اجرای محلی
```bash
git clone https://github.com/YOUR-USERNAME/kasbsara-prompt-course.git
cd kasbsara-prompt-course
npm start
```
یا فایل `index.html` را مستقیم در مرورگر باز کنید.

## Build
```bash
npm run build
```
این دستور `index.html` را در پوشهٔ `public/` کپی می‌کند (خروجی قابل انتشار). پوشهٔ `public/` در Git ثبت نمی‌شود و در هر Build ساخته می‌شود.

## انتشار روی Vercel
مخزن را در Vercel وارد کنید (Framework Preset: Other). Build Command: `npm run build` و Output Directory: `public` (این مقادیر در `vercel.json` هم تنظیم شده‌اند).

## لینک‌ها
- وب‌سایت: https://www.kasbsara.com
- یوتیوب: https://www.youtube.com/@Dr.Bagherizadeh-AI
- تلگرام کسب‌سرا: https://t.me/kasbsaracom
