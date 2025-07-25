---
title: ExportTableOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 560
url: /ar/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions صف
يمثل كافة خيارات جدول التصدير.



يكشف النوع ExportTableOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/exporttableoptions/__init__/#) | إنشاء مثيل جديد لـ ExportTableOptions|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [export_column_name](/cells/python-net/ar/aspose.cells/exporttableoptions/export_column_name) | يشير إلى ما إذا كانت البيانات الموجودة في الصف الأول يتم تصديرها إلى اسم العمود في جدول البيانات.<br/> القيمة الافتراضية هي false.|
| [skip_error_value](/cells/python-net/ar/aspose.cells/exporttableoptions/skip_error_value) | يشير إلى ما إذا كان يتم تخطي قيمة غير صالحة للعمود.<br/> على سبيل المثال، إذا كان نوع العمود عشريًا، فإن القيمة أكبر من عشري.MaxValue<br/>وإذا كانت هذه الخاصية صحيحة، فلن نقوم بطرح استثناء مرة أخرى.<br/> القيمة الافتراضية هي false.|
| [plot_visible_cells](/cells/python-net/ar/aspose.cells/exporttableoptions/plot_visible_cells) | يتم تصدير الخلايا المرئية فقط.|
| [plot_visible_rows](/cells/python-net/ar/aspose.cells/exporttableoptions/plot_visible_rows) | يتم تصدير الصفوف المرئية فقط.|
| [plot_visible_columns](/cells/python-net/ar/aspose.cells/exporttableoptions/plot_visible_columns) | يتم تصدير الأعمدة المرئية فقط.|
| [export_as_string](/cells/python-net/ar/aspose.cells/exporttableoptions/export_as_string) | يقوم بتصدير قيمة السلسلة الخاصة بالخلايا إلى جدول البيانات.|
| [export_as_html_string](/cells/python-net/ar/aspose.cells/exporttableoptions/export_as_html_string) | يقوم بتصدير قيمة سلسلة HTML الخاصة بالخلايا إلى جدول البيانات.|
| [format_strategy](/cells/python-net/ar/aspose.cells/exporttableoptions/format_strategy) | يحصل على استراتيجية التنسيق ويقوم بتعيينها عند تصدير القيمة كقيمة سلسلة.|
| [check_mixed_value_type](/cells/python-net/ar/aspose.cells/exporttableoptions/check_mixed_value_type) | خطأ، Aspose.Cells سوف يقوم بتعيين نوع DataColumn حسب نوع القيمة للصف الأول للأداء.<br/> صحيح، Aspose.Cells سوف يتحقق ما إذا كان نوع القيمة في العمود مختلطًا قبل تعيين نوع DataColumn<br/> ويتم خلط أنواع القيم، وسيكون نوع DataColumn عبارة عن سلسلة.|
| [allow_db_null](/cells/python-net/ar/aspose.cells/exporttableoptions/allow_db_null) |تشير هذه القيمة إلى ما إذا كان يُسمح باستخدام DBNulls في هذا الجدول.|
| [is_vertical](/cells/python-net/ar/aspose.cells/exporttableoptions/is_vertical) | صحيح إذا كان الصف في ملف المصنف يمثل صفًا في جدول البيانات. خطأ إذا كان العمود في ملف المصنف يمثل صفًا في جدول البيانات.|
| [indexes](/cells/python-net/ar/aspose.cells/exporttableoptions/indexes) | فهرس الأعمدة/الصفوف التي يجب تصديرها.|
| [rename_strategy](/cells/python-net/ar/aspose.cells/exporttableoptions/rename_strategy) | استراتيجية لتكرار أسماء الأعمدة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`preprocess_exported_value(self, cell_row, cell_column, value)`](/cells/python-net/ar/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.cellvalue) | قم بمعالجة قيمة الخلية الحالية التي سيتم تصديرها مسبقًا.|



###  ملاحظات

إذا كانت هناك بعض المتطلبات الخاصة بشأن التصدير، مثل تجاهل قيم الخطأ، فيمكن للمستخدم توسيع هذه الفئة
لاستبدال واجهات برمجة التطبيقات المقابلة لتحقيق الهدف.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
