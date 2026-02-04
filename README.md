<br>
<a href="https://saeed9400.github.io/IRAN_Passwall2/">► برای رفتن به صفحه اطلاعات این پروژه کلیک کنید ◄
<img width="1408" height="630" alt="Image" src="https://github.com/user-attachments/assets/c92044ae-3565-410d-9a6c-eabf1e2bd694" /> </a>
<br>
<br>
---
## ● توضیحات:
### ← این اسکریپت پکیج **PassWall2** را به راحتی روی فریمور **OpenWrt** نصب می‌کند.
### ← با تفکیک ترافیک، امکان دسترسی به سایت‌های داخلی ایران بدون نیاز به پروکسی فراهم می‌شود.
### ← در صفحه تنظیمات PassWall2، می‌توانید وضعیت لحظه‌ای تفکیک ترافیک، دسترسی به اینترنت و عملکرد کلی را مشاهده کنید.
### ← این اسکریپت همیشه آخرین نسخه منتشرشده را از منابع رسمی دانلود و نصب می‌کند.

### ● نسخه‌ها:
این پروژه اکنون دارای دو نسخه است که در پوشه‌های `v1` و `v2` در گیت‌هاب قرار گرفته‌اند:

- **نسخه v1** (پوشه v1):  
  نسخه اولیه با امکانات استاندارد شامل:  
  - نصب از منابع رسمی  
  - تفکیک ترافیک داخلی  
  - تنظیم منطقه زمانی تهران و DNS عمومی  
  - قواعد هوشمند مسیریابی  
  - بنر اختصاصی برای کاربران ایرانی  

- **نسخه v2** (پوشه v2):  
  نسخه بهبودیافته با تمرکز بر پایداری بیشتر در شرایط مختلف اتصال اینترنت ایران. شامل تغییرات زیر:  
  - بررسی عمیق‌تر وضعیت اتصال اینترنت (چند لایه: پینگ، رزولوشن DNS، دسترسی HTTPS)  
  - تست دسترسی به ریپازیتوری‌های رسمی و نصب مستقیم در صورت امکان  
  - در صورت محدودیت دسترسی، تلاش برای دریافت فایل‌ها از گیت‌هاب  
  - در صورت محدودیت شدیدتر، تلاش برای استفاده از ریپازیتوری جایگزین ایرانی  
  - تنها در صورت عدم دسترسی کامل به اینترنت، نصب امکان‌پذیر نخواهد بود  

برای انتخاب نسخه مناسب، به پوشه مربوطه مراجعه کنید:  
[v1](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v1)  
[v2](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v2)

<br>
<br>
---
<br>
## ● ویژگی‌ها:
- نصب پکیج PassWall2 تنها از منابع رسمی
- نصب پکیج‌های موردنیاز تفکیک ترافیک از منابع معتبر
- پایگاه داده کامل GeoIP / Geosite برای ایران
- تنظیم منطقه زمانی تهران و DNS عمومی
- ایجاد قواعد هوشمند برای ترافیک داخلی و سرویس‌های جهانی
- ساخت نودهای Shunt برای مدیریت ترافیک توسط کاربر
- بنر اختصاصی مناسب کاربران ایرانی PassWall2
## ● پیش‌نیازها:
- روتر با فریمور OpenWrt نصب‌شده
- اتصال اینترنت فعال
- دسترسی SSH با سطح root
<br>
<br>
---
<br>
## ● نکات مهم:
##### - روتر باید به اینترنت متصل باشد.
##### - پشتیبان‌گیری از تنظیمات قبلی توصیه می‌شود.
##### - استفاده شخصی و غیرتجاری آزاد است.
<br>
<br>
<br>
---
<a href="https://github.com/saeed9400/IRAN_Passwall2/blob/main/README_EN.md">► English Description ◄ </a>
<br>
<img width="1408" height="630" alt="Image" src="https://github.com/user-attachments/assets/c92044ae-3565-410d-9a6c-eabf1e2bd694" />
Easy Iran PassWall – Install PassWall2 on OpenWrt with full Iran traffic routing, smart filtering, GeoIP database, and automatic setup. Fast install script for all OpenWrt devices.
<br>
--------------------------------------------
<br>
● Description:
→ This script installs the PassWall2 package easily on devices running the OpenWrt firmware.
→ With traffic separation, Iranian domestic websites can be accessed without proxy.
→ In the PassWall2 settings page, you can monitor real-time traffic separation status, internet access, and overall performance.

### ● Versions:
This project now has two versions, located in the v1 and v2 folders on GitHub:

- **Version v1** (folder v1):  
  Initial version with standard features:  
  - Installation from official sources  
  - Domestic traffic separation  
  - Tehran timezone & public DNS setup  
  - Smart routing rules  
  - Custom banner for Iranian users  

- **Version v2** (folder v2):  
  Improved version with better resilience in varying Iranian internet conditions. Includes:  
  - Deeper internet connectivity checks (multi-layer: ping, DNS, HTTPS)  
  - Testing access to official repositories and direct installation when possible  
  - Fallback to GitHub downloads if repository access is limited  
  - Fallback to Iranian mirror repository in more restricted scenarios  
  - Installation only impossible when there is complete lack of internet connectivity  

To choose the appropriate version, refer to the corresponding folder:  
[v1](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v1)  
[v2](https://github.com/saeed9400/IRAN_Passwall2/tree/main/v2)

------------------------------------------------------------------------
● Features:
- Installs PassWall2 package only from official sources
- Installs required traffic-separation packages from trusted sources
- Includes complete GeoIP / Geosite databases for Iran
- Sets Tehran timezone and public DNS
- Creates smart routing rules for domestic and global services
- Builds Shunt nodes for user-controlled traffic management
- Includes custom banner for Iranian PassWall2 users
● Requirements:
- Router running OpenWrt firmware
- Active internet connection
- SSH access with root privileges
------------------------------------------------------------------------
● Important Notes:
- The router must have internet access.
- Backing up previous configurations is recommended.
- Free for personal and non-commercial use.
