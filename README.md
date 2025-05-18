# Online-phone-book
# 📞 دفترچه تلفن آنلاین

یک پروژه کامل و مدرن دفترچه تلفن تحت وب با قابلیت‌های مدیریت مخاطبین، جستجوی زنده (AJAX)، طراحی ریسپانسیو با Tailwind CSS، انیمیشن‌های جذاب با Animate.css و برنامه‌نویسی سمت سرور با PHP و پایگاه داده MySQL.

---

## 🚀 ویژگی‌ها

- افزودن، ویرایش، حذف و نمایش مخاطبین
- جستجوی زنده با AJAX و نمایش لحظه‌ای نتایج
- طراحی مدرن و واکنش‌گرا با استفاده از Tailwind CSS
- انیمیشن‌های زیبا برای المان‌ها با Animate.css
- اعتبارسنجی فرم‌ها در سمت کلاینت (JS) و سرور (PHP)
- استفاده از PDO برای جلوگیری از SQL Injection
- ساختار ماژولار و قابل توسعه

---

## 🧱 ساختار پروژه

/phonebook-app/
│
├── index.php ← صفحه اصلی (لیست مخاطبین + جستجو)
├── contact.php ← فرم افزودن/ویرایش مخاطب
│
├── api/
│ ├── add_contact.php ← API افزودن مخاطب
│ ├── edit_contact.php ← API ویرایش مخاطب
│ ├── delete_contact.php ← API حذف مخاطب
│ └── search.php ← API جستجوی لحظه‌ای
│
├── includes/
│ ├── db.php ← اتصال امن به MySQL با PDO
│ └── functions.php ← توابع کمکی پروژه
│
├── assets/
│ ├── css/
│ │ └── style.css ← استایل اختصاصی
│ ├── js/
│ │ ├── main.js ← منطق کلاینت + AJAX
│ │ └── animate.js ← انیمیشن‌های سفارشی
│ └── img/ ← تصاویر موردنیاز
│
├── sql/
│ └── database.sql ← اسکریپت ایجاد جدول مخاطبین
│
└── README.md ← مستندات پروژه

🛠️ پیش‌نیازها
PHP >= 7.4

MySQL

مرورگر مدرن (Chrome, Firefox, etc.)
کل پروژه را در پوشه htdocs یا روت سرور خود کپی کنید.

فایل sql/database.sql را در دیتابیس MySQL خود ایمپورت کنید.

اطلاعات اتصال دیتابیس را در includes/db.php تنظیم کنید.

پروژه را در مرورگر اجرا کنید:
http://localhost/phonebook-app/

![image](https://github.com/user-attachments/assets/4d0062e1-15cf-4713-a4e7-346ee4c6aa0f)
![image](https://github.com/user-attachments/assets/f33ac160-89c5-43c8-8033-de436e791b81)
![image](https://github.com/user-attachments/assets/9bd0d97a-a5d0-4d56-a7c4-5b4677eafc74)


