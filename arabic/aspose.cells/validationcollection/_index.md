---
title: ValidationCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1620
url: /ar/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection صف
يمثل جمع التحقق من صحة البيانات.



يكشف النوع ValidationCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/validationcollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells/validationcollection/add/#) | يضيف التحقق من صحة البيانات إلى المجموعة.|
| [add](/cells/python-net/ar/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | يضيف التحقق من صحة البيانات إلى المجموعة.|
| [copy_to](/cells/python-net/ar/aspose.cells/validationcollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells/validationcollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [remove_a_cell](/cells/python-net/ar/aspose.cells/validationcollection/remove_a_cell/#int-int) | إزالة كافة إعدادات التحقق من الصحة على الخلية.|
| [remove_area](/cells/python-net/ar/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | يزيل كافة إعدادات التحقق من الصحة على النطاق..|
| [get_validation_in_cell](/cells/python-net/ar/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | يحصل على التحقق من الصحة المطبق على خلية معينة.|
| [binary_search](/cells/python-net/ar/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



###  مثال

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
