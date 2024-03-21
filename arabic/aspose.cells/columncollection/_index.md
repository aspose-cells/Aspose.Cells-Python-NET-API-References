---
title: ColumnCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 280
url: /ar/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection صف
مجموعة من الكائنات [`Column`](/cells/python-net/ar/aspose.cells/column) التي تمثل الأعمدة الفردية (الإعدادات) في ورقة العمل.
يمثل كائن العمود فقط الإعدادات مثل عرض العمود والأنماط وما إلى ذلك. للعمود بأكمله،
لا علاقة له بحقيقة وجود خلايا (بيانات) غير فارغة أو عدم وجودها في العمود المقابل.
و"العدد" في هذه المجموعة يمثل فقط عدد كائنات العمود التي تم إنشاء مثيل لها في هذه المجموعة،
لا علاقة له بحقيقة وجود خلايا (بيانات) غير فارغة أو عدم وجودها في ورقة العمل.



يكشف النوع ColumnCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells/columncollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [copy_to](/cells/python-net/ar/aspose.cells/columncollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells/columncollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells/columncollection/index_of/#aspose.cells.Column-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells/columncollection/index_of/#aspose.cells.Column-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells/columncollection/last_index_of/#aspose.cells.Column) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [get_by_index](/cells/python-net/ar/aspose.cells/columncollection/get_by_index/#int) | يحصل على كائن العمود بواسطة الفهرس.|
| [get_column_by_index](/cells/python-net/ar/aspose.cells/columncollection/get_column_by_index/#int) | يحصل على الكائن [`Column`](/cells/python-net/ar/aspose.cells/column) حسب الموضع في القائمة.|
| [binary_search](/cells/python-net/ar/aspose.cells/columncollection/binary_search/#aspose.cells.Column) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



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
