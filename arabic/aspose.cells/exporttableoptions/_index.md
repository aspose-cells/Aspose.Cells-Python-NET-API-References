---
title: ExportTableOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 580
url: /ar/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions صف
يمثل جميع خيارات جدول التصدير.



يكشف النوع ExportTableOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/exporttableoptions/__init__/#) | إنشاء مثيل جديد لـ ExportTableOptions|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [export_column_name](/cells/python-net/ar/aspose.cells/exporttableoptions/export_column_name) | الإشارة إلى ما إذا كان سيتم تصدير البيانات الموجودة في الصف الأول إلى اسم عمود DataTable.<br/> القيمة الافتراضية هي كاذبة.|
| [skip_error_value](/cells/python-net/ar/aspose.cells/exporttableoptions/skip_error_value) | يشير إلى ما إذا كان تخطي قيمة غير صالحة للعمود.<br/> على سبيل المثال، إذا كان نوع العمود عشريًا، فستكون القيمة أكبر من decimal.MaxValue<br/>وهذه الخاصية صحيحة، ولن نطرح استثناءً مرة أخرى.<br/> القيمة الافتراضية هي كاذبة.|
| [plot_visible_cells](/cells/python-net/ar/aspose.cells/exporttableoptions/plot_visible_cells) | تصدير الخلايا المرئية فقط.|
| [plot_visible_rows](/cells/python-net/ar/aspose.cells/exporttableoptions/plot_visible_rows) | تصدير الصفوف المرئية فقط.|
| [plot_visible_columns](/cells/python-net/ar/aspose.cells/exporttableoptions/plot_visible_columns) | تصدير الأعمدة المرئية فقط.|
| [export_as_string](/cells/python-net/ar/aspose.cells/exporttableoptions/export_as_string) | تصدير قيمة سلسلة الخلايا إلى DataTable.|
| [export_as_html_string](/cells/python-net/ar/aspose.cells/exporttableoptions/export_as_html_string) | تصدير قيمة سلسلة html للخلايا إلى DataTable.|
| [format_strategy](/cells/python-net/ar/aspose.cells/exporttableoptions/format_strategy) | الحصول على استراتيجية التنسيق وتعيينها عند تصدير القيمة كقيمة سلسلة.|
| [check_mixed_value_type](/cells/python-net/ar/aspose.cells/exporttableoptions/check_mixed_value_type) | خطأ، Aspose.Cells سيقوم بتعيين نوع DataColumn حسب نوع قيمة الصف الأول للأداء.<br/> صحيح، Aspose.Cells سيتحقق مما إذا كان نوع القيمة في العمود مختلطًا قبل تعيين نوع DataColumn<br/>ونوع القيمة مختلط، وسيكون نوع DataColumn عبارة عن سلسلة.|
| [allow_db_null](/cells/python-net/ar/aspose.cells/exporttableoptions/allow_db_null) | تشير هذه القيمة إلى ما إذا كان DBNulls مسموحًا به في هذا الجدول.|
| [is_vertical](/cells/python-net/ar/aspose.cells/exporttableoptions/is_vertical) | صحيح إذا كان الصف الموجود في ملف المصنف يمثل صفًا في DataTable. خطأ إذا كان العمود الموجود في ملف المصنف يمثل صفًا في DataTable.|
| [indexes](/cells/python-net/ar/aspose.cells/exporttableoptions/indexes) | فهارس الأعمدة/الصفوف التي يجب تصديرها.|
| [rename_strategy](/cells/python-net/ar/aspose.cells/exporttableoptions/rename_strategy) | استراتيجية لأسماء الأعمدة المكررة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [preprocess_exported_value](/cells/python-net/ar/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.CellValue) | المعالجة المسبقة لقيمة الخلية الحالية المراد تصديرها.|



###  ملاحظات

إذا كانت هناك بعض المتطلبات الخاصة حول التصدير، مثل تجاهل قيم الخطأ، فيمكن للمستخدم توسيع هذه الفئة
للكتابة فوق واجهات برمجة التطبيقات المقابلة لتحقيق الهدف.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
