# لومن — Lumen Store

فروشگاه مفهومی فارسی آثار دیجیتال با سبد خرید محلی و دادهٔ نمونه؛ بدون پرداخت یا سفارش واقعی.

این نمونه‌کار توسط **محمد متین خوارزمی** طراحی و توسعه یافته و یک **پروژهٔ مفهومی** است. نام برند، داده‌ها و محصولات برای نمایش رابط استفاده شده‌اند و این مخزن ادعای همکاری با مشتری واقعی یا نتیجهٔ تجاری ندارد.

## امکانات

- ویترین آثار دیجیتال مفهومی
- افزودن، کم‌کردن و حذف از سبد نمونه
- پنجرهٔ سبد با مدیریت تمرکز صفحه‌کلید

## اجرای محلی

Node.js نسخهٔ ۲۰ یا بالاتر کافی است. وابستگی npm لازم نیست.

```sh
npm start
```

سایت در `http://127.0.0.1:8000` در دسترس است. برای پورت دیگر، متغیر محیطی `PORT` را تنظیم کنید. جایگزین با Python: `python -m http.server 8000 --bind 127.0.0.1`.

## ساختار

- `index.html`: صفحهٔ مستقل فارسی و RTL
- `css/demo.css`: سبک‌های رابط و واکنش‌گرایی
- `assets/`: فونت و دارایی‌های محلی مورد نیاز
- `scripts/serve.mjs`: سرور توسعه با Node.js، بدون وابستگی خارجی

فایل‌ها استاتیک‌اند و برای GitHub Pages به مرحلهٔ build نیاز ندارند. تنظیم انتشار باید پس از ایجاد مخزن واقعی انجام شود.

## منشأ و حقوق

این نسخه از [demos/lumen.html](https://matinmt3.github.io/matin-kharazmi-portfolio/demos/lumen.html) در [پورتفولیوی اصلی](https://github.com/matinmt3/matin-kharazmi-portfolio) جدا شده است. فایل‌های اصلی پورتفولیو تغییر نکرده‌اند. مسیر دارایی‌ها برای اجرای مستقل اصلاح شده و پیوند بازگشت به پورتفولیوی اصلی حفظ شده است.

حقوق کد و محتوای اختصاصی طبق [LICENSE](LICENSE) محفوظ است. فونت Vazirmatn تابع مجوز OFL است؛ [مجوزهای اجزای ثالث](docs/THIRD_PARTY.md) همراه پروژه قرار دارند.

## English

A Persian, RTL conceptual portfolio project by Mohammad Matin Kharazmi. This is an interface demonstration, not a real client commission or a production business service. Run with `npm start`; no package installation or external runtime CDN is required.
