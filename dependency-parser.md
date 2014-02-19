<div dir=rtl>

یکی از پیش‌نیازهای اصلی برای حل بسیاری از مسائل موجود در حوزه پردازش زبان طبیعی، وجود تحلیل نحوی از جملات زبان است. برای رسیدن به این هدف دو رویکرد متفاوت وجود دارد: 

* [دستور زایشی](http://fa.wikipedia.org/wiki/دستور_زایشی): ابتدا جمله را به دو بخش نهاد و گزاره تقسیم می‌شود و در ادامه به صورت بازگشتی کار تقسیم را تا رسیدن به واژه‌های جمله ادامه می‌دهد.

![درخت تجزیه زایشی](http://upload.wikimedia.org/wikipedia/commons/5/54/Parse_tree_1.jpg)

* [دستور وابستگی](http://fa.wikipedia.org/wiki/دستور_وابستگی): وظیفه تجزیه جمله را از فعل اصلی جمله آغاز می کند و در گام اول وابسته‌های مستقیم فعل و در ادامه به صورت بازگشتی وابسته‌های سطح بعدی را تا تحلیل کامل جمله ادامه می‌دهد.

![درخت تجزیه وابستگی](http://upload.wikimedia.org/wikipedia/commons/8/8c/Parse2.jpg)

تجزیه وابستگی برای تحلیل زبان‌هایی مثل فارسی که ترتیب واژگان در آن‌ها ثابت نیستند بهتر است. یکی از الگوریتم‌های تجزیه وابستگی که بر روی زبان فارسی دقت بالایی دارد و در عین حال پیاده‌سازی آن ساده است الگوریتم [کاوینگتون](http://www.stanford.edu/~mjkay/covington.pdf) است. تلاش‌هایی برای بهبود این الگوریتم نیز صورت گرفته است مثل [+](http://acl.ldc.upenn.edu/eacl2006/main/papers/04_1_nivre_29.pdf) و [+](http://acl.ldc.upenn.edu/D/D07/D07-1125.pdf).

در این پژوهش از شما خواسته شده است که الگوریتم کاوینگتون را پیاده‌سازی کرده و تلاش کنید دقت آن را بر روی زبان فارسی بهبود بخشید.

# مقدمه

# کارهای مرتبط

# آزمایش‌ها

# کارهای آینده

# مراجع
+ [م. خلاش، "بررسی روش‌های تجزیه در دستور وابستگی"، سمینار کارشناسی ارشد ، دانشگاه علم و صعت ایران، 1390.](http://nlp.iust.ac.ir/downloads/articles/A%20Survey%20on%20Dependency%20Parsing.pdf)
+ [م. خلاش، "ساز و کاری برای کشف تأثیر ویژگی‌های مختلف ساخت‌واژی و صرفی بر روی تجزیة وابستگی زبان فارسی"، پایان‌نامه کارشناسی اشد، دانشکده مهندسی کامپیوتر، دانشگاه علم و صنعت، 1391.](http://nlp.iust.ac.ir/downloads/articles/Dependency%20Parsing.pdf)
+ Kubler, S., McDonald, R., & Nivre, J. "Dependency parsing", Synthesis Lectures on Human Language Technologies, Vol. 1, pp. 1–127, 2009.
+ [Khallash, M., Hadian, A., & Minaei-Bidgoli, B. "An Empirical Study on the Effect of Morphological and Lexical Features in Persian Dependency Parsing". In Proceedings of the Fourth Workshop on Statistical Parsing of Morphologically Rich Languages, pp. 97–107, 2013.](http://www.aclweb.org/anthology/W/W13/W13-4912.pd)

# پیوندهای مفید
+ [پردازش زبان فارسی در پایتون](http://www.sobhe.ir/hazm)
+ [پیکره درختی وابستگی فارسی اوپسالا](http://dadegan.ir/catalog/updt)
+ [پیکره وابستگی نحوی زبان فارسی (دادگان)](http://dadegan.ir/catalog/perdt)
+ [سامانه جستجو در دادگان](http://search.dadegan.ir)
+ [پیاده‌سازی الگوریتم کاوینگتون](http://www.ai.uga.edu/mc/pronto/)
