---
title: Bash ssh
localeTitle:  باش - بروتوكول النقل الآمن ssh
---

بروتوكول النقل الآمن

## ايعاز الباش للـ: ssh

**يستخدم هذا الايعاز للاتصال بالحاسوب عن بعد.**

مثال:

`ssh 123.456.789.12`

 في المثال اعلاه سيحاول الحاسوب الاتصال عن بعد بأستخدام عنوان الاي بي 123.456.789.12  للحاسوب الاخر، او  عن طريق اسم النطاق "الدومين".

اذا تطلب الحاسوب الذي نحاول الاتصال به عن بعد اسم المستخدم، بامكنانا استخدم الايعاز بهذا الشكل:


`ssh username@remote_address`

 والذي بالتالي سيطلب كلمة السر اذا نجح الاتصال.


### للمزيد من المعلومات:
* [ويكيبيديا](https://ar.wikipedia.org/wiki/%D8%A8%D8%B1%D9%88%D8%AA%D9%88%D9%83%D9%88%D9%84_%D8%A7%D9%84%D9%86%D9%82%D9%84_%D8%A7%D9%84%D8%A2%D9%85%D9%86)