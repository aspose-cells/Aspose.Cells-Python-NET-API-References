---
title: ListObject صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject صف
يمثل كائن القائمة في ورقة العمل.
 الكائن ListObject هو عضو في مجموعة ListObjects.
تحتوي مجموعة ListObjects على كافة كائنات القائمة الموجودة في ورقة العمل.



يكشف النوع ListObject عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [start_row](/cells/python-net/ar/aspose.cells.tables/listobject/start_row) | يحصل على الصف الأول من النطاق.|
| [start_column](/cells/python-net/ar/aspose.cells.tables/listobject/start_column) | يحصل على عمود البداية للنطاق.|
| [end_row](/cells/python-net/ar/aspose.cells.tables/listobject/end_row) | يحصل على الصف النهائي للنطاق.|
| [end_column](/cells/python-net/ar/aspose.cells.tables/listobject/end_column) | يحصل على العمود النهائي للنطاق.|
| [list_columns](/cells/python-net/ar/aspose.cells.tables/listobject/list_columns) | يحصل على ListColumns من ListObject.|
| [show_header_row](/cells/python-net/ar/aspose.cells.tables/listobject/show_header_row) | يحصل ويحدد ما إذا كان ListObject هذا يعرض صف الرأس أم لا.|
| [show_totals](/cells/python-net/ar/aspose.cells.tables/listobject/show_totals) | يحصل ويحدد ما إذا كان ListObject هذا يعرض إجمالي الصف.|
| [data_range](/cells/python-net/ar/aspose.cells.tables/listobject/data_range) | يحصل على نطاق البيانات الخاص بـ ListObject.|
| [query_table](/cells/python-net/ar/aspose.cells.tables/listobject/query_table) | يحصل على جدول الاستعلام المرتبط.|
| [data_source_type](/cells/python-net/ar/aspose.cells.tables/listobject/data_source_type) |يحصل على نوع مصدر البيانات للجدول.|
| [auto_filter](/cells/python-net/ar/aspose.cells.tables/listobject/auto_filter) | يحصل على مرشح تلقائي.|
| [display_name](/cells/python-net/ar/aspose.cells.tables/listobject/display_name) | يحصل على اسم العرض ويحدده.|
| [comment](/cells/python-net/ar/aspose.cells.tables/listobject/comment) | يحصل على تعليق الجدول ويضبطه.|
| [show_table_style_first_column](/cells/python-net/ar/aspose.cells.tables/listobject/show_table_style_first_column) | يشير إلى ما إذا كان يجب تطبيق النمط على العمود الأول في الجدول.|
| [show_table_style_last_column](/cells/python-net/ar/aspose.cells.tables/listobject/show_table_style_last_column) | يشير إلى ما إذا كان يجب تطبيق النمط على العمود الأخير في الجدول.|
| [show_table_style_row_stripes](/cells/python-net/ar/aspose.cells.tables/listobject/show_table_style_row_stripes) | يشير إلى ما إذا كان يتم تطبيق تنسيق شريط الصف.|
| [show_table_style_column_stripes](/cells/python-net/ar/aspose.cells.tables/listobject/show_table_style_column_stripes) | يشير إلى ما إذا كان يتم تطبيق تنسيق شريط العمود.|
| [table_style_type](/cells/python-net/ar/aspose.cells.tables/listobject/table_style_type) | يحصل على نمط الجدول المدمج.|
| [table_style_name](/cells/python-net/ar/aspose.cells.tables/listobject/table_style_name) | يحصل على اسم نمط الجدول ويقوم بتعيينه.|
| [xml_map](/cells/python-net/ar/aspose.cells.tables/listobject/xml_map) | يحصل على [`ListObject.xml_map`](/cells/python-net/ar/aspose.cells.tables/listobject#xml_map) المستخدم لهذه القائمة.|
| [alternative_text](/cells/python-net/ar/aspose.cells.tables/listobject/alternative_text) | يحصل على النص البديل ويحدده.|
| [alternative_description](/cells/python-net/ar/aspose.cells.tables/listobject/alternative_description) | يحصل على الوصف البديل ويحدده.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/ar/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | ضع القيمة في الخلية.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/ar/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | ضع القيمة في الخلية.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/ar/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | ضع الصيغة في الخلية الموجودة في الجدول.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/ar/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | ضع الصيغة في الخلية الموجودة في الجدول.|
| [`convert_to_range(self)`](/cells/python-net/ar/aspose.cells.tables/listobject/convert_to_range/#) | تحويل الجدول إلى نطاق.|
| [`convert_to_range(self, options)`](/cells/python-net/ar/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | تحويل الجدول إلى نطاق.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/ar/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | تغيير حجم نطاق كائن القائمة.|
| [`update_column_name(self)`](/cells/python-net/ar/aspose.cells.tables/listobject/update_column_name/#) | تحديث اسم جميع أعمدة القائمة من ورقة العمل.|
| [`filter(self)`](/cells/python-net/ar/aspose.cells.tables/listobject/filter/#) | تصفية الجدول.|
| [`apply_style_to_range(self)`](/cells/python-net/ar/aspose.cells.tables/listobject/apply_style_to_range/#) | تطبيق نمط الجدول على النطاق.|



###  مثال

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.tables`](..)
