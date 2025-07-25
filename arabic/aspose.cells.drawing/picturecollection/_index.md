---
title: PictureCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 440
url: /ar/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection صف
يقوم بتغليف مجموعة من الكائنات [`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture).



يكشف النوع PictureCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.drawing/picturecollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | إضافة صورة إلى المجموعة.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | إضافة صورة إلى المجموعة.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | إضافة صورة إلى المجموعة.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/add/#int-int-str) | إضافة صورة إلى المجموعة.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | إضافة صورة إلى المجموعة.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | إضافة صورة إلى المجموعة.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`camera(self, row, column, range)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/camera/#int-int-str) | يلتقط صورة للمجموعة.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
* فئة [`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture)
