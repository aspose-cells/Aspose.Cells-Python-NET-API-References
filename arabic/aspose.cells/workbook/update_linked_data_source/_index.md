---
title: طريقة update_linked_data_source
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 440
url: /ar/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
إذا كان هذا المصنف يحتوي على روابط خارجية لمصدر بيانات آخر،
سيحاول Aspose.Cells استرداد أحدث البيانات من المصادر المحددة.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| external_workbooks | list | المصنفات التي سيتم استخدامها لتحديث بيانات الروابط الخارجية التي يشير إليها هذا المصنف.<br/>يتم تحديد تطابق تلك المصنفات مع الروابط الخارجية بواسطة [`Workbook.file_name`](/cells/python-net/ar/aspose.cells/workbook#file_name)<br/>و [`ExternalLink.data_source`](/cells/python-net/ar/aspose.cells/externallink#data_source). لذا يرجى التأكد من أن [`Workbook.file_name`](/cells/python-net/ar/aspose.cells/workbook#file_name) لديه<br/> تم تحديد القيمة الصحيحة لكل مصنف حتى يمكن ربطها بالرابط الخارجي المقابل.|
###  ملاحظات

إذا لم يتم العثور على رابط خارجي مطابق لأحد المصنفات، فسيتم تجاهل هذا المصنف.
لذا عندما تقوم بتعيين صيغة لاحقًا برابط خارجي جديد تنوي جعل المصنف المتجاهل
إذا كنت ترغب في ربطها، فلا يمكن تنفيذ الارتباط إلا عند استدعاء هذه الطريقة مرة أخرى باستخدام تلك المصنفات.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
