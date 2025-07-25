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
| [capacity](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | إضافة وحدة إلى ورقة العمل.|
| [`add(self, type, name)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | إضافة وحدة.|
| [`get(self, index)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/get/#int) | يحصل على [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule) في القائمة بواسطة الفهرس.|
| [`get(self, name)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/get/#str) | يحصل على [`VbaModule`](/cells/python-net/ar/aspose.cells.vba/vbamodule) في القائمة بالاسم.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | يمثل بيانات المصمم.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | أدخل نموذج المستخدم في مشروع VBA.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | إزالة الوحدة النمطية من ورقة العمل.|
| [`remove_by_name(self, name)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | إزالة الوحدة حسب الاسم|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



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
