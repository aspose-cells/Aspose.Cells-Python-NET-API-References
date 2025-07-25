---
title: CellsHelper صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 210
url: /ar/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper صف
يوفر وظائف مساعدة.



يكشف النوع CellsHelper عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [significant_digits](/cells/python-net/ar/aspose.cells/cellshelper/significant_digits) | يحصل على عدد الأرقام المهمة ويحدده.<br/> القيمة الافتراضية هي 17.|
| [dpi](/cells/python-net/ar/aspose.cells/cellshelper/dpi) | يحصل على DPI للجهاز.|
| [startup_path](/cells/python-net/ar/aspose.cells/cellshelper/startup_path) | يحصل على مسار بدء التشغيل أو يعينه، والذي تتم الإشارة إليه بواسطة بعض مراجع الصيغ الخارجية.|
| [alt_start_path](/cells/python-net/ar/aspose.cells/cellshelper/alt_start_path) | يحصل على مسار بدء التشغيل البديل أو يعينه، والذي تتم الإشارة إليه بواسطة بعض مراجع الصيغ الخارجية.|
| [library_path](/cells/python-net/ar/aspose.cells/cellshelper/library_path) |يحصل على مسار المكتبة أو يعينه والذي تتم الإشارة إليه بواسطة بعض مراجع الصيغ الخارجية.|
| [custom_implementation_factory](/cells/python-net/ar/aspose.cells/cellshelper/custom_implementation_factory) | يحصل على المصنع أو يعينه لإنشاء مثيلات ذات تنفيذ خاص.|
| [is_cloud_platform](/cells/python-net/ar/aspose.cells/cellshelper/is_cloud_platform) | يرجى تعيين هذه الخاصية على True عند التشغيل على منصة سحابية، مثل: Azure، وAWSLambda، وما إلى ذلك،|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/ar/aspose.cells/cellshelper/create_safe_sheet_name/#str) | التحقق من اسم الورقة المقدمة وإنشاء اسم صالح عند الحاجة إليه.<br/>إذا كان اسم الورقة المقدمة يتوافق مع قواعد اسم ورقة Excel، فقم بإرجاعها.<br/>وإلا سيتم قطع السلسلة إذا تجاوز الطول الحد الأقصى<br/> وسيتم استبدال الأحرف غير الصالحة بـ ' '، ثم إرجاع قيمة السلسلة المعاد بناؤها.|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/ar/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | التحقق من اسم الورقة المقدمة وإنشاء اسم صالح عند الحاجة إليه.<br/>إذا كان اسم الورقة المقدمة يتوافق مع قواعد اسم ورقة Excel، فقم بإرجاعها.<br/>وإلا سيتم قطع السلسلة إذا تجاوز الطول الحد الأقصى<br/> وسيتم استبدال الأحرف غير الصالحة بالحرف المحدد، ثم إرجاع قيمة السلسلة المعاد بناؤها.|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/ar/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) | احصل على عرض النص بوحدة النقاط.|
| [`get_version()`](/cells/python-net/ar/aspose.cells/cellshelper/get_version/#) | احصل على النسخة الإصدارية.|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/ar/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | يحصل على فهرس الصفوف والأعمدة في الخلايا وفقًا لاسمها.|
| [`cell_index_to_name(, row, column)`](/cells/python-net/ar/aspose.cells/cellshelper/cell_index_to_name/#int-int) | يحصل على اسم الخلية وفقًا لمؤشرات الصفوف والأعمدة الخاصة بها.|
| [`column_index_to_name(, column)`](/cells/python-net/ar/aspose.cells/cellshelper/column_index_to_name/#int) | يحصل على اسم العمود وفقًا لمؤشر العمود.|
| [`column_name_to_index(, column_name)`](/cells/python-net/ar/aspose.cells/cellshelper/column_name_to_index/#str) | يحصل على فهرس العمود وفقًا لاسم العمود.|
| [`row_index_to_name(, row)`](/cells/python-net/ar/aspose.cells/cellshelper/row_index_to_name/#int) | يحصل على اسم الصف وفقًا لمؤشر الصف.|
| [`row_name_to_index(, row_name)`](/cells/python-net/ar/aspose.cells/cellshelper/row_name_to_index/#str) | يحصل على مؤشر الصف وفقًا لاسم الصف.|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/ar/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | تحويل صيغة r1c1 الخاصة بالخلية إلى صيغة A1.|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/ar/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |تحويل صيغة A1 الخاصة بالخلية إلى الصيغة r1c1.|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/ar/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | تحويل القيمة المزدوجة إلى قيمة التاريخ والوقت.|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/ar/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) | تحويل التاريخ والوقت إلى قيمة مضاعفة.|
| [`get_used_colors(, workbook)`](/cells/python-net/ar/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) | يحصل على كافة الألوان المستخدمة في المصنف.|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/ar/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) | إضافة وظيفة إضافية.|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/ar/aspose.cells/cellshelper/merge_files/#list-str-str) | دمج بعض ملفات XLS الكبيرة في ملف XLS.|
| [`get_cache_folder()`](/cells/python-net/ar/aspose.cells/cellshelper/get_cache_folder/#) | يحصل على المجلد للملفات المؤقتة التي يمكن استخدامها كذاكرة تخزين مؤقتة للبيانات.|
| [`set_cache_folder(, cache)`](/cells/python-net/ar/aspose.cells/cellshelper/set_cache_folder/#str) | تعيين المجلد للملفات المؤقتة التي يمكن استخدامها كذاكرة تخزين مؤقتة للبيانات.|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/ar/aspose.cells/cellshelper/need_quote_in_formula/#str) | يشير إلى ما إذا كان يجب وضع اسم الورقة بين علامتي اقتباس مفردتين|
| [`init_for_dot_net_core()`](/cells/python-net/ar/aspose.cells/cellshelper/init_for_dot_net_core/#) | قم بإجراء التهيئة لبرنامج .NetCore.<br/> نقترح عليك استدعاء هذه الطريقة لجميع تهيئة .NetCore أولاً.<br/>على سبيل المثال:<br/>CellsHelper.InitForDotNetCore();<br/> مصنف wb = مصنف جديد();|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
