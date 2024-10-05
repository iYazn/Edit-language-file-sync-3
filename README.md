 <p dir="rtl">ملف اللغة العربية معدل بصيغةxml</p>

 <p dir="rtl"> برنامج QtLinguist </p>
 
 [ملف اللغة العربية معدلfordhmi_ar_SA.zip](https://github.com/user-attachments/files/17267625/fordhmi_ar_SA.zip)

[تحميل QtLinguist-Standalone-5.12.0.zip](https://github.com/lelegard/qtlinguist-installers/releases/download/v5.12.0/QtLinguist-Standalone-5.12.0.zip)
<p dir="rtl"></p>


<p dir="rtl">ترجمة لغةعرض قوائمSYNC 3 واضافة القوائم بعض التطبيقات FMode</p>

 <p dir="rtl">مثل زر الوسائط وشاشة الهدوء والخلفية ورقاقات الثلج</p>

<p dir="rtl">ملف .qm، وهو ملف ترجمة مجمع يستخدم في تطبيقات Qt،</p>


<p dir="rtl">تحتاج عادة إلى اتباع الخطوات التالية:</p>
 <p dir="rtl">ملفات .qm هي ملفات ثنائية تم تجميعها من ملفات .ts (مصدر ترجمة لغوي كيو تي). لتحريرها، تحتاج إلى فك ترجمبها مرة أخرى إلى تنسيق مصدرها، والذي عادة ما يكون قائما على XML.</p>
 
 <p dir="rtl"> يمكنك استخدام أداة تسمى lconvert تأتي مع Qt لفك تشفير ملفات .qm.</p>
 <p dir="rtl">افتح موجة الاوامر وادخل اي مسار البرنامج</p> 

 <p dir="rtl"> <code> cd c:/xxx/xxx/QtLinguist-Standalone </code></p> 


 <p dir="rtl">ضع ملف اللغة المراد تعديلها في نفس المجلد</p>

 <p dir="rtl">يمكنك فك تجميع ملف .qm مثل هذا: </p>

<p dir="rtl">
<code>lconvert -i qt_en.qm -o qt_en.ts</code>
</p>

 <p dir="rtl">سيقوم هذا الأمر بإنشاء ملف .ts (qt_en.ts) من ملف .qm المترجم.</p>


<p dir="rtl"><code>lconvert -i qt_en.qm -o qt_en.XML</code></p>

 <p dir="rtl">سيقوم هذا الأمر بإنشاء ملف .XML (qt_en.XML) من ملف .qm المترجم. </p>

<p dir="rtl">تحرير ملف .ts: بمجرد حصولك على ملف .ts، يمكنك فتحه في محرر نصوص أو أداة ترجمة متخصصة مثل Qt Linguist. يوفر Qt Linguist واجهة سهلة الاستخدام لتحرير الترجمات.</p>
<p dir="rtl">قم بإجراء التغييرات الخاصة بك: في ملف .ts، او xml ستجد النص المصدر الأصلي مع ترجماته. يمكنك تعديل الترجمات لتناسب احتياجاتك.</p>

<p dir="rtl">قم بتجميع ملف .ts مرة أخرى إلى .qm: بمجرد إجراء التغييرات، تحتاج إلى تجميع ملف .ts مرة أخرى إلى ملف .qm حتى يمكن استخدامه بواسطة تطبيق Qt الخاص بك.</p>


 <p dir="rtl">يمكنك تجميع ملف .ts او .xmlمثل هذا</p>
 <p dir="rtl"><code></code>lrelease qt_en.ts</code></p>

  <p dir="rtl">سينشئ هذا الأمر ملف .qm جديد (qt_en.qm) من ملف .ts المعدل.</p>
  
 <p dir="rtl">او عكس امر اتحويل السابق </p>
 <p dir="rtl"><code>lconvert -i qt_en.XML -o qt_en.qm</code></p>
 
 <p dir="rtl">سينشئ هذا الأمر ملف .qm جديد (qt_en.qm) من ملف .XML المعدل.</p>


<p dir="rtl">استبدل الملف .qm الأصلي: أخيرا، استبدل الملف qt_en.qm الأصلي بالملف الذي تم تجميعه حديثا. تأكد من الاحتفاظ بنسخة احتياطية من الملف الأصلي في حال احتجت إلى إعادة تغييراتك.</p>

<p dir="rtl">باتباع هذه الخطوات، يجب أن تكون قادرا على تحرير الترجمات في ملف .qm الخاص بك بشكل فعال.</p>

<p dir="rtl"></p>



<img width="1440" alt="0" src="https://github.com/user-attachments/assets/fb57efc1-a1f5-42fb-953f-a7a4bc83f585">

<img width="1440" alt="1" src="https://github.com/user-attachments/assets/b2cd70f8-8a1d-4af0-bacb-489a810877ee">

<img width="1440" alt="2" src="https://github.com/user-attachments/assets/3a715a8c-3026-4b6d-8fa3-dc6912039d3f">

<img width="1006" alt="3" src="https://github.com/user-attachments/assets/ea0f7e14-01c8-449f-a19f-c5889b165ec0">

<img width="1440" alt="4" src="https://github.com/user-attachments/assets/2b4afccd-8727-41f1-9fd6-3e1b96000a21">
<img width="1440" alt="5" src="https://github.com/user-attachments/assets/4f21e178-4c96-4bc8-b5c0-02605597f0a4">

<img width="1440" alt="6" src="https://github.com/user-attachments/assets/241711b8-06d3-4b2d-9fa5-741db5dfc6fe">

<img width="1440" alt="7" src="https://github.com/user-attachments/assets/7a299d1c-072d-4507-b81f-307e76b44acd">

