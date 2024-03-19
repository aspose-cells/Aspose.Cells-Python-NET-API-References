---
title: PivotTableCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 190
url: /ar/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection صف
يمثل مجموعة كافة كائنات PivotTable في ورقة العمل المحددة.



يكشف النوع PivotTableCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | إضافة ذاكرة تخزين مؤقت PivotTable جديدة إلى مجموعة PivotCaches.|
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | إضافة ذاكرة تخزين مؤقت PivotTable جديدة إلى مجموعة PivotCaches.|
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | إضافة ذاكرة تخزين مؤقت PivotTable جديدة إلى مجموعة PivotCaches.|
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | إضافة ذاكرة تخزين مؤقت PivotTable جديدة إلى مجموعة PivotCaches.|
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.PivotTable-str-str) | إضافة كائن PivotTable جديد إلى المجموعة من PivotTable آخر.|
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.PivotTable-int-int-str) | إضافة كائن PivotTable جديد إلى المجموعة من PivotTable آخر.|
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.PivotPageFields-str-str) |إضافة كائن PivotTable جديد إلى المجموعة بنطاقات دمج متعددة كمصدر بيانات.|
| [add](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str) |إضافة كائن PivotTable جديد إلى المجموعة بنطاقات دمج متعددة كمصدر بيانات.|
| [copy_to](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.PivotTable-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.PivotTable-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [remove_at](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | حذف PivotTable في الفهرس المحدد|
| [binary_search](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.PivotTable) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



###  مثال

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](..)
