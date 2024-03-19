---
title: CommentCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 300
url: /ar/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection صف
يغلف مجموعة من [`Comment`](/cells/python-net/ar/aspose.cells/comment) كائن.



يكشف النوع CommentCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/commentcollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add_threaded_comment](/cells/python-net/ar/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) | يضيف تعليقًا مترابطة.|
| [add_threaded_comment](/cells/python-net/ar/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) | يضيف تعليقًا مترابطة.|
| [get_threaded_comments](/cells/python-net/ar/aspose.cells/commentcollection/get_threaded_comments/#int-int) | يحصل على التعليقات المترابطة حسب فهرس الصف والعمود.|
| [get_threaded_comments](/cells/python-net/ar/aspose.cells/commentcollection/get_threaded_comments/#str) |يحصل على التعليقات المترابطة حسب اسم الخلية.|
| [add](/cells/python-net/ar/aspose.cells/commentcollection/add/#int-int) | يضيف تعليقًا إلى المجموعة.|
| [add](/cells/python-net/ar/aspose.cells/commentcollection/add/#str) | يضيف تعليقًا إلى المجموعة.|
| [remove_at](/cells/python-net/ar/aspose.cells/commentcollection/remove_at/#str) | يزيل تعليق الخلية المحددة.|
| [remove_at](/cells/python-net/ar/aspose.cells/commentcollection/remove_at/#int-int) | يزيل تعليق الخلية المحددة.|
| [copy_to](/cells/python-net/ar/aspose.cells/commentcollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells/commentcollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [binary_search](/cells/python-net/ar/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Comment`](/cells/python-net/ar/aspose.cells/comment)
