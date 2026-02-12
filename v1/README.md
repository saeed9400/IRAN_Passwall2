<div dir="rtl">

<p align="center">
  <a href="https://saeed9400.github.io/IRAN_Passwall2/v1">
    <strong>► برای رفتن به صفحه اطلاعات این پروژه کلیک کنید ◄</strong>
    <br><br>
    <img src="https://raw.githubusercontent.com/saeed9400/IRAN_Passwall2/main/v1/img/iran_passwall2_v1.png"
         alt="IRAN Passwall2 Web Installation Guide"
         width="70%">
  </a>
</p>

---

## ● توضیحات

- این اسکریپت پکیج PassWall2 را به‌صورت خودکار روی OpenWrt نصب می‌کند.
- با تفکیک ترافیک، سایت‌های داخلی ایران بدون قطع پروکسی در دسترس خواهند بود.
- امکان بررسی وضعیت اینترنت، فیلترینگ و Shunt به‌صورت لحظه‌ای وجود دارد.
- نصب همیشه از ریپازیتوری رسمی و آخرین نسخه انجام می‌شود.

---

## ● ویژگی‌ها

- نصب PassWall2 فقط از منابع رسمی
- تفکیک ترافیک ایران / جهانی
- پایگاه داده GeoIP و GeoSite ایران
- تنظیم خودکار Timezone تهران و DNS
- نودهای Shunt قابل مدیریت توسط کاربر
- بنر اختصاصی کاربران ایرانی

---

## ● پیش‌نیازها

- روتر با OpenWrt
- اینترنت فعال
- دسترسی SSH با سطح root

---

## ● نصب سریع

1. اتصال به روتر:
```
    ssh root@192.168.1.1
````


2. دانلود و اجرای اسکریپت:
```
    rm -f Passwall-IR.sh
    wget https://raw.githubusercontent.com/saeed9400/IRAN_Passwall2/main/v1/Passwall-IR.sh
    chmod +x Passwall-IR.sh
    sh Passwall-IR.sh
````
    

---

## ● نصب دستی

1. اتصال به روتر:
```
    ssh root@192.168.1.1
````


2. دانلود اسکریپت:
```
    wget https://raw.githubusercontent.com/saeed9400/IRAN_Passwall2/main/v1/Passwall-IR.sh
````
    

3. اجرای اسکریپت:
```
    chmod +x Passwall-IR.sh
    ./Passwall-IR.sh
````

---

## ● نکات مهم

- اینترنت روتر باید فعال باشد
- قبل از نصب، بکاپ از تنظیمات توصیه می‌شود
- استفاده فقط شخصی و غیرتجاری مجاز است

</div>
