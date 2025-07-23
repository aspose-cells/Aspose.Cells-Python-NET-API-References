---
title: built_in_document_properties عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 280
url: /ar/aspose.cells/worksheetcollection/built_in_document_properties/
is_root: false
---
##  built_in_document_properties عقار

إرجاع مجموعة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty) التي تمثل كافة خصائص المستند المضمنة في جدول البيانات.

###  ملاحظات

لا يمكن إضافة خاصية جديدة إلى قائمة خصائص المستند المُدمجة. يمكنك فقط الحصول على خاصية مُدمجة وتغيير قيمتها.
فيما يلي قائمة أسماء الخصائص المضمنة:

عنوان


موضوع


مؤلف


الكلمات الرئيسية


تعليقات


نموذج


المؤلف الأخير


رقم المراجعة


اسم التطبيق


تاريخ آخر طباعة


تاريخ الإنشاء


آخر وقت للحفظ


إجمالي وقت التحرير


عدد الصفحات


عدد الكلمات


عدد الأحرف


حماية


فئة


شكل


مدير


شركة


عدد البايتات


عدد الخطوط


عدد الفقرات


عدد الشرائح


عدد الأوراق النقدية


عدد الشرائح المخفية


عدد مقاطع الوسائط المتعددة

###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.worksheets.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  تعريف:
```python
@property
def built_in_document_properties(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`BuiltInDocumentPropertyCollection`](/cells/python-net/ar/aspose.cells.properties/builtindocumentpropertycollection)
* فئة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty)
* فئة [`WorksheetCollection`](/cells/python-net/ar/aspose.cells/worksheetcollection)
