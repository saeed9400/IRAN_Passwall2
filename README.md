<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>Easy-IRAN-Passwall</title>
<style>
    body {
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.7;
        margin: 20px;
        background-color: #f8f9fa;
        color: #333;
    }
    h1, h2, h3 {
        color: #2c3e50;
    }
    h1 { font-size: 2em; margin-bottom: 10px; }
    h2 { font-size: 1.6em; margin-top: 20px; }
    h3 { font-size: 1.3em; margin-top: 15px; }
    p { margin: 8px 0; }
    strong { font-weight: bold; }
    .container {
        display: flex;
        flex-direction: column;
        gap: 40px;
    }
    .section {
        padding: 25px;
        background-color: #fff;
        border-radius: 8px;
        box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }
    .rtl { direction: rtl; font-family: "Tahoma", Arial, sans-serif; }
    .ltr { direction: ltr; }
    code { background-color: #f1f1f1; padding: 2px 6px; border-radius: 4px; }
    .code-container {
        position: relative;
        background: #f4f4f4;
        border: 1px solid #ccc;
        border-radius: 6px;
        padding: 15px;
        font-family: monospace;
        margin: 15px 0;
        overflow-x: auto;
    }
    .copy-btn {
        position: absolute;
        top: 10px;
        right: 10px;
        background: #0077ff;
        color: #fff;
        border: none;
        padding: 5px 12px;
        border-radius: 4px;
        cursor: pointer;
    }
    .copy-btn:hover {
        background: #005fcc;
    }
    pre {
        margin: 0;
        white-space: pre-wrap;
    }
</style>
</head>
<body>

<div class="container">

<!-- ======================== بخش فارسی ======================== -->
<div class="section rtl">
    <h1>🚀 Easy-IRAN-Passwall</h1>

    <h2>● توضیحات:</h2>
    <p>این اسکریپت <strong>PassWall2 را به راحتی و کامل روی OpenWrt نصب می‌کند </strong> </p> 
    <p>با تفکیک ترافیک، <strong> سایت های داخلی ایران را بدون پروکسی باز کنید </strong> </p> 
    <p>در صفحه تنظیمات PassWall، وضعیت تفکیک، دسترسی به اینترنت و عبور از فیلترینگ قابل بررسی است.</p>

    <h3>● ویژگی‌ها:</h3>
    <ul>
        <li>نصب پکیج PassWall2 تنها از منابع رسمی</li>
        <li>نصب پکیج تفکیک ترافیک از منابع معتبر</li>
        <li>پایگاه داده کامل GeoIP / Geosite برای ایران</li>
        <li>تنظیم منطقه زمانی تهران و DNS عمومی</li>
        <li>ایجاد قواعد هوشمند برای ترافیک ایران و سرویس‌های جهانی</li>
        <li>ساخت نودهای Shunt برای مدیریت ترافیک توسط کاربر</li>
        <li>بنر اختصاصی مناسب کاربران ایرانی PassWall2</li>
    </ul>

    <h3>● پیش‌نیازها:</h3>
    <ul>
        <li>روتر با OpenWrt نصب شده</li>
        <li>اینترنت فعال</li>
        <li>دسترسی SSH با سطح root</li>
    </ul>

    <h3>● نصب سریع</h3>
   <ul>
    <li>وارد ترمینال SSH شوید: <code>ssh root@192.168.1.1</code></li>
    <p>بروی دکمه <strong>Copy</strong> کلیک کنید و سپس در ترمینال پیست و اجرا کنید:</p>
```bash
        <li><code>rm -f Passwall-IR.sh && wget https://raw.githubusercontent.com/saeed9400/Easy-IRAN-Passwall/main/Passwall-IR.sh && chmod +x Passwall-IR.sh && sh Passwall-IR.sh</code></li>
    </ul>
<br>
    <h3>● مراحل نصب بصورت جزییات:</h3>
    <ul>
        <li>در ویندوز، Command Prompt را باز کرده و دستور پایین را تایپ کنید.</li>
```bash
        <li><code>ssh root@192.168.1.1</code></li>
        <li>در صورت استفاده از IP متفاوت، آن را جایگزین 192.168.1.1 کنید.</li>
        <li>وارد ترمینال SSH خواهید شد ، خط فرمان به OpenWrt تغییر خواهد کرد</li>
        <li>در صورتی که دیوایس شما رمز دارد ، آنرا تایپ کنید</li>
        <li>هنگام وارد کردن رمز، کاراکترها نمایش داده نمی‌شوند.</li>
        <li>با فرمان پایین اسکریپت را دانلود کنید: </li>
```bash
        <li><code>wget https://raw.githubusercontent.com/saeed9400/Easy-IRAN-Passwall/main/Passwall-IR.sh -O Passwall-IR.sh</code></li>
        <li>با این فرمان اسکریپت را اجرا کنید: </li>
```bash
        <li><code>chmod +x Passwall-IR.sh && ./Passwall-IR.sh</code></li>
    </ul>

    <h3>● نکات مهم:</h3>
    <ul>
        <li>اینترنت روتر باید فعال باشد.</li>
        <li>پشتیبان‌گیری از تنظیمات قبلی توصیه می‌شود.</li>
        <li>استفاده شخصی و غیرتجاری آزاد است.</li>
    </ul>

    <p>🔗 <a href="https://github.com/saeed9400/Easy-IRAN-Passwall" target="_blank">مخزن گیت‌هاب</a></p>
</div>
