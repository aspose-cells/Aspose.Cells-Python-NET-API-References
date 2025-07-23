---
title: linked_data_sources عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources عقار

يحدد مصادر البيانات للروابط الخارجية المستخدمة في الصيغ.

###  ملاحظات

مثل [`Workbook.update_linked_data_source`](/cells/python-net/ar/aspose.cells/workbook/update_linked_data_source)، يمكنك هنا تحديد
مصادر البيانات للروابط الخارجية المستخدمة في الصيغ المراد حسابها، وخاصة تلك
تُستخدم في دالة INDIRECT. بالنسبة للروابط الخارجية المستخدمة في دالة INDIRECT،
لا يتم اعتبارها جزءًا من الروابط الخارجية للمصنف ولا يمكن تحديثها
بواسطة [`Workbook.update_linked_data_source`](/cells/python-net/ar/aspose.cells/workbook/update_linked_data_source).
يتم تحديد تطابق تلك المصنفات مع الروابط الخارجية بواسطة [`Workbook.file_name`](/cells/python-net/ar/aspose.cells/workbook#file_name)
و [`ExternalLink.data_source`](/cells/python-net/ar/aspose.cells/externallink#data_source). لذا يرجى التأكد من أن [`Workbook.file_name`](/cells/python-net/ar/aspose.cells/workbook#file_name) لديه
تم تحديدها بالقيمة الصحيحة (بشكل عام يجب أن تكون هي نفسها مع القيمة المقابلة)
[`ExternalLink.data_source`](/cells/python-net/ar/aspose.cells/externallink#data_source)) لكل مصنف حتى يمكن ربطها كما هو متوقع.
###  تعريف:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions)
