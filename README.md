# یادآور - PWA

## نصب روی آیفون:
1. فایل‌ها را روی یک سرور (حتی localhost) هاست کنید
2. در Safari آیفون آدرس را باز کنید
3. دکمه Share را بزنید
4. "Add to Home Screen" را انتخاب کنید

## ساختار فایل‌ها:
- index.html  : فایل اصلی برنامه
- manifest.json : تنظیمات PWA
- sw.js       : Service Worker (کش آفلاین)
- icon-180.png : آیکون Apple Touch
- icon-192.png : آیکون PWA کوچک
- icon-512.png : آیکون PWA بزرگ

## اجرای محلی:
```
python3 -m http.server 8080
```
سپس در Safari: http://localhost:8080
