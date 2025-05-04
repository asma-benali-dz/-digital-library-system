# -digital-library-system
this is test repo
# digital-library-system
👩‍💻 Student Info:
- **Name**: Asma BEN ALI.
- **Group**: G01.
-  Project Description:
This is a simple digital library management system using Object-Oriented Programming concepts in JAVA.

# نظام إدارة مكتبة رقمية مبسط# نظام إدارة مكتبة رقمية - Java


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

متطلبات التشغيل ⚙️
Java JDK 17+ (تدعم ميزات الـRecords والـPattern Matching)

Git 2.35+ (لإدارة الإصدارات المتقدمة)

MySQL 8.0+ (لتخزين البيانات - اختياري)


خطوات التشغيل ▶️  
# 1. استنساخ المستودع
git clone https://github.com/yourusername/digital-library.git

# 2. التجميع باستخدام Maven
mvn clean install

# 3. تشغيل الواجهة النصية
java -jar target/library-system-1.0.0.jar

# 4. (اختياري) تشغيل الواجهة الرسومية
java -jar target/library-system-1.0.0.jar --gui 

الترخيص 📜
هذا المشروع مرخص تحت MIT License - يُسمح بالتعديل وإعادة الاستخدام لأي غرض.







