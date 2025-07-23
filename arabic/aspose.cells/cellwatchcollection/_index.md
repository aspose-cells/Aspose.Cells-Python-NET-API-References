---
title: CellWatchCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 150
url: /ar/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection صف
يمثل مجموعة الخلايا الموجودة في ورقة العمل هذه والتي يتم مراقبتها في "نافذة المراقبة".



يكشف النوع CellWatchCollection عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/__init__/#) | إنشاء مثيل جديد لـ CellWatchCollection|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/cellwatchcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/add/#int-int) | يضيف [`CellWatch`](/cells/python-net/ar/aspose.cells/cellwatch) مع الصف والعمود.|
| [`add(self, cell_name)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/add/#str) | يضيف [`CellWatch`](/cells/python-net/ar/aspose.cells/cellwatch) باسم الخلية.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`get(self, cell_name)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/get/#str) | يحصل ويضبط [`CellWatch`](/cells/python-net/ar/aspose.cells/cellwatch) حسب اسم الخلية.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`CellWatch`](/cells/python-net/ar/aspose.cells/cellwatch)
