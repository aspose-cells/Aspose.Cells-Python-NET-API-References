---
title: طريقة get_cell_display_style
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 320
url: /ar/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
احصل على نمط العرض للخلية المحددة.


###  عائدات

أسلوب عرض الخلية المحددة.


```python

def get_cell_display_style(self, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف للخلية المحددة|
| column | int | عمود الخلية المحددة|
###  ملاحظات

نفس الشيء مع [`Cell.get_display_style`](/cells/python-net/ar/aspose.cells/cell/get_display_style)،
والشيء نفسه مع استخدام [`BorderType.SIDE_BORDERS`](/cells/python-net/ar/aspose.cells/bordertype#SIDE_BORDERS)
لرقم [`Cells.get_cell_display_style`](/cells/python-net/ar/aspose.cells/cells/get_cell_display_style).

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
احصل على نمط العرض للخلية المحددة.


###  عائدات

أسلوب عرض الخلية المحددة.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف للخلية المحددة|
| column | int | عمود الخلية المحددة|
| adjacent_borders | [`BorderType`](/cells/python-net/ar/aspose.cells/bordertype) | يشير إلى الحدود التي تحتاج إلى التحقق منها وتعديلها وفقًا لحدود الخلايا المجاورة.<br/>يرجى الاطلاع على الوصف لنفس المعلمة<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  ملاحظات

إذا كانت الخلية تتأثر أيضًا بإعدادات أخرى مثل التنسيق الشرطي وكائنات القائمة وما إلى ذلك،
ثم قد يكون نمط العرض مختلفًا عن [`Cells.get_cell_style`](/cells/python-net/ar/aspose.cells/cells/get_cell_style).
ولأن هذه الإعدادات قد يتم تطبيقها أيضًا على الخلايا الفارغة (غير الموجودة)،
يمكن تجنب إنشاء تلك الخلايا الفارغة باستخدام هذه الطريقة
لذا فإن الأداء سيكون أفضل من الحصول على المثيل Cell من Cells
ومن ثم الاتصال على الرقم [`Cell.get_display_style`](/cells/python-net/ar/aspose.cells/cell/get_display_style).


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
