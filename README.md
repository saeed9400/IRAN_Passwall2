Easy Iran PassWall – Install PassWall2 on OpenWrt with full Iran traffic routing, smart filtering, GeoIP database, and automatic setup. Fast install script for all OpenWrt devices.
<br>



--------------------------------------------
<img width="1408" height="736" alt="Image" src="https://github.com/user-attachments/assets/ab63ef7a-6342-461f-993e-5736104308e6" />

<br>
<a href="https://github.com/saeed9400/IRAN_Passwall2/blob/main/README_EN.md">► English Description ◄ </a>
<br>
<br>
--------------------------------------------


<br>


## ● توضیحات:


###  ← این اسکریپت پکیچ PassWall2 را به راحتی بروی فریمور OpenWrt نصب میکند. 

###  ← با تفکیک ترافیک، میتوانید سایت‌های داخلی ایران را بدون نیاز به قطع کردن پروکسی (فیلترشکن) استفاده کنید.

###  ←  در صفحه تنظیمات PassWall2، وضعیت لحظه ای تفکیک ترافیک، دسترسی به اینترنت و عبور از فیلترینگ را بررسی است.

###  ←  بعلت استفاده از زیپازتوری رسمی این اسکریپت همیشه آخرین ورژن منتشر شده را دانلود و نصب خواهد کرد.
<br>
<br>

---

<br>

## ● ویژگی‌ها:
- نصب پکیج PassWall2 تنها از منابع رسمی
- نصب پکیج تفکیک ترافیک از منابع معتبر
- پایگاه داده کامل GeoIP / Geosite برای ایران
- تنظیم منطقه زمانی تهران و DNS عمومی
- ایجاد قواعد هوشمند برای ترافیک ایران و سرویس‌های جهانی
- ساخت نودهای Shunt برای مدیریت ترافیک توسط کاربر
- بنر اختصاصی مناسب کاربران ایرانی PassWall2

## ● پیش‌نیازها:
- روتر با OpenWrt نصب شده
- اینترنت فعال
- دسترسی SSH با سطح root
<br>
<br>

---

<br>

# ● نصب سریع
### 1. وارد ترمینال SSH شوید:  
   ```bash
   ssh root@192.168.1.1
   ```

### 2. سپس دستور زیر را برای دانلود و اجرای اسکریپت اجرا کنید:
   ```bash
rm -f Passwall-IR.sh && wget https://raw.githubusercontent.com/saeed9400/IRAN_Passwall2/main/Passwall-IR.sh && chmod +x Passwall-IR.sh && sh Passwall-IR.sh
   ```

<br>
<br>

---

<br>


## ● جزییات نصب برای انجام دستی مراحل:

#### 1. در ویندوز، Command Prompt را باز کرده و دستور پایین را تایپ کنید:
   ```bash
   ssh root@192.168.1.1
   ```

   -- در صورت استفاده از IP متفاوت، آن را جایگزین 192.168.1.1 کنید.

   -- در صورتی که دیوایس شما رمز دارد، آن را تایپ کنید.

   -- هنگام وارد کردن رمز، کاراکترها نمایش داده نمی‌شوند

   -- در صورت درستی فرامین وارد ترمینال SSH خواهید شد و خط فرمان به OpenWrt تغییر خواهد کرد.
.

#### 2. با این فرمان اسکریپت را دانلود کنید:

   ```bash
wget https://raw.githubusercontent.com/saeed9400/IRAN_Passwall2/main/Passwall-IR.sh -O Passwall-IR.sh
   ```

#### 3. با این فرمان اسکریپت را اجرا کنید:

   ```bash
chmod +x Passwall-IR.sh && ./Passwall-IR.sh
   ```

<br>
<br>

---
<br>

## ● نکات مهم:

##### - اینترنت روتر باید فعال باشد .

##### - پشتیبان‌گیری از تنظیمات قبلی توصیه می‌شود.

##### - استفاده شخصی و غیرتجاری آزاد است

<br>
<br>
<br>

---


<br>



  <img width="1024" height="450" alt="Image" src="https://github.com/user-attachments/assets/ace11d99-b142-4964-b890-71204d9cac41" />

<br>


--------------------------------------------

<br>

● Description:

→ This script installs the PassWall2 package easily on devices running the OpenWrt firmware.

→ With traffic separation, you can access Iranian domestic websites without using a proxy.

→ In the PassWall2 settings page, you can check the status of traffic separation, internet access, and censorship bypass.

------------------------------------------------------------------------

● Features:

-   Installs the PassWall2 package only from official sources
-   Installs traffic‑separation packages from trusted repositories
-   Includes complete GeoIP / Geosite databases for Iran
-   Sets Tehran timezone and public DNS
-   Creates smart routing rules for Iranian and global services
-   Builds Shunt nodes for user‑controlled traffic management
-   Includes a custom banner for Iranian PassWall2 users

● Requirements:

-   A router running OpenWrt
-   Active internet connection
-   SSH access with root privileges

------------------------------------------------------------------------

● Quick Installation

1. Open the SSH terminal:

    ssh root@192.168.1.1

2. Download and run the script:

   ```bash
    rm -f Passwall-IR.sh && wget https://raw.githubusercontent.com/saeed9400/IRAN_Passwall2/main/Passwall-IR.sh && chmod +x Passwall-IR.sh && sh Passwall-IR.sh
   ```

------------------------------------------------------------------------

● Manual Installation Steps:

1. On Windows, open Command Prompt and type:

   ```bash
    ssh root@192.168.1.1
   ```

— If your device uses a different IP, replace 192.168.1.1.
— If your device requires a password, enter it.
— Characters will not appear when typing the password.
— If successful, you will enter the SSH terminal and the prompt will
switch to OpenWrt.

2. Download the script:

   ```bash
    wget https://raw.githubusercontent.com/saeed9400/IRAN_Passwall2/main/Passwall-IR.sh -O Passwall-IR.sh
   ```

3. Run the script:

   ```bash
    chmod +x Passwall-IR.sh && ./Passwall-IR.sh
   ```

------------------------------------------------------------------------

● Important Notes:

-   The router must have internet access.
-   Backing up previous configurations is recommended.
-   Free for personal and non-commercial use.

