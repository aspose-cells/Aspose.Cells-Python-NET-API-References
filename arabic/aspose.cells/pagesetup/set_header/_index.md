---
title: طريقة set_header
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 200
url: /ar/aspose.cells/pagesetup/set_header/
is_root: false
---
##  set_header(self, section, header_script) {#int-str}
تعيين نص برمجي لتنسيق رأس ملف Excel.



```python

def set_header(self, section, header_script):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| section | int |0: القسم الأيسر، 1: القسم الأوسط، 2: القسم الأيمن.|
| header_script | str | نص تنسيق الرأس.|
###  ملاحظات

أوامر البرنامج النصي:

| يأمر| وصف|
| :- | :- |
| &ص| رقم الصفحة الحالية|
| &ن| عدد الصفحات|
| &د| التاريخ الحالي|
| &ت| الوقت الحالي|
| &أ| اسم الورقة|
| &ف| اسم الملف بدون مسار|
| &"<FontName>"|اسم الخط، على سبيل المثال: &"Arial"|
| &"<FontName>, <FontStyle>"| اسم الخط ونمط الخط، على سبيل المثال: &"Arial,Bold"|
| &<FontSize>| حجم الخط. إذا تبع هذا الأمر رقمًا عاديًا لطباعته في العنوان، فسيتم فصله عن ارتفاع الخط بمسافة.|
| &ك<RRGGBB>| لون الخط، على سبيل المثال (RED): &KFF0000|
| &ج| نص الصورة|

على سبيل المثال: "&Arial,Bold&8Header Note"


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`PageSetup`](/cells/python-net/ar/aspose.cells/pagesetup)
