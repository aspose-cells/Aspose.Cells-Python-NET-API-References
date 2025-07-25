---
title: PivotFilter صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 140
url: /ar/aspose.cells.pivot/pivotfilter/
is_root: false
---
##  PivotFilter صف
يمثل PivotFilter في مجموعة PivotFilter.



يكشف النوع PivotFilter عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [use_whole_day](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/use_whole_day) | يشير إلى ما إذا كان يتم استخدام أيام كاملة في معايير التصفية الخاصة به.|
| [auto_filter](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/auto_filter) | يحصل على المرشح التلقائي لمرشح المحور.|
| [filter_type](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/filter_type) | يحصل على نوع التصفية التلقائية لمرشح المحور.|
| [field_index](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/field_index) | يحصل على مؤشر حقل المصدر الذي تم تطبيق مرشح المحور هذا عليه.|
| [filter_category](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/filter_category) | يحصل على فئة هذا الفلتر.|
| [value1](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/value1) | يحصل على قيمة السلسلة 1 لمرشح محور التسمية.|
| [value2](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/value2) | يحصل على قيمة السلسلة 2 لمرشح محور التسمية.|
| [measure_fld_index](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/measure_fld_index) | يحصل على مؤشر حقل القياس لمرشح المحور.|
| [value_field_index](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/value_field_index) | يحصل على مؤشر حقل القيمة في منطقة القيمة.|
| [measure_cube_field_index](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/measure_cube_field_index) | يحدد مؤشر حقل مكعب القياس.<br/>يتم استخدام هذه الخاصية فقط بواسطة المرشحات في محاور OLAP وتحدد المقياس الذي يجب أن ينطبق عليه مرشح القيمة.|
| [member_property_field_index](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/member_property_field_index) | يحصل على فهرس حقل خاصية العضو لمرشح المحور.|
| [name](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/name) | يحصل على اسم مرشح المحور.|
| [evaluation_order](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/evaluation_order) | يحصل على ترتيب التقييم لمرشح المحور.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_top_10_value(self)`](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/get_top_10_value/#) | يحصل على أفضل 10 إعدادات للمرشح.|
| [`get_labels(self)`](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/get_labels/#) | يحصل على تسميات مرشح التسمية التوضيحية.|
| [`get_number_values(self)`](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/get_number_values/#) | يحصل على قيم مرشح الأرقام.|
| [`get_date_time_values(self)`](/cells/python-net/ar/aspose.cells.pivot/pivotfilter/get_date_time_values/#) | يحصل على قيم مرشح الأرقام.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType

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
# Add top 10 filter
pivot.base_fields[0].filter_top10(0, PivotFilterType.COUNT, False, 2)
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](..)
