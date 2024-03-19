---
title: طريقة index_of
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells.vba/vbamodulecollection/index_of/
is_root: false
---
##  index_of {#aspose.cells.vba.VbaModule-int}
يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.


###  عائدات

الفهرس الصفري للتواجد الأول للقيمة ضمن نطاق العناصر في قائمة المصفوفة والذي يمتد من startIndex إلى العنصر الأخير، إذا وجد؛ وإلا -1.


```python
def index_of(self, item, index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule) | الكائن المطلوب تحديد موقعه في قائمة المصفوفات. يمكن أن تكون القيمة فارغة.|
| index | int | فهرس البداية للبحث ذو الأساس الصفري. 0 (صفر) صالح في قائمة فارغة.|


##  index_of {#aspose.cells.vba.VbaModule-int-int}
يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.


###  عائدات

الفهرس الصفري للتواجد الأول للقيمة ضمن نطاق العناصر في قائمة المصفوفة الذي يبدأ عند startIndex ويحتوي على عدد العناصر، إذا تم العثور عليها؛ وإلا -1.


```python
def index_of(self, item, index, count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule) | الكائن المطلوب تحديد موقعه في قائمة المصفوفات. يمكن أن تكون القيمة فارغة.|
| index | int | فهرس البداية للبحث ذو الأساس الصفري. 0 (صفر) صالح في قائمة فارغة.|
| count | int | عدد العناصر في القسم المراد البحث عنها.|



###  أنظر أيضا
* الوحدة [`aspose.cells.vba`](../../)
* فئة [`VbaModuleCollection`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection)
