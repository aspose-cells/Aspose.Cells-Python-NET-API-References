---
title: PivotTableCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 250
url: /ar/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection صف
يمثل مجموعة كل كائنات PivotTable الموجودة في ورقة العمل المحددة.



يكشف النوع PivotTableCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, source_data, dest_cell_name, table_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | إضافة جدول محوري جديد.|
| [`add(self, source_data, dest_cell_name, table_name, use_same_source)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | إضافة جدول محوري جديد.|
| [`add(self, source_data, row, column, table_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | إضافة جدول محوري جديد.|
| [`add(self, source_data, row, column, table_name, use_same_source)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | إضافة جدول محوري جديد.|
| [`add(self, source_data, row, column, table_name, use_same_source, is_xls_classic)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool-bool) | إضافة جدول محوري جديد.|
| [`add(self, source_data, cell, table_name, use_same_source, is_xls_classic)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool-bool) | إضافة جدول محوري جديد.|
| [`add(self, pivot_table, dest_cell_name, table_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-str-str) | إضافة جدول محوري جديد استنادًا إلى جدول محوري آخر.|
| [`add(self, pivot_table, row, column, table_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | إضافة جدول محوري جديد استنادًا إلى جدول محوري آخر.|
| [`add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-str-str) | إضافة كائن جدول محوري جديد إلى المجموعة التي تحتوي على نطاقات توحيد متعددة كمصدر بيانات.|
| [`add(self, source_data, is_auto_page, page_fields, row, column, table_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-int-int-str) | إضافة كائن جدول محوري جديد إلى المجموعة التي تحتوي على نطاقات توحيد متعددة كمصدر بيانات.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`get(self, name)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/get/#str) | يحصل على تقرير PivotTable حسب اسم PivotTable.|
| [`remove_pivot_table(self, pivot_table)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/remove_pivot_table/#aspose.cells.pivot.pivottable) | يحذف جدول البيانات المحوري المحدد ويحذف بيانات جدول البيانات المحوري|
| [`remove_pivot_table_data(self, pivot_table, keep_data)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/remove_pivot_table_data/#aspose.cells.pivot.pivottable-bool) | يحذف جدول البيانات المحوري المحدد|
| [`remove_by_index(self, index)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/remove_by_index/#int) | يحذف جدول البيانات المحوري عند الفهرس المحدد ويحذف بيانات جدول البيانات المحوري|
| [`remove_at(self, index, keep_data)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | يحذف الجدول المحوري عند الفهرس المحدد|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.pivottable) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



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
