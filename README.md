# -digital-library-system
this is test repo
# digital-library-system
👩‍💻 Student Info:
- **Name**: Asma BEN ALI.
- **Group**: G01.
-  Project Description:
This is a simple digital library management system using Object-Oriented Programming concepts in JAVA.

# نظام إدارة مكتبة رقمية مبسط# نظام إدارة مكتبة رقمية - Java


![GitHub](https://img.shields.io/github/license/asma-benali-dz/digital-library-system)

مشروع متكامل لإدارة المكتبات الرقمية مع تطبيق مفاهيم البرمجة الكائنية (OOP) بشكل متقدم.

## الميزات الرئيسية 🚀

- 📚 **إدارة الكتب**
  - إضافة/حذف كتب ورقية وإلكترونية
  - تتبع حالة الكتاب (معار/متاح)
  - تصنيف الكتب حسب النوع
- 👥 **إدارة المستعيرين**
  - تسجيل مستعيرين جدد
  - تتبع تاريخ الإعارة
- 🔄 **عمليات الإعارة**
  - إعارة كتب مع تحديد تواريخ الاسترجاع
  - إشعارات التأخير التلقائية
- 🔍 **نظام بحث متقدم**
  - بحث بالعنوان/المؤلف/ISBN
  - تصفية النتائج حسب النوع
- 📊 **تقارير إحصائية**
  - نسبة الإعارة حسب الفئة
  - الكتب الأكثر طلباً

## المفاهيم المطبقة 🧠

| المفهوم            التطبيق في المشروع 

| **التغليف**         جميع الحقول `private` مع `Getters/Setters`

| **الوراثة**        `EBook` و `PaperBook` يرثان من `Book`  

| **تعدد الأشكال**     تطبيق واجهة `Searchable` لأنواع الكتب 

| **الواجهات**      `Borrowable` لإدارة عمليات الإعارة    

## هيكل المشروع 🗂️


src/
├── main/
│   ├── java/
│   │   ├── library/
│   │   │   ├── models/
│   │   │   │   ├── Book.java
│   │   │   │   ├── EBook.java
│   │   │   │   ├── PaperBook.java
│   │   │   │   ├── Borrower.java
│   │   │   │   ├── BorrowingProcess.java
│   │   │   ├── interfaces/
│   │   │   │   ├── Borrowable.java
│   │   │   ├── services/
│   │   │   │   ├── LibraryService.java
│   │   │   ├── Main.java
├── test/
│   ├── java/
│   │   ├── library/
│   │   │   ├── tests/
docs/
README.md
