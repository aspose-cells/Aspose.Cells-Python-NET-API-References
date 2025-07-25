---
title: VbaProject صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject صف
يمثل مشروع VBA.



يكشف النوع VbaProject عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_valid_signed](/cells/python-net/ar/aspose.cells.vba/vbaproject/is_valid_signed) | يشير إلى ما إذا كان توقيع مشروع VBA صالحًا أم لا.|
| [cert_raw_data](/cells/python-net/ar/aspose.cells.vba/vbaproject/cert_raw_data) | يحصل على بيانات الشهادة الخام إذا تم توقيع مشروع VBA هذا.|
| [encoding](/cells/python-net/ar/aspose.cells.vba/vbaproject/encoding) |يحصل على ترميز مشروع VBA ويقوم بتعيينه.|
| [name](/cells/python-net/ar/aspose.cells.vba/vbaproject/name) | يحصل على اسم مشروع VBA ويحدده.|
| [is_signed](/cells/python-net/ar/aspose.cells.vba/vbaproject/is_signed) | يشير إلى ما إذا كان VBAcode موقّعًا أم لا.|
| [is_protected](/cells/python-net/ar/aspose.cells.vba/vbaproject/is_protected) | يشير إلى ما إذا كان مشروع VBA هذا محميًا.|
| [islocked_for_viewing](/cells/python-net/ar/aspose.cells.vba/vbaproject/islocked_for_viewing) | يشير إلى ما إذا كان مشروع VBA هذا مقفلاً للعرض.|
| [modules](/cells/python-net/ar/aspose.cells.vba/vbaproject/modules) | يحصل على جميع الكائنات [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule).|
| [references](/cells/python-net/ar/aspose.cells.vba/vbaproject/references) | يحصل على جميع المراجع لمشروع VBA.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/ar/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) | قم بتوقيع مشروع VBA هذا باستخدام DigitalSignature|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/ar/aspose.cells.vba/vbaproject/protect/#bool-str) | يحمي أو يلغي حماية مشروع VBA هذا.|
| [`copy(self, source)`](/cells/python-net/ar/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) | نسخ مشروع VBA من ملف آخر.|
| [`validate_password(self, password)`](/cells/python-net/ar/aspose.cells.vba/vbaproject/validate_password/#str) | التحقق من صحة كلمة مرور الحماية.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.vba`](..)
* فئة [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule)
