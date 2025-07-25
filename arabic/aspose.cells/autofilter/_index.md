---
title: AutoFilter صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter صف
يمثل التصفية التلقائية للورقة العمل المحددة.



يكشف النوع AutoFilter عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [sorter](/cells/python-net/ar/aspose.cells/autofilter/sorter) | يحصل على فرز البيانات.|
| [range](/cells/python-net/ar/aspose.cells/autofilter/range) | يمثل النطاق الذي ينطبق عليه AutoFilter المحدد.|
| [show_filter_button](/cells/python-net/ar/aspose.cells/autofilter/show_filter_button) | يشير إلى ما إذا كان زر التصفية التلقائية لهذا العمود مرئيًا.|
| [filter_columns](/cells/python-net/ar/aspose.cells/autofilter/filter_columns) | يحصل على مجموعة من أعمدة الفلتر.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/ar/aspose.cells/autofilter/get_cell_area/#) | يحصل على [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) حيث ينطبق هذا المرشح التلقائي.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/ar/aspose.cells/autofilter/get_cell_area/#bool) | يحصل على [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) حيث يتم تطبيق AutoFilter المحدد عليه.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/ar/aspose.cells/autofilter/remove_filter/#int-str) | إزالة مرشح لعمود المرشح.|
| [`remove_filter(self, field_index)`](/cells/python-net/ar/aspose.cells/autofilter/remove_filter/#int) | إزالة الفلتر المحدد.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/ar/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | يقوم بتصفية القائمة باستخدام معايير مخصصة.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/ar/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | يقوم بتصفية القائمة باستخدام معايير مخصصة.|
| [`refresh(self)`](/cells/python-net/ar/aspose.cells/autofilter/refresh/#) | قم بتحديث المرشحات التلقائية لإخفاء الصفوف أو إظهارها.|
| [`refresh(self, hide_rows)`](/cells/python-net/ar/aspose.cells/autofilter/refresh/#bool) | يحصل على جميع فهرس الصفوف المخفية.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/ar/aspose.cells/autofilter/set_range/#int-int-int) | تعيين النطاق الذي ينطبق عليه AutoFilter المحدد.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/ar/aspose.cells/autofilter/add_filter/#int-str) | إضافة مرشح لعمود المرشح.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/ar/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | إضافة مرشح التاريخ.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/ar/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |إزالة مرشح التاريخ.|
| [`filter(self, field_index, criteria)`](/cells/python-net/ar/aspose.cells/autofilter/filter/#int-str) | يقوم بتصفية القائمة باستخدام المعايير المحددة.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/ar/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | تصفية أفضل 10 عناصر في القائمة|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/ar/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | إضافة مرشح ديناميكي.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/ar/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | إضافة مرشح لون الخط.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/ar/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | يضيف مرشح لون التعبئة.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/ar/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | إضافة مرشح أيقونة.|
| [`match_blanks(self, field_index)`](/cells/python-net/ar/aspose.cells/autofilter/match_blanks/#int) | قم بمطابقة جميع الخلايا الفارغة في القائمة.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/ar/aspose.cells/autofilter/match_non_blanks/#int) | قم بمطابقة جميع الخلايا غير الفارغة في القائمة.|
| [`show_all(self)`](/cells/python-net/ar/aspose.cells/autofilter/show_all/#) | إظهار كافة الصفوف.|



###  مثال

```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea)
