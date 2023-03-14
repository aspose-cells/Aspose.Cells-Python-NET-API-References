---
title: ContentTypeProperty الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.properties/contenttypeproperty/
is_root: false
---
##  ContentTypeProperty الدرجة
يمثل معلومات المعرف.



يكشف نوع ContentTypeProperty الأعضاء التالية:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [name](/cells/python-net/ar/aspose.cells.properties/contenttypeproperty/name) | يرجع أو يحدد اسم الكائن.|
| [value](/cells/python-net/ar/aspose.cells.properties/contenttypeproperty/value) | إرجاع أو تعيين قيمة خاصية نوع المحتوى.|
| [type](/cells/python-net/ar/aspose.cells.properties/contenttypeproperty/type) | يحصل على نوع الملكية ويحددها.|
| [is_nillable](/cells/python-net/ar/aspose.cells.properties/contenttypeproperty/is_nillable) | يشير إلى ما إذا كانت القيمة يمكن أن تكون فارغة.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  أنظر أيضا
* وحدة [aspose.cells.properties](..)
