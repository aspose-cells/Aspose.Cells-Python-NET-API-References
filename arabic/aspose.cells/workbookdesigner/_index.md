---
title: WorkbookDesigner الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1600
url: /ar/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner الدرجة
لتغليف الكائن الذي يمثل جدول بيانات المصمم.



يكشف نوع WorkbookDesigner الأعضاء التالية:

###  المنشئون
| البناء| وصف|
| :- | :- |
| [WorkbookDesigner()](/cells/python-net/ar/aspose.cells/workbookdesigner/__init__/#) | يقوم بتهيئة نسخة جديدة من الفئة [WorkbookDesigner](/cells/python-net/ar/aspose.cells/workbookdesigner).|
| [WorkbookDesigner(workbook)](/cells/python-net/ar/aspose.cells/workbookdesigner/__init__/#Workbook) | يقوم بتهيئة نسخة جديدة من الفئة [WorkbookDesigner](/cells/python-net/ar/aspose.cells/workbookdesigner).|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [workbook](/cells/python-net/ar/aspose.cells/workbookdesigner/workbook) |الحصول على العنصر [WorkbookDesigner.workbook](/cells/python-net/ar/aspose.cells/workbookdesigner#workbook) وتعيينه.|
| [repeat_formulas_with_subtotal](/cells/python-net/ar/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | يشير إلى ما إذا كان يتم تكرار الصيغ مع صف الإجمالي الفرعي.|
| [update_empty_string_as_null](/cells/python-net/ar/aspose.cells/workbookdesigner/update_empty_string_as_null) | إذا كانت القيمة TRUE ، فسيتم إدراج Null إذا كانت القيمة "" ؛|
| [update_reference](/cells/python-net/ar/aspose.cells/workbookdesigner/update_reference) |يشير إلى ما إذا كان سيتم تحديث المراجع في أوراق العمل الأخرى.|
| [calculate_formula](/cells/python-net/ar/aspose.cells/workbookdesigner/calculate_formula) | يشير إلى ما إذا كان يجب حساب الصيغ.|
| [call_back](/cells/python-net/ar/aspose.cells/workbookdesigner/call_back) | يحصل ويعين واجهة رد معالجة سمارت ماركر.|
| [line_by_line](/cells/python-net/ar/aspose.cells/workbookdesigner/line_by_line) | يشير إلى ما إذا كانت معالجة العلامة الذكية سطرًا بسطر.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_data_source(data_source, cells_data_table)](/cells/python-net/ar/aspose.cells/workbookdesigner/set_data_source/#str-ICellsDataTable) | يحدد مصدر البيانات لكائن [ICellsDataTable](/cells/python-net/ar/aspose.cells/icellsdatatable).|
| [set_data_source(variable, data)](/cells/python-net/ar/aspose.cells/workbookdesigner/set_data_source/#str-any) | يضبط ربط البيانات بمتغير.|
| [process()](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#) | يعالج العلامات الذكية ويملأ قيم مصدر البيانات.|
| [process(is_preserved)](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#bool) | يعالج العلامات الذكية ويملأ قيم مصدر البيانات.|
| [process(sheet_index, is_preserved)](/cells/python-net/ar/aspose.cells/workbookdesigner/process/#int-bool) | يعالج العلامات الذكية ويملأ قيم مصدر البيانات.|
| [clear_data_source()](/cells/python-net/ar/aspose.cells/workbookdesigner/clear_data_source/#) | يمسح كل مصادر البيانات.|
| [get_smart_markers()](/cells/python-net/ar/aspose.cells/workbookdesigner/get_smart_markers/#) | إرجاع مجموعة من العلامات الذكية في جدول بيانات.|



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
* وحدة [aspose.cells](..)
* فئة [ICellsDataTable](/cells/python-net/ar/aspose.cells/icellsdatatable)
* فئة [WorkbookDesigner](/cells/python-net/ar/aspose.cells/workbookdesigner)
