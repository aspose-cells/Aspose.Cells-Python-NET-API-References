---
title: TextBoxCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 670
url: /ar/aspose.cells.drawing/textboxcollection/
is_root: false
---
##  TextBoxCollection صف
يقوم بتغليف مجموعة من الكائنات [`TextBox`](/cells/python-net/ar/aspose.cells.drawing/textbox).



يكشف النوع TextBoxCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`get(self, name)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/get/#str) | يحصل على العنصر [`TextBox`](/cells/python-net/ar/aspose.cells.drawing/textbox) حسب الاسم.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/add/#int-int-int-int) | إضافة مربع نص إلى المجموعة.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.drawing/textboxcollection/binary_search/#aspose.cells.drawing.textbox) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get collection object
textBoxCollection = workbook.worksheets[0].text_boxes
# add a textbox
textBoxCollection.add(1, 1, 50, 100)
for tbox in textBoxCollection:
    pass

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
* فئة [`TextBox`](/cells/python-net/ar/aspose.cells.drawing/textbox)
