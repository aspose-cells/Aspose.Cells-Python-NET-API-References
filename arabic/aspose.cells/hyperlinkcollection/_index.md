---
title: HyperlinkCollection الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 800
url: /ar/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection الدرجة
لتغليف مجموعة من [Hyperlink](/cells/python-net/ar/aspose.cells/hyperlink) عنصر.



يكشف نوع HyperlinkCollection الأعضاء التالية:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/hyperlinkcollection/capacity) | الحصول على أو تحديد عدد العناصر التي يمكن أن تحتويها قائمة الصفيف.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add(first_row, first_column, total_rows, total_columns, address)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.|
| [add(cell_name, total_rows, total_columns, address)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.|
| [add(start_cell_name, end_cell_name, address, text_to_display, screen_tip)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.|
| [copy_to(array)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/copy_to/#list) | ينسخ قائمة المصفوفات بأكملها إلى قائمة مصفوفة متوافقة أحادية البعد ، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to(index, array, array_index, count)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) |ينسخ نطاقًا من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة ، بدءًا من الفهرس المحدد لقائمة الصفيف الهدف.|
| [index_of(item, index)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/index_of/#Hyperlink-int) | البحث عن الكائن المحدد وإرجاع الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة الصفيف الذي يمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of(item, index, count)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/index_of/#Hyperlink-int-int) | البحث عن الكائن المحدد وإرجاع الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة الصفيف الذي يبدأ بالفهرس المحدد ويحتوي على عدد محدد من العناصر.|
| [last_index_of(item)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#Hyperlink) | البحث عن الكائن المحدد وإرجاع الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of(item, index)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#Hyperlink-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة الصفيف الذي يمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of(item, index, count)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#Hyperlink-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة الصفيف التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [binary_search(item)](/cells/python-net/ar/aspose.cells/hyperlinkcollection/binary_search/#Hyperlink) | يبحث في قائمة الصفيف التي تم فرزها بالكامل عن عنصر باستخدام المقارنة الافتراضية ويعيد فهرس العنصر على أساس الصفر.|



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
* وحدة [aspose.cells](..)
* فئة [Hyperlink](/cells/python-net/ar/aspose.cells/hyperlink)
