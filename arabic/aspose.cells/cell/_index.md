---
title: Cell صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 140
url: /ar/aspose.cells/cell/
is_root: false
---
##  Cell صف
يقوم بتغليف الكائن الذي يمثل خلية مصنف واحدة.



يكشف النوع Cell عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [worksheet](/cells/python-net/ar/aspose.cells/cell/worksheet) |يحصل على ورقة العمل الأصل.|
| [date_time_value](/cells/python-net/ar/aspose.cells/cell/date_time_value) | الحصول على قيمة DateTime الموجودة في الخلية.|
| [row](/cells/python-net/ar/aspose.cells/cell/row) | الحصول على رقم الصف (على أساس صفر) للخلية.|
| [column](/cells/python-net/ar/aspose.cells/cell/column) | الحصول على رقم العمود (على أساس صفر) للخلية.|
| [is_formula](/cells/python-net/ar/aspose.cells/cell/is_formula) | يمثل ما إذا كانت الخلية المحددة تحتوي على صيغة.|
| [type](/cells/python-net/ar/aspose.cells/cell/type) | يمثل نوع قيمة الخلية.|
| [name](/cells/python-net/ar/aspose.cells/cell/name) | يحصل على اسم الخلية.|
| [is_error_value](/cells/python-net/ar/aspose.cells/cell/is_error_value) | يتحقق مما إذا كانت قيمة هذه الخلية خطأ.|
| [is_numeric_value](/cells/python-net/ar/aspose.cells/cell/is_numeric_value) | يشير إلى ما إذا كانت قيمة هذه الخلية رقمية (int، double و datetime)|
| [string_value](/cells/python-net/ar/aspose.cells/cell/string_value) | يحصل على قيمة السلسلة الموجودة في الخلية. إذا كان نوع هذه الخلية عبارة عن سلسلة، فقم بإرجاع قيمة السلسلة نفسها.<br/>بالنسبة لأنواع الخلايا الأخرى، سيتم إرجاع قيمة السلسلة المنسقة (المنسقة بالنمط المحدد لهذه الخلية).<br/>قيمة الخلية المنسقة هي نفسها مع ما يمكنك الحصول عليه من Excel عند نسخ خلية كنص (مثل<br/> نسخ الخلية إلى محرر النصوص أو التصدير إلى ملف CSV).|
| [string_value_without_format](/cells/python-net/ar/aspose.cells/cell/string_value_without_format) | يحصل على قيمة الخلية كسلسلة بدون أي تنسيق.|
| [number_category_type](/cells/python-net/ar/aspose.cells/cell/number_category_type) | يمثل نوع الفئة لتنسيق أرقام هذه الخلية.|
| [display_string_value](/cells/python-net/ar/aspose.cells/cell/display_string_value) | الحصول على قيمة السلسلة المنسقة لهذه الخلية حسب نمط عرض الخلية.|
| [int_value](/cells/python-net/ar/aspose.cells/cell/int_value) | الحصول على القيمة الصحيحة الموجودة في الخلية.|
| [double_value](/cells/python-net/ar/aspose.cells/cell/double_value) | الحصول على القيمة المزدوجة الموجودة في الخلية.|
| [float_value](/cells/python-net/ar/aspose.cells/cell/float_value) | الحصول على القيمة العائمة الموجودة في الخلية.|
| [bool_value](/cells/python-net/ar/aspose.cells/cell/bool_value) |يحصل على القيمة المنطقية الموجودة في الخلية.|
| [has_custom_style](/cells/python-net/ar/aspose.cells/cell/has_custom_style) | يشير إلى ما إذا كانت هذه الخلية تحتوي على إعدادات نمط مخصصة (تختلف عن الإعدادات الافتراضية الموروثة<br/> من الصف أو العمود أو المصنف المقابل).|
| [shared_style_index](/cells/python-net/ar/aspose.cells/cell/shared_style_index) | يحصل على فهرس النمط المشترك للخلية في تجمع الأنماط.|
| [formula](/cells/python-net/ar/aspose.cells/cell/formula) | الحصول على صيغة [`Cell`](/cells/python-net/ar/aspose.cells/cell) أو تعيينها.|
| [formula_local](/cells/python-net/ar/aspose.cells/cell/formula_local) | احصل على الصيغة المنسقة للخلية.|
| [r1c1_formula](/cells/python-net/ar/aspose.cells/cell/r1c1_formula) | الحصول على صيغة R1C1 للرقم [`Cell`](/cells/python-net/ar/aspose.cells/cell) أو تعيينها.|
| [contains_external_link](/cells/python-net/ar/aspose.cells/cell/contains_external_link) | يشير إلى ما إذا كانت هذه الخلية تحتوي على رابط خارجي.<br/> ينطبق فقط عندما تكون الخلية عبارة عن خلية صيغة.|
| [is_array_header](/cells/python-net/ar/aspose.cells/cell/is_array_header) | يشير إلى أن صيغة الخلية هي صيغة صفيف<br/> وهي الخلية الأولى في المصفوفة.|
| [is_dynamic_array_formula](/cells/python-net/ar/aspose.cells/cell/is_dynamic_array_formula) | يشير إلى ما إذا كانت صيغة الخلية هي صيغة صفيف ديناميكية (صحيح) أو صيغة صفيف قديمة (خطأ).|
| [is_array_formula](/cells/python-net/ar/aspose.cells/cell/is_array_formula) | الإشارة إلى ما إذا كانت صيغة الخلية عبارة عن صيغة صفيف.|
| [is_in_array](/cells/python-net/ar/aspose.cells/cell/is_in_array) | الإشارة إلى ما إذا كانت صيغة الخلية عبارة عن صيغة صفيف.|
| [is_shared_formula](/cells/python-net/ar/aspose.cells/cell/is_shared_formula) | يشير إلى ما إذا كانت صيغة الخلية جزءًا من صيغة مشتركة.|
| [is_table_formula](/cells/python-net/ar/aspose.cells/cell/is_table_formula) | الإشارة إلى ما إذا كانت هذه الخلية جزءًا من صيغة الجدول.|
| [is_in_table](/cells/python-net/ar/aspose.cells/cell/is_in_table) | الإشارة إلى ما إذا كانت هذه الخلية جزءًا من صيغة الجدول.|
| [value](/cells/python-net/ar/aspose.cells/cell/value) | يحصل/يحدد القيمة الموجودة في هذه الخلية.|
| [is_style_set](/cells/python-net/ar/aspose.cells/cell/is_style_set) |يشير إلى ما إذا تم تعيين نمط الخلية. إذا تم إرجاع خطأ، فهذا يعني أن هذه الخلية لها تنسيق خلية افتراضي.|
| [is_merged](/cells/python-net/ar/aspose.cells/cell/is_merged) | التحقق مما إذا كانت الخلية جزءًا من نطاق مدمج أم لا.|
| [comment](/cells/python-net/ar/aspose.cells/cell/comment) | يحصل على تعليق هذه الخلية.|
| [html_string](/cells/python-net/ar/aspose.cells/cell/html_string) | الحصول على سلسلة html التي تحتوي على البيانات وبعض التنسيقات في هذه الخلية وتعيينها.|
| [embedded_image](/cells/python-net/ar/aspose.cells/cell/embedded_image) | الحصول على الصورة المضمنة في الخلية وتعيينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#bool) | يضع قيمة منطقية في الخلية.|
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#int) | يضع قيمة عددية في الخلية.|
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#float) | يضع قيمة مزدوجة في الخلية.|
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#str-bool-bool) | يضع قيمة في الخلية، وإذا كان ذلك مناسبًا، فسيتم تحويل القيمة إلى نوع بيانات آخر وسيتم إعادة تعيين تنسيق أرقام الخلية.|
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#str-bool) | يضع قيمة سلسلة في الخلية ويحول القيمة إلى نوع بيانات آخر إذا كان ذلك مناسبًا.|
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#str) | يضع قيمة سلسلة في الخلية.|
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#DateTime) | يضع قيمة DateTime في الخلية.|
| [put_value](/cells/python-net/ar/aspose.cells/cell/put_value/#any) | يضع قيمة كائن في الخلية.|
| [get_display_style](/cells/python-net/ar/aspose.cells/cell/get_display_style/#) | الحصول على نمط عرض الخلية.<br/>إذا تأثرت هذه الخلية أيضًا بإعدادات أخرى مثل التنسيق الشرطي وكائنات القائمة وما إلى ذلك،<br/>فقد يكون نمط العرض مختلفًا عن cell.GetStyle().|
| [get_display_style](/cells/python-net/ar/aspose.cells/cell/get_display_style/#bool) | الحصول على نمط عرض الخلية.<br/> إذا كانت الخلية منسقة شرطيًا، فإن نمط العرض ليس هو نفسه cell.GetStyle().|
| [get_style](/cells/python-net/ar/aspose.cells/cell/get_style/#) | الحصول على نمط الخلية.|
| [get_style](/cells/python-net/ar/aspose.cells/cell/get_style/#bool) | إذا كانت قيمة checkBorders صحيحة، فتحقق مما إذا كانت حدود الخلايا الأخرى ستؤثر على نمط هذه الخلية.|
| [set_style](/cells/python-net/ar/aspose.cells/cell/set_style/#aspose.cells.Style) | يضبط نمط الخلية.|
| [set_style](/cells/python-net/ar/aspose.cells/cell/set_style/#aspose.cells.Style-bool) | قم بتطبيق خاصية النمط المتغيرة على الخلية.|
| [set_style](/cells/python-net/ar/aspose.cells/cell/set_style/#aspose.cells.Style-aspose.cells.StyleFlag) | قم بتطبيق نمط الخلية بناءً على الأعلام.|
| [set_formula](/cells/python-net/ar/aspose.cells/cell/set_formula/#str-any) | قم بتعيين الصيغة وقيمة (النتيجة المحسوبة) للصيغة.|
| [set_formula](/cells/python-net/ar/aspose.cells/cell/set_formula/#str-bool-bool-any) | قم بتعيين الصيغة وقيمة الصيغة.|
| [set_formula](/cells/python-net/ar/aspose.cells/cell/set_formula/#str-aspose.cells.FormulaParseOptions-any) | قم بتعيين الصيغة وقيمة (النتيجة المحسوبة) للصيغة.|
| [set_array_formula](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | تعيين صيغة صفيف لنطاق من الخلايا.|
| [set_array_formula](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int) | يعين صيغة صفيف (تم إدخال صيغة الصفيف القديمة عبر CTRL + SHIFT + ENTER في مللي إكسل) إلى نطاق من الخلايا.|
| [set_array_formula](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions) | تعيين صيغة صفيف لنطاق من الخلايا.|
| [set_array_formula](/cells/python-net/ar/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | تعيين صيغة صفيف لنطاق من الخلايا.|
| [set_shared_formula](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | تعيين صيغة لنطاق من الخلايا.|
| [set_shared_formula](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int) | تعيين الصيغ المشتركة لنطاق من الخلايا.|
| [set_shared_formula](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions) | تعيين الصيغ المشتركة لنطاق من الخلايا.|
| [set_shared_formula](/cells/python-net/ar/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | تعيين الصيغ المشتركة لنطاق من الخلايا.|
| [get_leafs](/cells/python-net/ar/aspose.cells/cell/get_leafs/#) | احصل على كافة الخلايا التي تشير إلى هذه الخلية مباشرة وتحتاج إلى التحديث عند تعديل هذه الخلية.|
| [get_leafs](/cells/python-net/ar/aspose.cells/cell/get_leafs/#bool) | الحصول على جميع الخلايا التي سيتم تحديثها عند تعديل هذه الخلية.|
| [set_dynamic_array_formula](/cells/python-net/ar/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-bool) |يضبط صيغة الصفيف الديناميكي ويجعل الصيغة تمتد إلى الخلايا المجاورة إن أمكن.|
| [set_dynamic_array_formula](/cells/python-net/ar/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool) |يضبط صيغة الصفيف الديناميكي ويجعل الصيغة تمتد إلى الخلايا المجاورة إن أمكن.|
| [set_dynamic_array_formula](/cells/python-net/ar/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions) |يضبط صيغة الصفيف الديناميكي ويجعل الصيغة تمتد إلى الخلايا المجاورة إن أمكن.|
| [set_table_formula](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | قم بإنشاء جدول بيانات ذو متغيرين لنطاق معين بدءًا من هذه الخلية.|
| [set_table_formula](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | قم بإنشاء جدول بيانات ذو متغير واحد لنطاق معين بدءًا من هذه الخلية.|
| [set_table_formula](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | قم بإنشاء جدول بيانات ذو متغيرين لنطاق معين بدءًا من هذه الخلية.|
| [set_table_formula](/cells/python-net/ar/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | قم بإنشاء جدول بيانات ذو متغير واحد لنطاق معين بدءًا من هذه الخلية.|
| [get_characters](/cells/python-net/ar/aspose.cells/cell/get_characters/#) | إرجاع كافة كائنات الأحرف<br/> يمثل نطاقًا من الأحرف داخل نص الخلية.|
| [get_characters](/cells/python-net/ar/aspose.cells/cell/get_characters/#bool) | إرجاع كافة كائنات الأحرف<br/> يمثل نطاقًا من الأحرف داخل نص الخلية.|
| [calculate](/cells/python-net/ar/aspose.cells/cell/calculate/#aspose.cells.CalculationOptions) | يحسب صيغة الخلية.|
| [get_string_value](/cells/python-net/ar/aspose.cells/cell/get_string_value/#aspose.cells.CellValueFormatStrategy) | يحصل على قيمة السلسلة من خلال استراتيجية منسقة محددة.|
| [get_width_of_value](/cells/python-net/ar/aspose.cells/cell/get_width_of_value/#) | يحصل على عرض القيمة بوحدة البكسل.|
| [get_height_of_value](/cells/python-net/ar/aspose.cells/cell/get_height_of_value/#) | يحصل على ارتفاع القيمة بوحدة البكسل.|
| [get_format_conditions](/cells/python-net/ar/aspose.cells/cell/get_format_conditions/#) | يحصل على شروط التنسيق التي تنطبق على هذه الخلية.|
| [get_formula](/cells/python-net/ar/aspose.cells/cell/get_formula/#bool-bool) | الحصول على صيغة هذه الخلية.|
| [get_precedents](/cells/python-net/ar/aspose.cells/cell/get_precedents/#) | يحصل على كافة المراجع التي تظهر في صيغة هذه الخلية.|
| [get_dependents](/cells/python-net/ar/aspose.cells/cell/get_dependents/#bool) | احصل على كافة الخلايا التي تشير صيغتها إلى هذه الخلية مباشرة.|
| [get_precedents_in_calculation](/cells/python-net/ar/aspose.cells/cell/get_precedents_in_calculation/#) | الحصول على كافة السوابق (مرجع إلى الخلايا الموجودة في المصنف الحالي) التي تستخدمها صيغة هذه الخلية أثناء حسابها.|
| [get_dependents_in_calculation](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation/#bool) | يحصل على كافة الخلايا التي تعتمد نتائجها المحسوبة على هذه الخلية.|
| [get_array_range](/cells/python-net/ar/aspose.cells/cell/get_array_range/#) |يحصل على نطاق الصفيف إذا كانت صيغة الخلية عبارة عن صيغة صفيف.|
| [remove_array_formula](/cells/python-net/ar/aspose.cells/cell/remove_array_formula/#bool) | إزالة صيغة الصفيف.|
| [copy](/cells/python-net/ar/aspose.cells/cell/copy/#aspose.cells.Cell) | نسخ البيانات من الخلية المصدر.|
| [characters](/cells/python-net/ar/aspose.cells/cell/characters/#int-int) | تقوم بإرجاع كائن الأحرف الذي يمثل نطاقًا من الأحرف داخل نص الخلية.|
| [replace](/cells/python-net/ar/aspose.cells/cell/replace/#str-str-aspose.cells.ReplaceOptions) | استبدال نص الخلية بالخيارات.|
| [insert_text](/cells/python-net/ar/aspose.cells/cell/insert_text/#int-str) | أدخل بعض الأحرف في الخلية.<br/> إذا كانت الخلية منسقة بشكل منسق، فيمكن أن تحتفظ هذه الطريقة بالتنسيق الأصلي.|
| [is_rich_text](/cells/python-net/ar/aspose.cells/cell/is_rich_text/#) | الإشارة إلى ما إذا كانت قيمة السلسلة لهذه الخلية عبارة عن نص منسق منسق.|
| [set_characters](/cells/python-net/ar/aspose.cells/cell/set_characters/#list) | يضبط تنسيق النص المنسق للخلية.|
| [get_merged_range](/cells/python-net/ar/aspose.cells/cell/get_merged_range/#) | تقوم بإرجاع كائن [`Range`](/cells/python-net/ar/aspose.cells/range) الذي يمثل نطاقًا مدمجًا.|
| [get_html_string](/cells/python-net/ar/aspose.cells/cell/get_html_string/#bool) | يحصل على سلسلة html التي تحتوي على البيانات وبعض التنسيقات في هذه الخلية.|
| [to_json](/cells/python-net/ar/aspose.cells/cell/to_json/#) | تحويل [`Cell`](/cells/python-net/ar/aspose.cells/cell) إلى JSON بيانات الهيكل.|
| [equals](/cells/python-net/ar/aspose.cells/cell/equals/#aspose.cells.Cell) | التحقق مما إذا كان هذا الكائن يشير إلى نفس الخلية مع كائن خلية آخر.|
| [get_conditional_formatting_result](/cells/python-net/ar/aspose.cells/cell/get_conditional_formatting_result/#) | الحصول على نتيجة التنسيق الشرطي.|
| [get_validation](/cells/python-net/ar/aspose.cells/cell/get_validation/#) | الحصول على التحقق المطبق على هذه الخلية.|
| [get_validation_value](/cells/python-net/ar/aspose.cells/cell/get_validation_value/#) | يحصل على قيمة التحقق من الصحة التي تنطبق على هذه الخلية.|
| [get_table](/cells/python-net/ar/aspose.cells/cell/get_table/#) |الحصول على الجدول الذي يحتوي على هذه الخلية.|



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
