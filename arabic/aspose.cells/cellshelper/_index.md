---
title: CellsHelper صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 240
url: /ar/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper صف
يوفر وظائف المساعدة.



يكشف النوع CellsHelper عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [significant_digits](/cells/python-net/ar/aspose.cells/cellshelper/significant_digits) | الحصول على عدد الأرقام المهمة وتعيينها.<br/> القيمة الافتراضية هي 17.|
| [dpi](/cells/python-net/ar/aspose.cells/cellshelper/dpi) | يحصل على DPI للجهاز.|
| [startup_path](/cells/python-net/ar/aspose.cells/cellshelper/startup_path) | الحصول على مسار بدء التشغيل أو تعيينه، والذي تتم الإشارة إليه بواسطة بعض مراجع الصيغ الخارجية.|
| [alt_start_path](/cells/python-net/ar/aspose.cells/cellshelper/alt_start_path) | الحصول على مسار بدء التشغيل البديل أو تعيينه، والذي تتم الإشارة إليه بواسطة بعض مراجع الصيغ الخارجية.|
| [library_path](/cells/python-net/ar/aspose.cells/cellshelper/library_path) | الحصول على أو تعيين مسار المكتبة الذي تتم الإشارة إليه بواسطة بعض مراجع الصيغ الخارجية.|
| [custom_implementation_factory](/cells/python-net/ar/aspose.cells/cellshelper/custom_implementation_factory) | الحصول على المصنع أو تعيينه لإنشاء مثيلات ذات تنفيذ خاص.|
| [is_cloud_platform](/cells/python-net/ar/aspose.cells/cellshelper/is_cloud_platform) | يرجى تعيين هذه الخاصية على "صحيح" عند التشغيل على منصة سحابية، مثل: Azure، وAWSLambda، وما إلى ذلك،|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [create_safe_sheet_name](/cells/python-net/ar/aspose.cells/cellshelper/create_safe_sheet_name/#str) | يتحقق من اسم الورقة المعطاة وينشئ اسمًا صالحًا عند الحاجة.<br/>إذا كان اسم الورقة المحدد يتوافق مع قواعد اسم ورقة Excel، فقم بإعادته.<br/>وإلا سيتم اقتطاع السلسلة إذا تجاوز الطول الحد الأقصى<br/>وسيتم استبدال الأحرف غير الصالحة بـ ' '، ثم يتم إرجاع قيمة السلسلة المعاد إنشاؤها.|
| [create_safe_sheet_name](/cells/python-net/ar/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | يتحقق من اسم الورقة المعطاة وينشئ اسمًا صالحًا عند الحاجة.<br/>إذا كان اسم الورقة المحدد يتوافق مع قواعد اسم ورقة Excel، فقم بإعادته.<br/>وإلا سيتم اقتطاع السلسلة إذا تجاوز الطول الحد الأقصى<br/> وسيتم استبدال الأحرف غير الصالحة بحرف معين، ثم إرجاع قيمة السلسلة المعاد بناؤها.|
| [get_text_width](/cells/python-net/ar/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.Font-float) | الحصول على عرض النص بوحدة النقاط.|
| [get_version](/cells/python-net/ar/aspose.cells/cellshelper/get_version/#) | الحصول على نسخة الإصدار.|
| [cell_name_to_index](/cells/python-net/ar/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | يحصل على فهارس صفوف وأعمدة الخلية وفقًا لاسمها.|
| [cell_index_to_name](/cells/python-net/ar/aspose.cells/cellshelper/cell_index_to_name/#int-int) | يحصل على اسم الخلية وفقا لفهارس الصفوف والأعمدة الخاصة بها.|
| [column_index_to_name](/cells/python-net/ar/aspose.cells/cellshelper/column_index_to_name/#int) | يحصل على اسم العمود وفقا لفهرس العمود.|
| [column_name_to_index](/cells/python-net/ar/aspose.cells/cellshelper/column_name_to_index/#str) | يحصل على فهرس العمود وفقًا لاسم العمود.|
| [row_index_to_name](/cells/python-net/ar/aspose.cells/cellshelper/row_index_to_name/#int) | يحصل على اسم الصف وفقا لفهرس الصف.|
| [row_name_to_index](/cells/python-net/ar/aspose.cells/cellshelper/row_name_to_index/#str) | الحصول على فهرس الصف وفقًا لاسم الصف.|
| [convert_r1c1_formula_to_a1](/cells/python-net/ar/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | تحويل صيغة r1c1 للخلية إلى صيغة A1.|
| [convert_a1_formula_to_r1c1](/cells/python-net/ar/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) | تحويل صيغة A1 للخلية إلى صيغة r1c1.|
| [get_date_time_from_double](/cells/python-net/ar/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | تحويل القيمة المزدوجة إلى قيمة التاريخ والوقت.|
| [get_double_from_date_time](/cells/python-net/ar/aspose.cells/cellshelper/get_double_from_date_time/#DateTime-bool) | تحويل التاريخ والوقت إلى قيمة مضاعفة.|
| [get_used_colors](/cells/python-net/ar/aspose.cells/cellshelper/get_used_colors/#aspose.cells.Workbook) | الحصول على كافة الألوان المستخدمة في المصنف.|
| [add_add_in_function](/cells/python-net/ar/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.ParameterType) | إضافة وظيفة الوظيفة الإضافية.|
| [merge_files](/cells/python-net/ar/aspose.cells/cellshelper/merge_files/#list-str-str) | دمج بعض ملفات xls الكبيرة في ملف xls.|
| [need_quote_in_formula](/cells/python-net/ar/aspose.cells/cellshelper/need_quote_in_formula/#str) |يشير إلى ما إذا كان يجب تضمين اسم الورقة بين علامتي اقتباس مفردتين|
| [init_for_dot_net_core](/cells/python-net/ar/aspose.cells/cellshelper/init_for_dot_net_core/#) | قم بإجراء التهيئة لبرنامج .NetCore.<br/> نقترح عليك استدعاء هذه الطريقة لجميع عمليات تهيئة .NetCore أولاً.<br/>على سبيل المثال:<br/>CellsHelper.InitForDotNetCore();<br/> Workbook wb = new Workbook();|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
