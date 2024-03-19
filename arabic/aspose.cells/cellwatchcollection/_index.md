---
title: CellWatchCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 180
url: /ar/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection صف
يمثل مجموعة الخلايا الموجودة في ورقة العمل هذه والتي يتم مراقبتها في "نافذة المراقبة".



يكشف النوع CellWatchCollection عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/cellwatchcollection/__init__/#) | إنشاء مثيل جديد لـ CellWatchCollection|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/cellwatchcollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells/cellwatchcollection/add/#int-int) | يضيف [`CellWatch`](/cells/python-net/ar/aspose.cells/cellwatch) مع الصف والعمود.|
| [add](/cells/python-net/ar/aspose.cells/cellwatchcollection/add/#str) | يضيف [`CellWatch`](/cells/python-net/ar/aspose.cells/cellwatch) باسم الخلية.|
| [copy_to](/cells/python-net/ar/aspose.cells/cellwatchcollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [binary_search](/cells/python-net/ar/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.CellWatch) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



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
