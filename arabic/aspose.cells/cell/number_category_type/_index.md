---
title: number_category_type عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 670
url: /ar/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type عقار

يمثل نوع الفئة لتنسيق أرقام هذه الخلية.

###  ملاحظات

عندما يتم دمج نمط تنسيق الخلية مع أنماط التنسيق الشرطي،
فإن النوع الذي تم إرجاعه يتوافق مع الجزء المستخدم للقيمة الحالية لهذه الخلية.
على سبيل المثال، إذا كان نمط التنسيق لهذه الخلية هو "#,##0;(#,##0);"-";@"،
ثم عندما تكون قيمة الخلية رقمية وليست 0، يكون النوع الذي تم إرجاعه هو [`NumberCategoryType.NUMBER`](/cells/python-net/ar/aspose.cells/numbercategorytype#NUMBER)؛
عندما تكون قيمة الخلية 0 أو ليست قيمة رقمية، فإن النوع الذي يتم إرجاعه هو [`NumberCategoryType.TEXT`](/cells/python-net/ar/aspose.cells/numbercategorytype#TEXT).
###  تعريف:
```python
@property
def number_category_type(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
* فئة [`NumberCategoryType`](/cells/python-net/ar/aspose.cells/numbercategorytype)
