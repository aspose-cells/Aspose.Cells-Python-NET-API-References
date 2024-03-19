---
title: HyperlinkCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 850
url: /ar/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection صف
يغلف مجموعة من [`Hyperlink`](/cells/python-net/ar/aspose.cells/hyperlink) كائن.



يكشف النوع HyperlinkCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/hyperlinkcollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | إضافة ارتباط تشعبي إلى خلية محددة أو نطاق من الخلايا.|
| [add](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | إضافة ارتباط تشعبي إلى خلية محددة أو نطاق من الخلايا.|
| [add](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | إضافة ارتباط تشعبي إلى خلية محددة أو نطاق من الخلايا.|
| [copy_to](/cells/python-net/ar/aspose.cells/hyperlinkcollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [binary_search](/cells/python-net/ar/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Hyperlink`](/cells/python-net/ar/aspose.cells/hyperlink)
