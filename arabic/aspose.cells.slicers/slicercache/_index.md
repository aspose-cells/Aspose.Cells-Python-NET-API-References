---
title: SlicerCache صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.slicers/slicercache/
is_root: false
---
##  SlicerCache صف
تمثيل وصف موجز لذاكرة التخزين المؤقت للشرائح



يكشف النوع SlicerCache عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [cross_filter_type](/cells/python-net/ar/aspose.cells.slicers/slicercache/cross_filter_type) | إرجاع أو تعيين ما إذا كانت أداة التقطيع تشارك في التصفية المتبادلة مع أدوات التقطيع الأخرى<br/> التي تشترك في نفس ذاكرة التخزين المؤقت للمُقطّع، وكيفية عرض التصفية المتقاطعة. القراءة/الكتابة|
| [list](/cells/python-net/ar/aspose.cells.slicers/slicercache/list) | يُرجع ما إذا كانت الشريحة المرتبطة بذاكرة التخزين المؤقت للشريحة المحددة تستند إلى مصدر بيانات غير OLAP. للقراءة فقط|
| [slicer_cache_items](/cells/python-net/ar/aspose.cells.slicers/slicercache/slicer_cache_items) | يُرجع مجموعة SlicerCacheItem التي تحتوي على مجموعة جميع العناصر في ذاكرة التخزين المؤقت للمُقطّع. للقراءة فقط|
| [name](/cells/python-net/ar/aspose.cells.slicers/slicercache/name) | إرجاع اسم ذاكرة التخزين المؤقت للتقطيع.|
| [source_name](/cells/python-net/ar/aspose.cells.slicers/slicercache/source_name) | إرجاع اسم ذاكرة التخزين المؤقت لهذه الشريحة.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.cells.slicers import SlicerStyleType

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
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
slicerIndex = slicers.add(pivot, "E12", "fruit")
slicer = slicers[slicerIndex]
slicer.style_type = SlicerStyleType.SLICER_STYLE_LIGHT2
# Get SlicerCache object of current slicer
slicerCache = slicer.slicer_cache
# do your business
book.save("out.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.slicers`](..)
