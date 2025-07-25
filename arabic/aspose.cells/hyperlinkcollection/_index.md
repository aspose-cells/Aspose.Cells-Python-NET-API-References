---
title: HyperlinkCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 830
url: /ar/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection صف
يقوم بتغليف مجموعة من الكائنات [`Hyperlink`](/cells/python-net/ar/aspose.cells/hyperlink).



يكشف النوع HyperlinkCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/hyperlinkcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, first_row, first_column, total_rows, total_columns, address)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.|
| [`add(self, cell_name, total_rows, total_columns, address)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.|
| [`add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.hyperlink) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



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
