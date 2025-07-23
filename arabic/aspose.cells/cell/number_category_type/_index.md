---
title: number_category_type عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 700
url: /ar/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type عقار

يمثل نوع الفئة لتنسيق الأرقام في هذه الخلية.

###  ملاحظات

عندما يتم دمج نمط تنسيق الخلية مع أنماط التنسيق الشرطي،
ثم يكون النوع المرتجع مطابقًا للجزء المستخدم للقيمة الحالية لهذه الخلية.
على سبيل المثال، إذا كان نمط التنسيق لهذه الخلية هو "#,##0;(#,##0);"-";@",
ثم عندما تكون قيمة الخلية رقمية وليست 0، يكون النوع المرتجع هو [`NumberCategoryType.NUMBER`](/cells/python-net/ar/aspose.cells/numbercategorytype#NUMBER)؛
عندما تكون قيمة الخلية 0 أو ليست قيمة رقمية، يكون النوع المرتجع هو [`NumberCategoryType.TEXT`](/cells/python-net/ar/aspose.cells/numbercategorytype#TEXT).
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
