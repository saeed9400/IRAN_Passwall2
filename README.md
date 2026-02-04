<br>

<p align="center">
  <a href="https://saeed9400.github.io/IRAN_Passwall2/">
    <strong>► برای رفتن به صفحه اطلاعات این پروژه کلیک کنید ◄</strong>
    <br><br>
    <img src="https://github.com/user-attachments/assets/c92044ae-3565-410d-9a6c-eabf1e2bd694"
         alt="تصویر پروژه"
         style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  </a>
</p>

<br>

---

## توضیحات پروژه

این اسکریپت به صورت خودکار پکیج **PassWall2** را روی فریمور **OpenWrt** نصب می‌کند.

با استفاده از قابلیت تفکیک ترافیک، امکان دسترسی به سایت‌های داخلی ایران بدون نیاز به پروکسی فراهم می‌شود.

در صفحه تنظیمات PassWall2 می‌توانید وضعیت لحظه‌ای تفکیک ترافیک، دسترسی به اینترنت و عملکرد کلی را مشاهده کنید.

اسکریپت همیشه آخرین نسخه منتشرشده را از منابع رسمی دریافت و نصب می‌نماید.

### نسخه‌های موجود

پروژه در حال حاضر دو نسخه اصلی دارد که در پوشه‌های `v1` و `v2` در مخزن گیت‌هاب قرار گرفته‌اند:

- **نسخه v1**  
  پوشه: [v1](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v1)  
  نسخه پایه و استاندارد شامل:

  - نصب از منابع رسمی  
  - تفکیک ترافیک داخلی  
  - تنظیم منطقه زمانی تهران و DNS عمومی  
  - قواعد هوشمند مسیریابی  
  - بنر اختصاصی برای کاربران ایرانی  

- **نسخه v2**  
  پوشه: [v2](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v2)  
  نسخه بهبودیافته با تمرکز بر پایداری در شرایط متنوع اینترنت ایران، شامل:

  - بررسی چندلایه وضعیت اتصال (پینگ + رزولوشن DNS + دسترسی HTTPS)  
  - اولویت نصب مستقیم از ریپازیتوری‌های رسمی  
  - در صورت محدودیت، تلاش برای دانلود از گیت‌هاب  
  - در صورت محدودیت شدیدتر، استفاده از ریپازیتوری جایگزین ایرانی  
  - تنها در صورت قطع کامل اینترنت، نصب امکان‌پذیر نیست  

برای انتخاب نسخه مناسب، به پوشه مورد نظر مراجعه کنید.

---

## ویژگی‌های اصلی

- نصب پکیج PassWall2 صرفاً از منابع رسمی  
- نصب پکیج‌های لازم برای تفکیک ترافیک از منابع معتبر  
- پایگاه داده کامل GeoIP و Geosite ویژه ایران  
- تنظیم خودکار منطقه زمانی تهران و DNS عمومی  
- ایجاد قواعد هوشمند مسیریابی برای ترافیک داخلی و بین‌المللی  
- ساخت نودهای Shunt جهت مدیریت دستی ترافیک توسط کاربر  
- بنر اختصاصی و زیباسازی شده برای کاربران ایرانی PassWall2  

## پیش‌نیازها

- روتر مجهز به فریمور OpenWrt  
- اتصال اینترنت فعال روی روتر  
- دسترسی SSH با سطح کاربری root  

## نکات مهم

- روتر حتماً باید به اینترنت متصل باشد.  
- تهیه نسخه پشتیبان از تنظیمات فعلی قبل از اجرا توصیه می‌شود.  
- این اسکریپت فقط برای استفاده شخصی و غیرتجاری آزاد است.  

<br>

---

<p align="center">
  <a href="https://github.com/saeed9400/IRAN_Passwall2/blob/main/README_EN.md">
    ► English Description ◄
  </a>
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c92044ae-3565-410d-9a6c-eabf1e2bd694"
       alt="Project Image"
       style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</p>

<p align="center">
  <strong>Easy Iran PassWall</strong><br>
  Install PassWall2 on OpenWrt with Iran traffic routing, GeoIP database and automatic setup<br>
  Fast install script compatible with most OpenWrt devices
</p>

<br>

---

### Description

This script automatically installs the **PassWall2** package on **OpenWrt** firmware.

Using traffic separation, it enables access to Iranian domestic websites without requiring a proxy.

The PassWall2 settings page shows real-time traffic separation status, internet connectivity and overall performance.

The script always fetches and installs the latest official release.

### Available Versions

The project currently provides two main versions in folders `v1` and `v2`:

- **Version v1**  
  Folder: [v1](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v1)  
  Standard/base version including:

  - Installation from official sources  
  - Domestic traffic separation  
  - Tehran timezone & public DNS configuration  
  - Smart routing rules  
  - Custom banner for Iranian users  

- **Version v2**  
  Folder: [v2](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v2)  
  Enhanced version with improved resilience under varying Iranian internet conditions, featuring:

  - Multi-layer connectivity check (ping + DNS resolution + HTTPS access)  
  - Priority direct installation from official repositories  
  - Fallback to GitHub downloads when repository access is restricted  
  - Fallback to Iranian mirror repository in more severe restrictions  
  - Installation only impossible when internet is completely unavailable  

Choose the version that best suits your connection conditions.

### Features

- Installs PassWall2 exclusively from official sources  
- Installs required traffic separation packages from trusted sources  
- Complete GeoIP / Geosite database for Iran  
- Automatic Tehran timezone and public DNS setup  
- Intelligent routing rules for domestic and international traffic  
- Shunt nodes for manual traffic management  
- Custom, user-friendly banner for Iranian PassWall2 users  

### Requirements

- Router running OpenWrt firmware  
- Active internet connection on the router  
- SSH root access  

### Important Notes

- The router must be connected to the internet.  
- Backup of current configuration before running is strongly recommended.  
- For personal, non-commercial use only.  
