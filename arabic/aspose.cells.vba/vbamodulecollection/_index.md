---
title: VbaModuleCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection صف
يمثل قائمة [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule)



يكشف النوع VbaModuleCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.Worksheet) | يضيف وحدة نمطية لورقة العمل.|
| [add](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.VbaModuleType-str) | يضيف الوحدة النمطية.|
| [copy_to](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [add_designer_storage](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [get_designer_storage](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | يمثل بيانات المصمم.|
| [add_user_form](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | أدخل نموذج المستخدم في مشروع VBA.|
| [binary_search](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.VbaModule) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.vba`](..)
* فئة [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule)
