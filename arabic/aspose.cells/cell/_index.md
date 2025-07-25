---
title: Cell صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells/cell/
is_root: false
---
##  Cell صف
يقوم بتغليف الكائن الذي يمثل خلية مصنف واحدة.



يكشف النوع Cell عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [worksheet](/cells/python-net/ar/aspose.cells/cell/worksheet) | يحصل على ورقة العمل الأصلية.|
| [date_time_value](/cells/python-net/ar/aspose.cells/cell/date_time_value) | يحصل على قيمة DateTime الموجودة في الخلية.|
| [row](/cells/python-net/ar/aspose.cells/cell/row) | يحصل على رقم الصف (على أساس الصفر) للخلية.|
| [column](/cells/python-net/ar/aspose.cells/cell/column) | يحصل على رقم العمود (على أساس الصفر) للخلية.|
| [is_formula](/cells/python-net/ar/aspose.cells/cell/is_formula) | يمثل ما إذا كانت الخلية المحددة تحتوي على صيغة.|
| [has_custom_function](/cells/python-net/ar/aspose.cells/cell/has_custom_function) |يتحقق ما إذا كانت هناك وظيفة مخصصة (وظيفة غير مدعومة) في صيغة هذه الخلية.|
| [type](/cells/python-net/ar/aspose.cells/cell/type) | يمثل نوع قيمة الخلية.|
| [name](/cells/python-net/ar/aspose.cells/cell/name) | يحصل على اسم الخلية.|
| [is_error_value](/cells/python-net/ar/aspose.cells/cell/is_error_value) | التحقق مما إذا كانت قيمة هذه الخلية خطأ.|
| [is_numeric_value](/cells/python-net/ar/aspose.cells/cell/is_numeric_value) | يشير إلى ما إذا كانت قيمة هذه الخلية رقمية (int وdouble وdatetime)|
| [string_value](/cells/python-net/ar/aspose.cells/cell/string_value) | احصل على قيمة السلسلة النصية الموجودة في الخلية. إذا كان نوع هذه الخلية سلسلة نصية، فأرجع قيمة السلسلة النصية نفسها.<br/>بالنسبة لأنواع الخلايا الأخرى، سيتم إرجاع قيمة السلسلة المنسقة (المنسقة بالنمط المحدد لهذه الخلية).<br/>قيمة الخلية المنسقة هي نفسها ما يمكنك الحصول عليه من Excel عند نسخ خلية كنص (مثل<br/> نسخ الخلية إلى محرر النصوص أو تصديرها إلى ملف csv).|
| [string_value_without_format](/cells/python-net/ar/aspose.cells/cell/string_value_without_format) | يحصل على قيمة الخلية كسلسلة بدون أي تنسيق.|
| [number_category_type](/cells/python-net/ar/aspose.cells/cell/number_category_type) | يمثل نوع الفئة لتنسيق الأرقام في هذه الخلية.|
| [display_string_value](/cells/python-net/ar/aspose.cells/cell/display_string_value) | يحصل على قيمة السلسلة المنسقة لهذه الخلية حسب نمط عرض الخلية.|
| [int_value](/cells/python-net/ar/aspose.cells/cell/int_value) | يحصل على القيمة الصحيحة الموجودة في الخلية.|
| [double_value](/cells/python-net/ar/aspose.cells/cell/double_value) | يحصل على القيمة المزدوجة الموجودة في الخلية.|
| [float_value](/cells/python-net/ar/aspose.cells/cell/float_value) | يحصل على القيمة العائمة الموجودة في الخلية.|
| [bool_value](/cells/python-net/ar/aspose.cells/cell/bool_value) | يحصل على القيمة المنطقية الموجودة في الخلية.|
| [has_custom_style](/cells/python-net/ar/aspose.cells/cell/has_custom_style) | يشير إلى ما إذا كانت هذه الخلية تحتوي على إعدادات نمط مخصصة (تختلف عن الإعدادات الافتراضية الموروثة<br/>من الصف أو العمود أو المصنف المقابل).|
| [shared_style_index](/cells/python-net/ar/aspose.cells/cell/shared_style_index) | يحصل على مؤشر النمط المشترك للخلية في مجموعة الأنماط.|
| [formula](/cells/python-net/ar/aspose.cells/cell/formula) | يحصل على صيغة [`Cell`](/cells/python-net/ar/aspose.cells/cell) أو يعينها.|
| [formula_local](/cells/python-net/ar/aspose.cells/cell/formula_local) | احصل على صيغة تنسيق اللغة المحلية للخلية.|
| [r1c1_formula](/cells/python-net/ar/aspose.cells/cell/r1c1_formula) | يحصل على صيغة R1C1 الخاصة بـ [`Cell`](/cells/python-net/ar/aspose.cells/cell) أو يعينها.|
| [contains_external_link](/cells/python-net/ar/aspose.cells/cell/contains_external_link) | يشير إلى ما إذا كانت هذه الخلية تحتوي على رابط خارجي.<br/> ينطبق فقط عندما تكون الخلية عبارة عن خلية صيغة.|
| [is_array_header](/cells/python-net/ar/aspose.cells/cell/is_array_header) | يشير إلى أن صيغة الخلية هي صيغة مصفوفة<br/> وهي الخلية الأولى للمصفوفة.|
| [is_dynamic_array_formula](/cells/python-net/ar/aspose.cells/cell/is_dynamic_array_formula) | يشير إلى ما إذا كانت صيغة الخلية عبارة عن صيغة مصفوفة ديناميكية (صحيح) أو صيغة مصفوفة قديمة (خطأ).|
| [is_array_formula](/cells/python-net/ar/aspose.cells/cell/is_array_formula) | يشير إلى ما إذا كانت صيغة الخلية عبارة عن صيغة مصفوفة.|
| [is_in_array](/cells/python-net/ar/aspose.cells/cell/is_in_array) | يشير إلى ما إذا كانت صيغة الخلية عبارة عن صيغة مصفوفة.|
| [is_shared_formula](/cells/python-net/ar/aspose.cells/cell/is_shared_formula) | يشير إلى ما إذا كانت صيغة الخلية جزءًا من الصيغة المشتركة.|
| [is_table_formula](/cells/python-net/ar/aspose.cells/cell/is_table_formula) | يشير إلى ما إذا كانت هذه الخلية جزءًا من صيغة الجدول.|
| [is_in_table](/cells/python-net/ar/aspose.cells/cell/is_in_table) | يشير إلى ما إذا كانت هذه الخلية جزءًا من صيغة الجدول.|
| [value](/cells/python-net/ar/aspose.cells/cell/value) | يحصل على/يحدد القيمة الموجودة في هذه الخلية.|
| [is_style_set](/cells/python-net/ar/aspose.cells/cell/is_style_set) | يشير إلى ما إذا كان نمط الخلية مُعيّنًا. إذا كانت القيمة "خطأ"، فهذا يعني أن تنسيق الخلية الافتراضي مُحدّد.|
| [is_merged](/cells/python-net/ar/aspose.cells/cell/is_merged) | التحقق مما إذا كانت الخلية جزءًا من نطاق مدمج أم لا.|
| [comment](/cells/python-net/ar/aspose.cells/cell/comment) |يحصل على تعليق هذه الخلية.|
| [html_string](/cells/python-net/ar/aspose.cells/cell/html_string) | يحصل على سلسلة HTML التي تحتوي على البيانات وبعض التنسيقات في هذه الخلية ويقوم بتعيينها.|
| [is_check_box_style](/cells/python-net/ar/aspose.cells/cell/is_check_box_style) | يشير إلى ما إذا كان يتم تعيين هذه الخلية كصندوق اختيار.|
| [embedded_image](/cells/python-net/ar/aspose.cells/cell/embedded_image) | يحصل على الصورة المضمنة في الخلية ويضبطها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/ar/aspose.cells/cell/put_value/#bool) | وضع قيمة منطقية في الخلية.|
| [`put_value(self, int_value)`](/cells/python-net/ar/aspose.cells/cell/put_value/#int) | وضع قيمة عددية في الخلية.|
| [`put_value(self, double_value)`](/cells/python-net/ar/aspose.cells/cell/put_value/#float) | وضع قيمة مضاعفة في الخلية.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/ar/aspose.cells/cell/put_value/#str-bool-bool) | يضع قيمة في الخلية، وإذا كان ذلك مناسبًا، فسيتم تحويل القيمة إلى نوع بيانات آخر وسيتم إعادة تعيين تنسيق رقم الخلية.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/ar/aspose.cells/cell/put_value/#str-bool) | يضع قيمة سلسلة في الخلية ويحول القيمة إلى نوع بيانات آخر إذا لزم الأمر.|
| [`put_value(self, string_value)`](/cells/python-net/ar/aspose.cells/cell/put_value/#str) | يضع قيمة سلسلة في الخلية.|
| [`put_value(self, date_time)`](/cells/python-net/ar/aspose.cells/cell/put_value/#datetime) | يضع قيمة DateTime في الخلية.|
| [`put_value(self, object_value)`](/cells/python-net/ar/aspose.cells/cell/put_value/#any) | وضع قيمة الكائن في الخلية.|
| [`get_display_style(self)`](/cells/python-net/ar/aspose.cells/cell/get_display_style/#) | يحصل على نمط العرض لهذه الخلية.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/ar/aspose.cells/cell/get_display_style/#bool) | يحصل على نمط العرض لهذه الخلية.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/ar/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | يحصل على نمط العرض لهذه الخلية.|
| [`get_style(self)`](/cells/python-net/ar/aspose.cells/cell/get_style/#) | يحصل على نمط الخلية.|
| [`get_style(self, check_borders)`](/cells/python-net/ar/aspose.cells/cell/get_style/#bool) | إذا كانت checkBorders صحيحة، فتحقق ما إذا كانت حدود الخلايا الأخرى ستؤثر على نمط هذه الخلية.|
| [`set_style(self, style)`](/cells/python-net/ar/aspose.cells/cell/set_style/#aspose.cells.style) | تعيين نمط الخلية.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/ar/aspose.cells/cell/set_style/#aspose.cells.style-bool) | تطبيق خاصية النمط المتغيرة على الخلية.|
| [`set_style(self, style, flag)`](/cells/python-net/ar/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |تطبيق نمط الخلية بناءً على العلامات.|
| [`set_formula(self, formula, value)`](/cells/python-net/ar/aspose.cells/cell/set_formula/#str-any) | قم بتعيين الصيغة وقيمة (النتيجة المحسوبة) للصيغة.|
| [`set_formula(self, formula, options)`](/cells/python-net/ar/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | قم بتعيين الصيغة وقيمة (النتيجة المحسوبة) للصيغة.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/ar/aspose.cells/cell/set_formula/#str-bool-bool-any) | تعيين الصيغة وقيمة الصيغة.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/ar/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | قم بتعيين الصيغة وقيمة (النتيجة المحسوبة) للصيغة.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | تعيين صيغة المصفوفة لمجموعة من الخلايا.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int) | تعيين صيغة المصفوفة (صيغة المصفوفة القديمة التي تم إدخالها عبر CTRL+SHIFT+ENTER في ms excel) إلى نطاق من الخلايا.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | تعيين صيغة المصفوفة لمجموعة من الخلايا.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | تعيين صيغة المصفوفة لمجموعة من الخلايا.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | تعيين صيغة لمجموعة من الخلايا.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int) | تعيين الصيغ المشتركة لمجموعة من الخلايا.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | تعيين الصيغ المشتركة لمجموعة من الخلايا.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | تعيين الصيغ المشتركة لمجموعة من الخلايا.|
| [`get_leafs(self)`](/cells/python-net/ar/aspose.cells/cell/get_leafs/#) | احصل على جميع الخلايا التي تشير إلى هذه الخلية بشكل مباشر وتحتاج إلى التحديث عند تعديل هذه الخلية.|
| [`get_leafs(self, recursive)`](/cells/python-net/ar/aspose.cells/cell/get_leafs/#bool) | احصل على جميع الخلايا التي سيتم تحديثها عند تعديل هذه الخلية.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/ar/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | تعيين صيغة المصفوفة الديناميكية وجعل الصيغة تنتشر في الخلايا المجاورة إذا كان ذلك ممكنًا.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/ar/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | تعيين صيغة المصفوفة الديناميكية وجعل الصيغة تنتشر في الخلايا المجاورة إذا كان ذلك ممكنًا.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/ar/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | تعيين صيغة المصفوفة الديناميكية وجعل الصيغة تنتشر في الخلايا المجاورة إذا كان ذلك ممكنًا.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | قم بإنشاء جدول بيانات مكون من متغيرين للنطاق المحدد بدءًا من هذه الخلية.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | قم بإنشاء جدول بيانات مكون من متغير واحد للنطاق المحدد بدءًا من هذه الخلية.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | قم بإنشاء جدول بيانات مكون من متغيرين للنطاق المحدد بدءًا من هذه الخلية.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | قم بإنشاء جدول بيانات مكون من متغير واحد للنطاق المحدد بدءًا من هذه الخلية.|
| [`get_characters(self)`](/cells/python-net/ar/aspose.cells/cell/get_characters/#) | إرجاع جميع كائنات الأحرف<br/> وهو ما يمثل نطاقًا من الأحرف داخل نص الخلية.|
| [`get_characters(self, flag)`](/cells/python-net/ar/aspose.cells/cell/get_characters/#bool) | إرجاع جميع كائنات الأحرف<br/> وهو ما يمثل نطاقًا من الأحرف داخل نص الخلية.|
| [`calculate(self, options)`](/cells/python-net/ar/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | يحسب صيغة الخلية.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/ar/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |يحصل على قيمة السلسلة حسب استراتيجية منسقة محددة.|
| [`get_width_of_value(self)`](/cells/python-net/ar/aspose.cells/cell/get_width_of_value/#) | يحصل على عرض القيمة بوحدة البكسل.|
| [`get_height_of_value(self)`](/cells/python-net/ar/aspose.cells/cell/get_height_of_value/#) | يحصل على ارتفاع القيمة بوحدة البكسل.|
| [`get_format_conditions(self)`](/cells/python-net/ar/aspose.cells/cell/get_format_conditions/#) | يحصل على شروط التنسيق التي تنطبق على هذه الخلية.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/ar/aspose.cells/cell/get_formula/#bool-bool) | احصل على صيغة هذه الخلية.|
| [`get_precedents(self)`](/cells/python-net/ar/aspose.cells/cell/get_precedents/#) | يحصل على جميع المراجع التي تظهر في صيغة هذه الخلية.|
| [`get_dependents(self, is_all)`](/cells/python-net/ar/aspose.cells/cell/get_dependents/#bool) | احصل على جميع الخلايا التي تشير صيغتها إلى هذه الخلية بشكل مباشر.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/ar/aspose.cells/cell/get_precedents_in_calculation/#) | يحصل على جميع السوابق (الإشارة إلى الخلايا في المصنف الحالي) التي تستخدمها صيغة هذه الخلية أثناء حسابها.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation/#bool) | يحصل على جميع الخلايا التي تعتمد نتيجتها المحسوبة على هذه الخلية.|
| [`get_array_range(self)`](/cells/python-net/ar/aspose.cells/cell/get_array_range/#) | يحصل على نطاق المصفوفة إذا كانت صيغة الخلية عبارة عن صيغة مصفوفة.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/ar/aspose.cells/cell/remove_array_formula/#bool) | إزالة صيغة المصفوفة.|
| [`copy(self, cell)`](/cells/python-net/ar/aspose.cells/cell/copy/#aspose.cells.cell) | نسخ البيانات من خلية المصدر.|
| [`characters(self, start_index, length)`](/cells/python-net/ar/aspose.cells/cell/characters/#int-int) | يقوم بإرجاع كائن الأحرف الذي يمثل نطاقًا من الأحرف داخل نص الخلية.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/ar/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | استبدال نص الخلية بالخيارات.|
| [`insert_text(self, index, text)`](/cells/python-net/ar/aspose.cells/cell/insert_text/#int-str) | أدخل بعض الأحرف في الخلية.<br/> إذا كانت الخلية ذات تنسيق غني، فقد تتمكن هذه الطريقة من الاحتفاظ بالتنسيق الأصلي.|
| [`is_rich_text(self)`](/cells/python-net/ar/aspose.cells/cell/is_rich_text/#) |يشير إلى ما إذا كانت قيمة السلسلة لهذه الخلية عبارة عن نص منسق.|
| [`set_characters(self, characters)`](/cells/python-net/ar/aspose.cells/cell/set_characters/#list) | تعيين تنسيق النص الغني للخلية.|
| [`get_merged_range(self)`](/cells/python-net/ar/aspose.cells/cell/get_merged_range/#) | يقوم بإرجاع الكائن [`Range`](/cells/python-net/ar/aspose.cells/range) الذي يمثل نطاقًا مدمجًا.|
| [`get_html_string(self, html5)`](/cells/python-net/ar/aspose.cells/cell/get_html_string/#bool) | يحصل على سلسلة HTML التي تحتوي على البيانات وبعض التنسيقات في هذه الخلية.|
| [`to_json(self)`](/cells/python-net/ar/aspose.cells/cell/to_json/#) | تحويل بيانات الهيكل [`Cell`](/cells/python-net/ar/aspose.cells/cell) إلى JSON.|
| [`equals(self, cell)`](/cells/python-net/ar/aspose.cells/cell/equals/#aspose.cells.cell) | التحقق مما إذا كان هذا الكائن يشير إلى نفس الخلية مع كائن خلية آخر.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/ar/aspose.cells/cell/get_conditional_formatting_result/#) | احصل على نتيجة التنسيق الشرطي.|
| [`get_validation(self)`](/cells/python-net/ar/aspose.cells/cell/get_validation/#) | يحصل على التحقق المطبق على هذه الخلية.|
| [`get_validation_value(self)`](/cells/python-net/ar/aspose.cells/cell/get_validation_value/#) | يحصل على قيمة التحقق التي تم تطبيقها على هذه الخلية.|
| [`get_table(self)`](/cells/python-net/ar/aspose.cells/cell/get_table/#) | يحصل على الجدول الذي يحتوي على هذه الخلية.|
| [`get_rich_value(self)`](/cells/python-net/ar/aspose.cells/cell/get_rich_value/#) | يحصل على قيمة غنية للخلية.|



###  مثال

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
* فئة [`Range`](/cells/python-net/ar/aspose.cells/range)
