---
title: FormatCondition صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 700
url: /ar/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition صف
يمثل شرط التنسيق الشرطي.



يكشف النوع FormatCondition عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [formula1](/cells/python-net/ar/aspose.cells/formatcondition/formula1) | يحصل على القيمة أو التعبير المرتبط بالتنسيق الشرطي ويقوم بتعيينها.|
| [formula2](/cells/python-net/ar/aspose.cells/formatcondition/formula2) | يحصل على القيمة أو التعبير المرتبط بالتنسيق الشرطي ويقوم بتعيينها.|
| [operator](/cells/python-net/ar/aspose.cells/formatcondition/operator) | يحصل على نوع مشغل التنسيق الشرطي ويقوم بتعيينه.|
| [stop_if_true](/cells/python-net/ar/aspose.cells/formatcondition/stop_if_true) |صحيح، لا يمكن تطبيق أي قواعد ذات أولوية أقل على هذه القاعدة، عندما يتم تقييم هذه القاعدة على أنها صحيحة.<br/> ينطبق فقط على Excel 2007؛|
| [priority](/cells/python-net/ar/aspose.cells/formatcondition/priority) | أولوية قاعدة التنسيق الشرطي هذه. تُستخدم هذه القيمة لتحديد<br/>يجب تقييم التنسيق وعرضه. القيم الرقمية الأقل لها أولوية أعلى من<br/> القيم الرقمية الأعلى، حيث أن '1' هي ذات الأولوية الأعلى.|
| [style](/cells/python-net/ar/aspose.cells/formatcondition/style) | يحصل على نمط نطاقات الخلايا المنسقة الشرطية أو يعينه.|
| [type](/cells/python-net/ar/aspose.cells/formatcondition/type) | يحصل على نوع التنسيق الشرطي ويحدد ما إذا كان مناسبًا أم لا.|
| [icon_set](/cells/python-net/ar/aspose.cells/formatcondition/icon_set) | احصل على مثيل "IconSet" للتنسيق الشرطي.<br/>IconSetType الافتراضي للمثيل هو TrafficLights31.<br/> صالح فقط لنوع = IconSet.|
| [data_bar](/cells/python-net/ar/aspose.cells/formatcondition/data_bar) | احصل على مثيل "DataBar" للتنسيق الشرطي.<br/>اللون الافتراضي للمثيل هو اللون الأزرق.<br/> صالح فقط للنوع DataBar.|
| [color_scale](/cells/python-net/ar/aspose.cells/formatcondition/color_scale) | احصل على مثيل "ColorScale" للتنسيق الشرطي.<br/>الحالة الافتراضية هي "green-yellow-red" 3ColorScale .<br/> صالح فقط لنوع = ColorScale.|
| [top10](/cells/python-net/ar/aspose.cells/formatcondition/top10) | احصل على مثيل "Top10" للتنسيق الشرطي.<br/>تسلط قاعدة المثيل الافتراضي الضوء على الخلايا التي<br/>القيم تقع ضمن الفئة العشرة الأولى.<br/> صالح فقط للنوع Top10.|
| [above_average](/cells/python-net/ar/aspose.cells/formatcondition/above_average) |احصل على مثيل "AboveAverage" للتنسيق الشرطي.<br/> تسلط قاعدة المثيل الافتراضية الضوء على الخلايا التي<br/>أعلى من المتوسط لجميع القيم في النطاق.<br/> صالح فقط للنوع = AboveAverage.|
| [text](/cells/python-net/ar/aspose.cells/formatcondition/text) | قيمة النص في قاعدة التنسيق الشرطي "يحتوي النص على".<br/>صالح فقط لنوع = containsText، notContainsText، startsWith و endsWith.<br/> القيمة الافتراضية هي null.|
| [time_period](/cells/python-net/ar/aspose.cells/formatcondition/time_period) | الفترة الزمنية المعمول بها في قاعدة التنسيق الشرطي "تاريخ وقوع...".<br/>صالح فقط لنوع = timePeriod.<br/> القيمة الافتراضية هي TimePeriodType.Today.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/formatcondition/get_formula1/#bool-bool) | يحصل على القيمة أو التعبير المرتبط بشرط التنسيق هذا.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/ar/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | يحصل على قيمة أو تعبير التنسيق الشرطي للخلية.|
| [`get_formula1(self, row, column)`](/cells/python-net/ar/aspose.cells/formatcondition/get_formula1/#int-int) | يحصل على صيغة التنسيق الشرطي للخلية.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/formatcondition/get_formula2/#bool-bool) | يحصل على القيمة أو التعبير المرتبط بشرط التنسيق هذا.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/ar/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | يحصل على قيمة أو تعبير التنسيق الشرطي للخلية.|
| [`get_formula2(self, row, column)`](/cells/python-net/ar/aspose.cells/formatcondition/get_formula2/#int-int) | يحصل على صيغة التنسيق الشرطي للخلية.|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | تعيين القيمة أو التعبير المرتبط بشرط التنسيق هذا.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | تعيين القيمة أو التعبير المرتبط بشرط التنسيق هذا.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | تعيين القيمة أو التعبير المرتبط بشرط التنسيق هذا.|



###  مثال

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
