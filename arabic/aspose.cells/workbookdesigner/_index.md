---
title: WorkbookDesigner صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1670
url: /ar/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner صف
يقوم بتغليف الكائن الذي يمثل جدول بيانات المصمم.



يكشف النوع WorkbookDesigner عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/workbookdesigner/__init__/#) | تهيئة مثيل جديد للفئة [`WorkbookDesigner`](/cells/python-net/ar/aspose.cells/workbookdesigner).|
| [__init__](/cells/python-net/ar/aspose.cells/workbookdesigner/__init__/#aspose.cells.Workbook) | تهيئة مثيل جديد للفئة [`WorkbookDesigner`](/cells/python-net/ar/aspose.cells/workbookdesigner).|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [workbook](/cells/python-net/ar/aspose.cells/workbookdesigner/workbook) | الحصول على الكائن [`WorkbookDesigner.workbook`](/cells/python-net/ar/aspose.cells/workbookdesigner#workbook) وتعيينه.|
| [repeat_formulas_with_subtotal](/cells/python-net/ar/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | يشير إلى ما إذا كانت الصيغ مكررة مع صف الإجمالي الفرعي.|
| [update_empty_string_as_null](/cells/python-net/ar/aspose.cells/workbookdesigner/update_empty_string_as_null) | إذا كانت القيمة TRUE، فسيتم إدراج Null إذا كانت القيمة هي ""؛|
| [update_reference](/cells/python-net/ar/aspose.cells/workbookdesigner/update_reference) | يشير إلى ما إذا كان سيتم تحديث المراجع في أوراق العمل الأخرى.|
| [calculate_formula](/cells/python-net/ar/aspose.cells/workbookdesigner/calculate_formula) | الإشارة إلى ما إذا كان ينبغي حساب الصيغ.|
| [call_back](/cells/python-net/ar/aspose.cells/workbookdesigner/call_back) | الحصول على واجهة رد الاتصال الخاصة بمعالجة العلامة الذكية وتعيينها.|
| [line_by_line](/cells/python-net/ar/aspose.cells/workbookdesigner/line_by_line) | يشير إلى ما إذا كان سيتم معالجة العلامة الذكية سطرًا تلو الآخر.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_data_source](/cells/python-net/ar/aspose.cells/workbookdesigner/set_data_source/#str-aspose.cells.ICellsDataTable) | يعين مصدر البيانات لكائن [`ICellsDataTable`](/cells/python-net/ar/aspose.cells/icellsdatatable).|
| [set_data_source](/cells/python-net/ar/aspose.cells/workbookdesigner/set_data_source/#str-any) | يضبط ربط البيانات بمتغير.|
| [process](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#) |يعالج العلامات الذكية ويملأ قيم مصدر البيانات.|
| [process](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#bool) |يعالج العلامات الذكية ويملأ قيم مصدر البيانات.|
| [process](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#int-bool) |يعالج العلامات الذكية ويملأ قيم مصدر البيانات.|
| [clear_data_source](/cells/python-net/ar/aspose.cells/workbookdesigner/clear_data_source/#) | مسح كافة مصادر البيانات.|
| [set_json_data_source](/cells/python-net/ar/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [get_smart_markers](/cells/python-net/ar/aspose.cells/workbookdesigner/get_smart_markers/#) | إرجاع مجموعة من العلامات الذكية في جدول بيانات.|



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
* فئة [`ICellsDataTable`](/cells/python-net/ar/aspose.cells/icellsdatatable)
* فئة [`WorkbookDesigner`](/cells/python-net/ar/aspose.cells/workbookdesigner)
