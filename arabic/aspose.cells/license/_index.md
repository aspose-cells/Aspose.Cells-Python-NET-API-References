---
title: License صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 930
url: /ar/aspose.cells/license/
is_root: false
---
##  License صف
توفر طرقًا لترخيص المكون.



يكشف النوع License عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/license/__init__/#) | يقوم بإنشاء مثيل جديد لهذه الفئة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_license(self, license_name)`](/cells/python-net/ar/aspose.cells/license/set_license/#str) | ترخيص المكون.|
| [`set_license(self, stream)`](/cells/python-net/ar/aspose.cells/license/set_license/#io.rawiobase) | ترخيص المكون.|



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

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
