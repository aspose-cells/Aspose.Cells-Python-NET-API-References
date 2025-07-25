---
title: CommentCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 270
url: /ar/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection صف
يقوم بتغليف مجموعة من الكائنات [`Comment`](/cells/python-net/ar/aspose.cells/comment).



يكشف النوع CommentCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/commentcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/ar/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | يضيف تعليقًا مترابطًا.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/ar/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | يضيف تعليقًا مترابطًا.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/ar/aspose.cells/commentcollection/get_threaded_comments/#int-int) | يحصل على التعليقات المترابطة حسب مؤشر الصف والعمود.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/ar/aspose.cells/commentcollection/get_threaded_comments/#str) | يحصل على التعليقات المترابطة حسب اسم الخلية.|
| [`add(self, row, column)`](/cells/python-net/ar/aspose.cells/commentcollection/add/#int-int) | يضيف تعليقًا إلى المجموعة.|
| [`add(self, cell_name)`](/cells/python-net/ar/aspose.cells/commentcollection/add/#str) | يضيف تعليقًا إلى المجموعة.|
| [`get(self, row, column)`](/cells/python-net/ar/aspose.cells/commentcollection/get/#int-int) | أضف API for Python عبر .Net. نظرًا لأن هذا [int، int] غير مدعوم|
| [`get(self, index)`](/cells/python-net/ar/aspose.cells/commentcollection/get/#int) | يحصل على العنصر [`Comment`](/cells/python-net/ar/aspose.cells/comment) في الفهرس المحدد.|
| [`get(self, cell_name)`](/cells/python-net/ar/aspose.cells/commentcollection/get/#str) | يحصل على العنصر [`Comment`](/cells/python-net/ar/aspose.cells/comment) في الخلية المحددة.|
| [`remove_at(self, cell_name)`](/cells/python-net/ar/aspose.cells/commentcollection/remove_at/#str) | إزالة تعليق الخلية المحددة.|
| [`remove_at(self, row, column)`](/cells/python-net/ar/aspose.cells/commentcollection/remove_at/#int-int) | إزالة تعليق الخلية المحددة.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells/commentcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells/commentcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Comment`](/cells/python-net/ar/aspose.cells/comment)
