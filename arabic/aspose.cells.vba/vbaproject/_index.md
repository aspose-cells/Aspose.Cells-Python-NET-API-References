---
title: VbaProject الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject الدرجة
يمثل مشروع VBA.



يكشف نوع VbaProject الأعضاء التالية:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_valid_signed](/cells/python-net/ar/aspose.cells.vba/vbaproject/is_valid_signed) | يشير إلى ما إذا كان توقيع مشروع VBA صالحًا أم لا.|
| [cert_raw_data](/cells/python-net/ar/aspose.cells.vba/vbaproject/cert_raw_data) | يحصل على البيانات الأولية للشهادة إذا تم توقيع مشروع VBA.|
| [name](/cells/python-net/ar/aspose.cells.vba/vbaproject/name) | الحصول على اسم مشروع VBA وتعيينه.|
| [is_signed](/cells/python-net/ar/aspose.cells.vba/vbaproject/is_signed) | يشير إلى ما إذا كان VBAcode موقّعًا أم لا.|
| [is_protected](/cells/python-net/ar/aspose.cells.vba/vbaproject/is_protected) | يشير إلى ما إذا كان مشروع VBA محميًا.|
| [islocked_for_viewing](/cells/python-net/ar/aspose.cells.vba/vbaproject/islocked_for_viewing) | يشير إلى ما إذا كان مشروع VBA مغلقًا للعرض أم لا.|
| [modules](/cells/python-net/ar/aspose.cells.vba/vbaproject/modules) | يحصل على جميع [VbaModule](/cells/python-net/ar/aspose.cells.vba/vbamodule) كائنات.|
| [references](/cells/python-net/ar/aspose.cells.vba/vbaproject/references) | يحصل على كافة مراجع مشروع VBA.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [sign(digital_signature)](/cells/python-net/ar/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.DigitalSignature) | قم بتوقيع مشروع VBA هذا بواسطة DigitalSignature|
| [protect(islocked_for_viewing, password)](/cells/python-net/ar/aspose.cells.vba/vbaproject/protect/#bool-str) | يحمي أو يلغي حماية مشروع VBA هذا.|
| [copy(source)](/cells/python-net/ar/aspose.cells.vba/vbaproject/copy/#VbaProject) | انسخ مشروع VBA من ملف آخر.|
| [validate_password(password)](/cells/python-net/ar/aspose.cells.vba/vbaproject/validate_password/#str) | يتحقق من صحة كلمة مرور الحماية.|



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
* وحدة [aspose.cells.vba](..)
* فئة [VbaModule](/cells/python-net/ar/aspose.cells.vba/vbamodule)
