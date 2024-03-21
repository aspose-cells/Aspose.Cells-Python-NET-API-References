---
title: طريقة update_linked_data_source
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 420
url: /ar/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source {#list}
إذا كان هذا المصنف يحتوي على ارتباطات خارجية بمصدر بيانات آخر،
سيحاول Aspose.Cells استرداد أحدث البيانات من مصادر العطاء.



```python
def update_linked_data_source(self, external_workbooks):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| external_workbooks | list | المصنفات التي سيتم استخدامها لتحديث بيانات الارتباطات الخارجية المشار إليها بواسطة هذا المصنف.<br/>يتم تحديد مطابقة تلك المصنفات مع الروابط الخارجية بواسطة [`Workbook.file_name`](/cells/python-net/ar/aspose.cells/workbook#file_name)<br/>و [`ExternalLink.data_source`](/cells/python-net/ar/aspose.cells/externallink#data_source). لذا يرجى التأكد من وجود [`Workbook.file_name`](/cells/python-net/ar/aspose.cells/workbook#file_name)<br/> تم تحديدها بالقيمة المناسبة لكل مصنف بحيث يمكن ربطها بالارتباط الخارجي المقابل.|
###  ملاحظات

إذا تعذر العثور على الرابط الخارجي المقابل لمصنف واحد، فسيتم تجاهل هذا المصنف.
لذلك عندما تقوم بتعيين صيغة لاحقًا باستخدام رابط خارجي جديد تنوي إنشاء المصنف الذي تم تجاهله
سيتم ربطه به، فلا يمكن تنفيذ الارتباط حتى تستدعي هذه الطريقة مرة أخرى مع تلك المصنفات.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
