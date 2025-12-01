# Easy-IRAN-Passwall

اسکریپتی ساده و کامل برای نصب PassWall2 روی OpenWrt با تمرکز ویژه روی کاربران ایرانی

---

## ● توضیحات:
این اسکریپت **PassWall2 را به راحتی و کامل روی OpenWrt نصب می‌کند**  
با تفکیک ترافیک، **سایت های داخلی ایران را بدون پروکسی باز کنید**  
در صفحه تنظیمات PassWall، وضعیت تفکیک، دسترسی به اینترنت و عبور از فیلترینگ قابل بررسی است.

## ● ویژگی‌ها:
- نصب پکیج PassWall2 تنها از منابع رسمی
- نصب پکیج تفکیک ترافیک از منابع معتبر
- پایگاه داده کامل GeoIP / GeoSite برای ایران
- تنظیم منطقه زمانی تهران و DNS عمومی
- ایجاد قواعد هوشمند برای ترافیک ایران و سرویس‌های جهانی
- ساخت نودهای Shunt برای مدیریت ترافیک توسط کاربر
- بنر اختصاصی مناسب کاربران ایرانی PassWall2

## ● پیش‌نیازها:
- روتر با OpenWrt نصب شده
- اینترنت فعال
- دسترسی SSH با سطح root

## ● نصب سریع (توصیه شده)

```bash
rm -f Passwall-IR.sh && wget https://raw.githubusercontent.com/saeed9400/Easy-IRAN-Passwall/main/Passwall-IR.sh && chmod +x Passwall-IR.sh && sh Passwall-IR.sh
● مراحل نصب به صورت جزئیات:

وارد SSH شوید: ssh root@192.168.1.1
دانلود اسکریپت:Bashwget https://raw.githubusercontent.com/saeed9400/Easy-IRAN-Passwall/main/Passwall-IR.sh -O Passwall-IR.sh
اجرا:Bashchmod +x Passwall-IR.sh && ./Passwall-IR.sh

● نکات مهم:

اینترنت روتر حتماً باید فعال باشد
حتماً قبل از اجرا از تنظیمات فعلی بک‌آپ بگیرید
استفاده شخصی و غیرتجاری کاملاً آزاد است
