---
title: Name صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1000
url: /ar/aspose.cells/name/
is_root: false
---
##  Name صف
يمثل اسمًا محددًا لمجموعة من الخلايا.



يكشف النوع Name عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [comment](/cells/python-net/ar/aspose.cells/name/comment) | يحصل على تعليق الاسم ويضبطه.<br/> ينطبق فقط على إصدارات Excel 2007 أو الإصدارات الأحدث.|
| [text](/cells/python-net/ar/aspose.cells/name/text) | يحصل على نص اسم الكائن.|
| [full_text](/cells/python-net/ar/aspose.cells/name/full_text) | يحصل على اسم النص الكامل للكائن مع إعداد النطاق.|
| [refers_to](/cells/python-net/ar/aspose.cells/name/refers_to) | يقوم بإرجاع أو تعيين الصيغة التي تم تعريف الاسم للإشارة إليها، بدءًا بعلامة المساواة.|
| [r1c1_refers_to](/cells/python-net/ar/aspose.cells/name/r1c1_refers_to) |يحصل على أو يعين مرجع R1C1 الخاص بـ [`Name`](/cells/python-net/ar/aspose.cells/name).|
| [is_referred](/cells/python-net/ar/aspose.cells/name/is_referred) | يشير إلى ما إذا كان يتم الإشارة إلى هذا الاسم بواسطة صيغ أخرى.|
| [is_visible](/cells/python-net/ar/aspose.cells/name/is_visible) | يشير إلى ما إذا كان الاسم مرئيًا أم لا.|
| [sheet_index](/cells/python-net/ar/aspose.cells/name/sheet_index) | يشير إلى أن هذا الاسم ينتمي إلى المصنف أو ورقة العمل.<br/> 0 = الاسم العالمي، وإلا يتم الفهرسة إلى ورقة (على أساس واحد)|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_refers_to(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/name/get_refers_to/#bool-bool) | احصل على مرجع هذا الاسم.|
| [`get_refers_to(self, is_r1c1, is_local, row, column)`](/cells/python-net/ar/aspose.cells/name/get_refers_to/#bool-bool-int-int) | احصل على مرجع هذا الاسم استنادًا إلى الخلية المحددة.|
| [`get_ranges(self)`](/cells/python-net/ar/aspose.cells/name/get_ranges/#) | يحصل على جميع النطاقات المشار إليها بهذا الاسم.|
| [`get_ranges(self, recalculate)`](/cells/python-net/ar/aspose.cells/name/get_ranges/#bool) | يحصل على جميع النطاقات المشار إليها بهذا الاسم.|
| [`get_range(self)`](/cells/python-net/ar/aspose.cells/name/get_range/#) | يحصل على النطاق إذا كان هذا الاسم يشير إلى نطاق.|
| [`get_range(self, recalculate)`](/cells/python-net/ar/aspose.cells/name/get_range/#bool) | يحصل على النطاق إذا كان هذا الاسم يشير إلى نطاق|
| [`get_range(self, sheet_index, row, column)`](/cells/python-net/ar/aspose.cells/name/get_range/#int-int-int) | يحصل على النطاق إذا كان هذا الاسم يشير إلى نطاق.<br/> إذا لم يكن مرجع هذا الاسم مطلقًا، فقد يختلف النطاق بالنسبة للخلية المختلفة.|
| [`set_refers_to(self, refers_to, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/name/set_refers_to/#str-bool-bool) | تعيين مرجع هذا الاسم.|
| [`get_referred_areas(self, recalculate)`](/cells/python-net/ar/aspose.cells/name/get_referred_areas/#bool) | يحصل على جميع المراجع المشار إليها بهذا الاسم.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating a named range
range = worksheet.cells.create_range("B4", "G14")
# Setting the name of the named range
range.name = "TestRange"
# Saving the modified Excel file in default (that is Excel 2000) format
workbook.save("output.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Name`](/cells/python-net/ar/aspose.cells/name)
