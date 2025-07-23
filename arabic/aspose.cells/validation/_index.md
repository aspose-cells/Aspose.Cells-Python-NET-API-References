---
title: Validation صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1520
url: /ar/aspose.cells/validation/
is_root: false
---
##  Validation صف
يمثل إعدادات التحقق من صحة البيانات.



يكشف النوع Validation عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [operator](/cells/python-net/ar/aspose.cells/validation/operator) | يمثل المشغل للتحقق من صحة البيانات.|
| [alert_style](/cells/python-net/ar/aspose.cells/validation/alert_style) | يمثل نمط تنبيه التحقق.|
| [type](/cells/python-net/ar/aspose.cells/validation/type) | يمثل نوع التحقق من صحة البيانات.|
| [input_message](/cells/python-net/ar/aspose.cells/validation/input_message) | يمثل رسالة إدخال التحقق من صحة البيانات.|
| [input_title](/cells/python-net/ar/aspose.cells/validation/input_title) | يمثل عنوان مربع حوار إدخال التحقق من صحة البيانات.|
| [error_message](/cells/python-net/ar/aspose.cells/validation/error_message) | يمثل رسالة خطأ التحقق من صحة البيانات.|
| [error_title](/cells/python-net/ar/aspose.cells/validation/error_title) | يمثل عنوان مربع حوار خطأ التحقق من صحة البيانات.|
| [show_input](/cells/python-net/ar/aspose.cells/validation/show_input) | يشير إلى ما إذا كان سيتم عرض رسالة إدخال التحقق من صحة البيانات كلما حدد المستخدم خلية في نطاق التحقق من صحة البيانات.|
| [show_error](/cells/python-net/ar/aspose.cells/validation/show_error) | يشير إلى ما إذا كانت رسالة خطأ التحقق من صحة البيانات ستظهر عندما يقوم المستخدم بإدخال بيانات غير صالحة.|
| [ignore_blank](/cells/python-net/ar/aspose.cells/validation/ignore_blank) |يشير إلى ما إذا كانت القيم الفارغة مسموح بها من خلال التحقق من صحة نطاق البيانات.|
| [formula1](/cells/python-net/ar/aspose.cells/validation/formula1) | يمثل القيمة أو التعبير المرتبط بالتحقق من صحة البيانات.|
| [formula2](/cells/python-net/ar/aspose.cells/validation/formula2) | يمثل القيمة أو التعبير المرتبط بالتحقق من صحة البيانات.|
| [value1](/cells/python-net/ar/aspose.cells/validation/value1) | يمثل القيمة الأولى المرتبطة بالتحقق من صحة البيانات.|
| [value2](/cells/python-net/ar/aspose.cells/validation/value2) | يمثل القيمة الثانية المرتبطة بالتحقق من صحة البيانات.|
| [in_cell_drop_down](/cells/python-net/ar/aspose.cells/validation/in_cell_drop_down) | يشير إلى ما إذا كان التحقق من صحة البيانات يعرض قائمة منسدلة تحتوي على قيم مقبولة.|
| [areas](/cells/python-net/ar/aspose.cells/validation/areas) | يحصل على كل [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) التي تحتوي على إعدادات التحقق من صحة البيانات.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/validation/get_formula1/#bool-bool) | يحصل على القيمة أو التعبير المرتبط بهذا التحقق.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/ar/aspose.cells/validation/get_formula1/#bool-bool-int-int) | يحصل على القيمة أو التعبير المرتبط بهذا التحقق لخلية معينة.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/validation/get_formula2/#bool-bool) | يحصل على القيمة أو التعبير المرتبط بهذا التحقق.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/ar/aspose.cells/validation/get_formula2/#bool-bool-int-int) | يحصل على القيمة أو التعبير المرتبط بهذا التحقق لخلية معينة.|
| [`add_area(self, cell_area)`](/cells/python-net/ar/aspose.cells/validation/add_area/#aspose.cells.cellarea) | يتم تطبيق التحقق على المنطقة.|
| [`add_area(self, cell_area, check_intersection, check_edge)`](/cells/python-net/ar/aspose.cells/validation/add_area/#aspose.cells.cellarea-bool-bool) | يتم تطبيق التحقق على المنطقة.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/validation/set_formula1/#str-bool-bool) | تعيين القيمة أو التعبير المرتبط بهذا التحقق.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/validation/set_formula2/#str-bool-bool) | تعيين القيمة أو التعبير المرتبط بهذا التحقق.|
| [`get_list_value(self, row, column)`](/cells/python-net/ar/aspose.cells/validation/get_list_value/#int-int) | احصل على قيمة لقائمة التحقق للخلية المحددة.|
| [`get_value(self, row, column, is_value1)`](/cells/python-net/ar/aspose.cells/validation/get_value/#int-int-bool) | احصل على قيمة التحقق من صحة الخلية المحددة.|
| [`add_areas(self, areas, check_intersection, check_edge)`](/cells/python-net/ar/aspose.cells/validation/add_areas/#list-bool-bool) | تطبيق التحقق على المناطق المحددة.|
| [`remove_area(self, cell_area)`](/cells/python-net/ar/aspose.cells/validation/remove_area/#aspose.cells.cellarea) | إزالة إعدادات التحقق في النطاق.|
| [`remove_areas(self, areas)`](/cells/python-net/ar/aspose.cells/validation/remove_areas/#list) |يزيل هذا التحقق من المناطق المحددة.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/ar/aspose.cells/validation/remove_a_cell/#int-int) | إزالة إعدادات التحقق في الخلية.|
| [`copy(self, source, copy_option)`](/cells/python-net/ar/aspose.cells/validation/copy/#aspose.cells.validation-aspose.cells.copyoptions) | التحقق من صحة النسخة.|



###  مثال

```python
from aspose.cells import CellArea, OperatorType, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.WHOLE_NUMBER
validation.operator = OperatorType.BETWEEN
validation.formula1 = "3"
validation.formula2 = "1234"

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea)
