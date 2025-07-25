---
title: ColumnCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 250
url: /ar/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection صف
مجموعة من الكائنات [`Column`](/cells/python-net/ar/aspose.cells/column) التي تمثل الأعمدة الفردية في ورقة العمل.
يمثل كائن العمود فقط الإعدادات مثل عرض العمود والأنماط وما إلى ذلك للعمود بأكمله،
لا علاقة له بحقيقة وجود خلايا غير فارغة (بيانات) أو عدم وجودها في العمود المقابل.
ويمثل "Count" في هذه المجموعة فقط عدد كائنات العمود التي تم إنشاؤها في هذه المجموعة،
لا علاقة له بحقيقة وجود خلايا غير فارغة (بيانات) أو عدم وجودها في ورقة العمل.



يكشف النوع ColumnCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/columncollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells/columncollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells/columncollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`get_by_index(self, index)`](/cells/python-net/ar/aspose.cells/columncollection/get_by_index/#int) | يحصل على كائن العمود حسب الفهرس.|
| [`get_column_by_index(self, index)`](/cells/python-net/ar/aspose.cells/columncollection/get_column_by_index/#int) | يحصل على الكائن [`Column`](/cells/python-net/ar/aspose.cells/column) حسب الموضع في القائمة.|
| [`get(self, column_index)`](/cells/python-net/ar/aspose.cells/columncollection/get/#int) | أضف API for Python عبر .Net.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells/columncollection/binary_search/#aspose.cells.column) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Column`](/cells/python-net/ar/aspose.cells/column)
