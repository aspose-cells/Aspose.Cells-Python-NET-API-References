---
title: طريقة set_license
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/license/set_license/
is_root: false
---
##  set_license(self, license_name) {#str}
ترخيص المكون.



```python

def set_license(self, license_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| license_name | str |  |
###  ملاحظات

يحاول العثور على الترخيص في المواقع التالية:


1. المسار الصريح.


2. المجلد الذي يحتوي على مجموعة المكونات Aspose.


3. المجلد الذي يحتوي على مجموعة استدعاء العميل.


4. المجلد الذي يحتوي على تجميع الإدخالات (بدء التشغيل).


5. مورد مضمن في تجميع الاستدعاء الخاص بالعميل.


**ملحوظة:**في الإطار المضغوط .NET، حاول العثور على الترخيص فقط في هذه المواقع:


1. المسار الصريح.


2. مورد مضمن في تجميع الاستدعاء الخاص بالعميل.
###  مثال


في هذا المثال، سيتم إجراء محاولة للعثور على ملف ترخيص يسمى MyLicense.lic
 في المجلد الذي يحتوي على


المكون، في المجلد الذي يحتوي على التجميع المستدعي،
في مجلد تجميع الإدخالات ثم في الموارد المضمنة لتجميع الاستدعاء.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```
يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمن.
استخدم سلسلة فارغة للتبديل إلى وضع التقييم.


##  set_license(self, stream) {#io.RawIOBase}
ترخيص المكون.



```python

def set_license(self, stream):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase |دفق يحتوي على الترخيص.|
###  ملاحظات

استخدم هذه الطريقة لتحميل ترخيص من الدفق.
###  مثال


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`License`](/cells/python-net/ar/aspose.cells/license)
