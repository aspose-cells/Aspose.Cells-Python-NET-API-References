---
title: طريقة last_index_of
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells.vba/vbamodulecollection/last_index_of/
is_root: false
---
##  last_index_of {#aspose.cells.vba.VbaModule}
يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.


###  عائدات

الفهرس الصفري لآخر تواجد للقيمة ضمن قائمة المصفوفة بأكملها، إذا تم العثور عليها؛ وإلا -1.


```python
def last_index_of(self, item):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule) | الكائن المطلوب تحديد موقعه في قائمة المصفوفات. يمكن أن تكون القيمة فارغة.|


##  last_index_of {#aspose.cells.vba.VbaModule-int}
يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.


###  عائدات

الفهرس الصفري لآخر تواجد للقيمة ضمن نطاق العناصر في قائمة المصفوفة والذي يمتد من العنصر الأول إلى startIndex، إذا وجد؛ وإلا -1.


```python
def last_index_of(self, item, index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule) | الكائن المطلوب تحديد موقعه في قائمة المصفوفات. يمكن أن تكون القيمة فارغة.|
| index | int | فهرس البداية الصفري للبحث الخلفي.|


##  last_index_of {#aspose.cells.vba.VbaModule-int-int}
يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.


###  عائدات

الفهرس الصفري لآخر تواجد للقيمة ضمن نطاق العناصر في System.Collections. قائمة المصفوفات التي تحتوي على عدد من العناصر وتنتهي عند startIndex، إذا وجدت؛ وإلا -1.


```python
def last_index_of(self, item, index, count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule) | الكائن المطلوب تحديد موقعه في قائمة المصفوفات. يمكن أن تكون القيمة فارغة.|
| index | int | فهرس البداية الصفري للبحث الخلفي.|
| count | int | عدد العناصر في القسم المراد البحث عنها.|



###  أنظر أيضا
* الوحدة [`aspose.cells.vba`](../../)
* فئة [`VbaModuleCollection`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection)
