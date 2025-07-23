---
title: ListColumn صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cells.tables/listcolumn/
is_root: false
---
##  ListColumn صف
يمثل عمودًا في جدول.



يكشف النوع ListColumn عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [name](/cells/python-net/ar/aspose.cells.tables/listcolumn/name) | يحصل على اسم العمود ويحدده.|
| [totals_calculation](/cells/python-net/ar/aspose.cells.tables/listcolumn/totals_calculation) | يحصل على نوع الحساب ويحدده في صف الإجماليات في عمود القائمة.|
| [range](/cells/python-net/ar/aspose.cells.tables/listcolumn/range) | يحصل على نطاق عمود القائمة هذا.|
| [is_array_formula](/cells/python-net/ar/aspose.cells.tables/listcolumn/is_array_formula) | يشير إلى ما إذا كانت الصيغة عبارة عن صيغة مصفوفة.|
| [formula](/cells/python-net/ar/aspose.cells.tables/listcolumn/formula) | يحصل على صيغة عمود القائمة ويقوم بتعيينها.|
| [totals_row_label](/cells/python-net/ar/aspose.cells.tables/listcolumn/totals_row_label) | يحصل على ويقوم بتعيين تسميات العرض للصف الإجمالي.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) | يحصل على صيغة إجمالي صف عمود القائمة هذا.|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) | يحصل على صيغة إجمالي صف عمود القائمة هذا.|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) | يحصل على صيغة عمود القائمة هذا.|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) | تعيين الصيغة لهذا العمود القائمة.|
| [`get_data_style(self)`](/cells/python-net/ar/aspose.cells.tables/listcolumn/get_data_style/#) | يحصل على نمط البيانات في هذا العمود من الجدول.|
| [`set_data_style(self, style)`](/cells/python-net/ar/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) | تعيين نمط البيانات في هذا العمود من الجدول.|



###  مثال

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(4):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
listColumn = table.list_columns[4]
listColumn.totals_calculation = TotalsCalculation.SUM
listColumn.formula = "=[A]"
workbook.save(r"Book1.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.tables`](..)
