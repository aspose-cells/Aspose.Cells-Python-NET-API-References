---
title: WorkbookDesigner صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1580
url: /ar/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner صف
يقوم بتغليف الكائن الذي يمثل جدول بيانات المصمم.



يكشف النوع WorkbookDesigner عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/workbookdesigner/__init__/#) | يقوم بتهيئة مثيل جديد للفئة [`WorkbookDesigner`](/cells/python-net/ar/aspose.cells/workbookdesigner).|
| [`__init__(self, workbook)`](/cells/python-net/ar/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) | يقوم بتهيئة مثيل جديد للفئة [`WorkbookDesigner`](/cells/python-net/ar/aspose.cells/workbookdesigner).|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [workbook](/cells/python-net/ar/aspose.cells/workbookdesigner/workbook) | يحصل على الكائن [`WorkbookDesigner.workbook`](/cells/python-net/ar/aspose.cells/workbookdesigner#workbook) ويقوم بتعيينه.|
| [repeat_formulas_with_subtotal](/cells/python-net/ar/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | يشير إلى ما إذا كان يتم تكرار الصيغ مع صف المجموع الفرعي.|
| [update_empty_string_as_null](/cells/python-net/ar/aspose.cells/workbookdesigner/update_empty_string_as_null) |إذا كانت القيمة TRUE، فسيتم إدراج Null إذا كانت القيمة ""؛|
| [update_reference](/cells/python-net/ar/aspose.cells/workbookdesigner/update_reference) | يشير إلى ما إذا كان سيتم تحديث المراجع في أوراق العمل الأخرى.|
| [calculate_formula](/cells/python-net/ar/aspose.cells/workbookdesigner/calculate_formula) | يشير إلى ما إذا كان ينبغي حساب الصيغ.|
| [line_by_line](/cells/python-net/ar/aspose.cells/workbookdesigner/line_by_line) | يشير إلى ما إذا كان يتم معالجة العلامة الذكية سطرًا بسطر.|
| [contains_variables](/cells/python-net/ar/aspose.cells/workbookdesigner/contains_variables) | يشير إلى ما إذا كانت ورقة العمل الأولى تحتوي على متغيرات مخصصة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/ar/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/ar/aspose.cells/workbookdesigner/set_data_source/#str-any) | تعيين ربط البيانات إلى متغير.|
| [`process(self, range, is_preserved)`](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) | معالجة العلامات الذكية وملء قيم مصدر البيانات.|
| [`process(self)`](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#) | معالجة العلامات الذكية وملء قيم مصدر البيانات.|
| [`process(self, is_preserved)`](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#bool) | معالجة العلامات الذكية وملء قيم مصدر البيانات.|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#int-bool) | معالجة العلامات الذكية وملء قيم مصدر البيانات.|
| [`clear_data_source(self)`](/cells/python-net/ar/aspose.cells/workbookdesigner/clear_data_source/#) | مسح كافة مصادر البيانات.|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/ar/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/ar/aspose.cells/workbookdesigner/get_smart_markers/#) | إرجاع مجموعة من العلامات الذكية في جدول بيانات.|



###  مثال

```python
from aspose.cells import Workbook, WorkbookDesigner

# Create WorkbookDesigner object.
wd = WorkbookDesigner()
# Open the template file (which contains smart markers).
wd.workbook = Workbook("SmartMarker_Designer.xls")
# Initialize your data from data source
# DataSet ds = new DataSet();
# ...
# Set the datatable as the data source.
# wd.SetDataSource(dt);
# Process the smart markers to fill the data into the worksheets.
wd.process(True)
# Save the excel file.
wd.workbook.save("outSmartMarker_Designer.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`WorkbookDesigner`](/cells/python-net/ar/aspose.cells/workbookdesigner)
