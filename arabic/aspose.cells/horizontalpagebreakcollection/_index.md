---
title: HorizontalPageBreakCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 790
url: /ar/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection صف
يغلف مجموعة من [`HorizontalPageBreak`](/cells/python-net/ar/aspose.cells/horizontalpagebreak) كائن.



يكشف النوع HorizontalPageBreakCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) |إضافة فاصل صفحات أفقي إلى المجموعة.|
| [add](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/add/#int) |إضافة فاصل صفحات أفقي إلى المجموعة.|
| [add](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/add/#int-int) |إضافة فاصل صفحات أفقي إلى المجموعة.|
| [add](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/add/#str) |إضافة فاصل صفحات أفقي إلى المجموعة.|
| [copy_to](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [binary_search](/cells/python-net/ar/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.HorizontalPageBreak) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`HorizontalPageBreak`](/cells/python-net/ar/aspose.cells/horizontalpagebreak)
