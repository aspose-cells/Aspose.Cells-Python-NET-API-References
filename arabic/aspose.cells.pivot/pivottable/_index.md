---
title: PivotTable صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 230
url: /ar/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable صف
وصف موجز لـ PivotTable.



يكشف النوع PivotTable عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/ar/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | يحدد ما إذا كان الجدول المحوري متوافقًا مع Excel2003 عند تحديث الجدول المحوري،<br/>إذا كانت القيمة صحيحة، فيجب أن يكون طول السلسلة أقل من أو يساوي 255 حرفًا، لذا إذا كانت السلسلة أكبر من 255 حرفًا،<br/>سيتم اقتطاعه. إذا كان false، فلن يكون للسلسلة القيد المذكور أعلاه.<br/> القيمة الافتراضية هي true.|
| [refreshed_by_who](/cells/python-net/ar/aspose.cells.pivot/pivottable/refreshed_by_who) | يحصل على اسم آخر مستخدم قام بتحديث جدول البيانات المحوري هذا|
| [refresh_date](/cells/python-net/ar/aspose.cells.pivot/pivottable/refresh_date) | يحصل على تاريخ الوقت الأخير الذي تم فيه تحديث الجدول المحوري.|
| [pivot_table_style_name](/cells/python-net/ar/aspose.cells.pivot/pivottable/pivot_table_style_name) | يحصل على اسم نمط الجدول المحوري ويقوم بتعيينه.|
| [pivot_table_style_type](/cells/python-net/ar/aspose.cells.pivot/pivottable/pivot_table_style_type) | يحصل على نمط جدول المحور المدمج ويقوم بتعيينه.|
| [column_fields](/cells/python-net/ar/aspose.cells.pivot/pivottable/column_fields) | يقوم بإرجاع كائن PivotFields الذي يتم عرضه حاليًا كحقول أعمدة.|
| [row_fields](/cells/python-net/ar/aspose.cells.pivot/pivottable/row_fields) | يقوم بإرجاع كائن PivotFields الذي يتم عرضه حاليًا كحقول صف.|
| [page_fields](/cells/python-net/ar/aspose.cells.pivot/pivottable/page_fields) | يقوم بإرجاع كائن PivotFields الذي يتم عرضه حاليًا كحقول صفحة.|
| [data_fields](/cells/python-net/ar/aspose.cells.pivot/pivottable/data_fields) | يحصل على كائن PivotField الذي يمثل جميع حقول البيانات في PivotTable.<br/>للقراءة فقط. سيكون init فقط عندما يكون هناك حقلين أو أكثر من البيانات في DataPiovtFiels.<br/> يُستخدم فقط لإضافة حقل DataPivotField إلى منطقة الصفوف/الأعمدة في جدول PivotTable. الإعداد الافتراضي هو منطقة الصفوف.|
| [data_field](/cells/python-net/ar/aspose.cells.pivot/pivottable/data_field) |يحصل على الكائن [`PivotField`](/cells/python-net/ar/aspose.cells.pivot/pivotfield) الذي يمثل كافة حقول البيانات في جدول محوري.<br/>للقراءة فقط.<br/>سيتم إنشاؤه فقط عندما يكون هناك حقلين أو أكثر من البيانات في منطقة البيانات.<br/> افتراضيًا، يكون في منطقة الصف. يمكنك سحبه إلى منطقة الصف/العمود باستخدام دالة PivotTable.AddFieldToArea().|
| [base_fields](/cells/python-net/ar/aspose.cells.pivot/pivottable/base_fields) | إرجاع كافة حقول المحور الأساسية في جدول المحور.|
| [pivot_filters](/cells/python-net/ar/aspose.cells.pivot/pivottable/pivot_filters) | إرجاع جميع مرشحات حقول المحور في جدول المحور.|
| [column_range](/cells/python-net/ar/aspose.cells.pivot/pivottable/column_range) | إرجاع كائن CellArea الذي يمثل النطاق<br/> الذي يحتوي على منطقة العمود في تقرير PivotTable. للقراءة فقط.|
| [row_range](/cells/python-net/ar/aspose.cells.pivot/pivottable/row_range) | إرجاع كائن CellArea الذي يمثل النطاق<br/> الذي يحتوي على منطقة الصف في تقرير PivotTable. للقراءة فقط.|
| [data_body_range](/cells/python-net/ar/aspose.cells.pivot/pivottable/data_body_range) | إرجاع كائن [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) الذي يمثل النطاق الذي يحتوي على منطقة البيانات<br/> في القائمة بين صف الرأس وصف الإدراج. للقراءة فقط.|
| [table_range1](/cells/python-net/ar/aspose.cells.pivot/pivottable/table_range1) | إرجاع كائن CellArea الذي يمثل النطاق الذي يحتوي على تقرير PivotTable بأكمله،<br/> لكن لا يتضمن حقول الصفحة. للقراءة فقط.|
| [table_range2](/cells/python-net/ar/aspose.cells.pivot/pivottable/table_range2) | إرجاع كائن CellArea الذي يمثل النطاق الذي يحتوي على تقرير PivotTable بأكمله،<br/> يتضمن حقول الصفحة. للقراءة فقط.|
| [is_grid_drop_zones](/cells/python-net/ar/aspose.cells.pivot/pivottable/is_grid_drop_zones) | يشير إلى ما إذا كان تقرير PivotTable يعرض تخطيط PivotTable الكلاسيكي.<br/> (يتيح سحب الحقول في الشبكة)|
| [show_column_grand_totals](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_column_grand_totals) |يشير إلى ما إذا كان سيتم عرض الإجماليات الكلية لأعمدة جدول المحور هذا.|
| [show_row_grand_totals](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_row_grand_totals) | يشير إلى ما إذا كان سيتم عرض الإجماليات الكلية لصفوف جدول المحور.|
| [column_grand](/cells/python-net/ar/aspose.cells.pivot/pivottable/column_grand) | يشير إلى ما إذا كان تقرير PivotTable يعرض الإجماليات الكلية للأعمدة.|
| [row_grand](/cells/python-net/ar/aspose.cells.pivot/pivottable/row_grand) | يشير إلى ما إذا كان سيتم عرض الإجماليات الكبرى لصفوف جدول المحور هذا.|
| [display_null_string](/cells/python-net/ar/aspose.cells.pivot/pivottable/display_null_string) | يشير إلى ما إذا كان تقرير PivotTable يعرض سلسلة مخصصة إذا كانت القيمة فارغة.|
| [null_string](/cells/python-net/ar/aspose.cells.pivot/pivottable/null_string) | يحصل على السلسلة المعروضة في الخلايا التي تحتوي على قيم فارغة<br/> عندما تكون خاصية DisplayNullString صحيحة. القيمة الافتراضية هي سلسلة فارغة.|
| [display_error_string](/cells/python-net/ar/aspose.cells.pivot/pivottable/display_error_string) | يشير إلى ما إذا كان تقرير PivotTable يعرض سلسلة مخصصة في الخلايا التي تحتوي على أخطاء.|
| [data_field_header_name](/cells/python-net/ar/aspose.cells.pivot/pivottable/data_field_header_name) | يحصل على اسم رأس حقل منطقة القيمة في الجدول المحوري ويقوم بتعيينه.|
| [error_string](/cells/python-net/ar/aspose.cells.pivot/pivottable/error_string) | يحصل على السلسلة المعروضة في الخلايا التي تحتوي على أخطاء<br/> عندما تكون خاصية DisplayErrorString صحيحة. القيمة الافتراضية هي سلسلة فارغة.|
| [is_auto_format](/cells/python-net/ar/aspose.cells.pivot/pivottable/is_auto_format) | يشير إلى ما إذا كان يتم تنسيق تقرير PivotTable تلقائيًا.<br/>مربع الاختيار "تنسيق الجدول تلقائيًا" الموجود في خيار Pivottable لبرنامج Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/ar/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | يشير إلى ما إذا كان يتم ضبط عرض العمود تلقائيًا عند التحديث|
| [auto_format_type](/cells/python-net/ar/aspose.cells.pivot/pivottable/auto_format_type) | يحصل على نوع التنسيق التلقائي لجدول PivotTable ويقوم بتعيينه.|
| [has_blank_rows](/cells/python-net/ar/aspose.cells.pivot/pivottable/has_blank_rows) | يشير إلى ما إذا كان سيتم إضافة صفوف فارغة.<br/> تنطبق هذه الخاصية فقط على أنواع التنسيق التلقائي لـ PivotTable والتي تحتاج إلى إضافة صفوف فارغة.|
| [merge_labels](/cells/python-net/ar/aspose.cells.pivot/pivottable/merge_labels) | صحيح إذا كانت تسميات عنصر الصف الخارجي وعنصر العمود والمجموع الفرعي والمجموع الكلي لتقرير PivotTable المحدد تستخدم خلايا مدمجة.|
| [preserve_formatting](/cells/python-net/ar/aspose.cells.pivot/pivottable/preserve_formatting) | يشير إلى ما إذا كان يتم الحفاظ على التنسيق عند تحديث الجدول المحوري أو إعادة حسابه.|
| [show_drill](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_drill) | يحصل ويحدد ما إذا كان سيتم عرض أزرار التوسيع/الطي.|
| [enable_drilldown](/cells/python-net/ar/aspose.cells.pivot/pivottable/enable_drilldown) | يحصل على ما إذا كان التنقيب ممكّنًا.|
| [enable_field_dialog](/cells/python-net/ar/aspose.cells.pivot/pivottable/enable_field_dialog) | يشير إلى ما إذا كان مربع حوار حقل الجدول المحوري متاحًا<br/> عندما يقوم المستخدم بالنقر المزدوج فوق حقل PivotTable.|
| [enable_field_list](/cells/python-net/ar/aspose.cells.pivot/pivottable/enable_field_list) | يشير إلى ما إذا كانت قائمة الحقول الخاصة بجدول البيانات المحوري متوفرة في عرض Excel.|
| [enable_wizard](/cells/python-net/ar/aspose.cells.pivot/pivottable/enable_wizard) | يشير إلى ما إذا كان معالج PivotTable متاحًا.|
| [subtotal_hidden_page_items](/cells/python-net/ar/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |يشير إلى ما إذا كانت عناصر حقل الصفحة مخفية في تقرير PivotTable<br/>يتم تضمينها في إجماليات الصفوف والأعمدة، وإجماليات الكتل، والإجماليات الكلية.<br/> القيمة الافتراضية هي False.|
| [grand_total_name](/cells/python-net/ar/aspose.cells.pivot/pivottable/grand_total_name) | إرجاع الملصق الذي يتم عرضه في عنوان عمود الإجمالي الكلي أو الصف.<br/> القيمة الافتراضية هي السلسلة "الإجمالي الكلي".|
| [manual_update](/cells/python-net/ar/aspose.cells.pivot/pivottable/manual_update) | يشير إلى ما إذا كان سيتم إعادة حساب تقرير PivotTable فقط بناءً على طلب المستخدم.|
| [is_multiple_field_filters](/cells/python-net/ar/aspose.cells.pivot/pivottable/is_multiple_field_filters) | يحدد قيمة منطقية تشير إلى ما إذا كان من الممكن تعيين عدة مرشحات على حقول جدول محوري.|
| [allow_multiple_filters_per_field](/cells/python-net/ar/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) | يحدد قيمة منطقية تشير إلى ما إذا كان من الممكن تعيين عدة مرشحات على حقول جدول محوري.|
| [missing_items_limit](/cells/python-net/ar/aspose.cells.pivot/pivottable/missing_items_limit) | يحدد قيمة منطقية تشير إلى ما إذا كان من الممكن تعيين عدة مرشحات على حقول جدول محوري.|
| [enable_data_value_editing](/cells/python-net/ar/aspose.cells.pivot/pivottable/enable_data_value_editing) | يحدد قيمة منطقية تشير إلى ما إذا كان يُسمح للمستخدم بتحرير الخلايا في منطقة البيانات في الجدول المحوري.<br/> تمكين تحرير الخلايا في منطقة القيم|
| [show_data_tips](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_data_tips) | يقوم بتحديد قيمة منطقية تشير إلى ما إذا كان يجب عرض تلميحات الأدوات لخلايا بيانات الجدول المحوري.|
| [show_member_property_tips](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_member_property_tips) | يحدد قيمة منطقية تشير إلى ما إذا كان ينبغي حذف معلومات خصائص العضو من تلميحات أدوات PivotTable.|
| [show_values_row](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_values_row) | يشير إلى ما إذا كان يتم عرض صف القيم.|
| [show_empty_col](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_empty_col) | يشير إلى ما إذا كان سيتم تضمين الأعمدة الفارغة في الجدول|
| [show_empty_row](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_empty_row) |يشير إلى ما إذا كان سيتم تضمين الصفوف الفارغة في الجدول.|
| [field_list_sort_ascending](/cells/python-net/ar/aspose.cells.pivot/pivottable/field_list_sort_ascending) | يشير إلى ما إذا كانت الحقول في الجدول المحوري مرتبة بترتيب غير افتراضي في قائمة الحقول.|
| [print_drill](/cells/python-net/ar/aspose.cells.pivot/pivottable/print_drill) | يحدد قيمة منطقية تشير إلى ما إذا كان يجب طباعة مؤشرات الحفر.<br/> طباعة أزرار التوسيع/الطي عند عرضها على الجدول المحوري.|
| [alt_text_title](/cells/python-net/ar/aspose.cells.pivot/pivottable/alt_text_title) | يحصل على عنوان النص البديل ويحدده.|
| [alt_text_description](/cells/python-net/ar/aspose.cells.pivot/pivottable/alt_text_description) | يحصل على وصف النص البديل.|
| [name](/cells/python-net/ar/aspose.cells.pivot/pivottable/name) | يحصل على اسم الجدول المحوري|
| [column_header_caption](/cells/python-net/ar/aspose.cells.pivot/pivottable/column_header_caption) | يحصل على عنوان رأس العمود للجدول المحوري.|
| [indent](/cells/python-net/ar/aspose.cells.pivot/pivottable/indent) | يقوم بتحديد زيادة المسافة البادئة للمحور المضغوط ويمكن استخدامه لتعيين تخطيط التقرير إلى نموذج مضغوط.|
| [row_header_caption](/cells/python-net/ar/aspose.cells.pivot/pivottable/row_header_caption) | يحصل على تسمية توضيحية لرأس الصف في جدول البيانات المحوري.|
| [show_row_header_caption](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_row_header_caption) | يشير إلى ما إذا كان سيتم عرض عنوان رأس الصف في تقرير PivotTable<br/> يشير إلى ما إذا كان سيتم عرض عناوين الحقول وقوائم التصفية المنسدلة|
| [custom_list_sort](/cells/python-net/ar/aspose.cells.pivot/pivottable/custom_list_sort) | يشير إلى ما إذا كان سيتم أخذ القائمة المخصصة المضمنة في الاعتبار عند فرز البيانات|
| [pivot_format_conditions](/cells/python-net/ar/aspose.cells.pivot/pivottable/pivot_format_conditions) | يحصل على شروط التنسيق للجدول المحوري.|
| [conditional_formats](/cells/python-net/ar/aspose.cells.pivot/pivottable/conditional_formats) | يحصل على التنسيقات الشرطية لجدول المحور.|
| [page_field_order](/cells/python-net/ar/aspose.cells.pivot/pivottable/page_field_order) |يحصل على الترتيب الذي تتم به إضافة حقول الصفحة إلى تخطيط تقرير PivotTable ويقوم بتعيينه.|
| [page_field_wrap_count](/cells/python-net/ar/aspose.cells.pivot/pivottable/page_field_wrap_count) | يحصل على عدد حقول الصفحة في كل عمود أو صف في تقرير PivotTable.|
| [tag](/cells/python-net/ar/aspose.cells.pivot/pivottable/tag) | يحصل على سلسلة محفوظة مع تقرير PivotTable.|
| [save_data](/cells/python-net/ar/aspose.cells.pivot/pivottable/save_data) | يشير إلى ما إذا كان يتم حفظ البيانات الخاصة بتقرير PivotTable مع المصنف.|
| [refresh_data_on_opening_file](/cells/python-net/ar/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | يشير إلى ما إذا كان سيتم تحديث البيانات عند فتح الملف.|
| [refresh_data_flag](/cells/python-net/ar/aspose.cells.pivot/pivottable/refresh_data_flag) | يشير إلى ما إذا كان يتم تحديث البيانات أم لا.|
| [source_type](/cells/python-net/ar/aspose.cells.pivot/pivottable/source_type) | يحصل على نوع مصدر البيانات للجدول المحوري.|
| [external_connection_data_source](/cells/python-net/ar/aspose.cells.pivot/pivottable/external_connection_data_source) | يحصل على مصدر بيانات الاتصال الخارجي.|
| [data_source](/cells/python-net/ar/aspose.cells.pivot/pivottable/data_source) | يحصل على مصدر البيانات للجدول المحوري ويقوم بتعيينه.|
| [pivot_formats](/cells/python-net/ar/aspose.cells.pivot/pivottable/pivot_formats) | يحصل على مجموعة التنسيقات المطبقة على PivotTable.|
| [item_print_titles](/cells/python-net/ar/aspose.cells.pivot/pivottable/item_print_titles) | يشير إلى ما إذا كان يجب تكرار أسماء PivotItem في الجزء العلوي من كل صفحة مطبوعة.|
| [repeat_items_on_each_printed_page](/cells/python-net/ar/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) | يشير إلى ما إذا كانت تسميات العناصر المحورية في منطقة الصف تتكرر في كل صفحة مطبوعة لحقول المحور في شكل جدول.|
| [print_titles](/cells/python-net/ar/aspose.cells.pivot/pivottable/print_titles) | يشير إلى ما إذا كانت عناوين الطباعة لورقة العمل محددة بناءً على<br/> في تقرير الجدول المحوري. القيمة الافتراضية هي خطأ.|
| [display_immediate_items](/cells/python-net/ar/aspose.cells.pivot/pivottable/display_immediate_items) |يشير إلى ما إذا كانت العناصر الموجودة في مناطق الصفوف والأعمدة مرئية<br/> عندما تكون منطقة بيانات الجدول المحوري فارغة. القيمة الافتراضية هي "صحيح".|
| [is_selected](/cells/python-net/ar/aspose.cells.pivot/pivottable/is_selected) | يشير إلى ما إذا كان تم تحديد جدول المحور هذا.|
| [show_pivot_style_row_header](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | يشير إلى ما إذا كان يجب تطبيق النمط على رأس الصف في جدول المحور.|
| [show_pivot_style_column_header](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | يشير إلى ما إذا كان يجب تطبيق النمط على رأس العمود في جدول المحور.|
| [show_pivot_style_row_stripes](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | يشير إلى ما إذا كان يتم تطبيق تنسيق شريط الصف.|
| [show_pivot_style_column_stripes](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | يشير إلى ما إذا كان يتم تطبيق تنسيق الشريط على العمود.|
| [show_pivot_style_last_column](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | يشير إلى ما إذا كان يتم تطبيق تنسيق العمود.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) | إزالة حقل من منطقة حقل محددة|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) | إزالة حقل من منطقة حقل محددة|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | إزالة الحقل من منطقة الحقل المحددة|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) | يضيف الحقل إلى المنطقة المحددة.|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) | يضيف الحقل إلى المنطقة المحددة.|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | يضيف الحقل إلى المنطقة المحددة.|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | إضافة حقل محسوب إلى حقل المحور.|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | إضافة حقل محسوب إلى حقل المحور وسحبه إلى منطقة البيانات.|
| [`move(self, row, column)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/move/#int-int) | نقل الجدول المحوري إلى موقع مختلف في ورقة العمل.|
| [`move(self, dest_cell_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/move/#str) | نقل الجدول المحوري إلى موقع مختلف في ورقة العمل.|
| [`move_to(self, row, column)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/move_to/#int-int) | نقل الجدول المحوري إلى موقع مختلف في ورقة العمل.|
| [`move_to(self, dest_cell_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/move_to/#str) | نقل الجدول المحوري إلى موقع مختلف في ورقة العمل.|
| [`get_source(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_source/#) | احصل على بيانات المصدر الخاصة بـ Pivotable.|
| [`get_source(self, is_original)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_source/#bool) | احصل على بيانات المصدر الخاصة بـ Pivotable.|
| [`refresh_data(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/refresh_data/#) |يقوم بتحديث بيانات الجدول المحوري وإعداداته من مصدر البيانات الخاص به.|
| [`refresh_data(self, option)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) | يقوم بتحديث بيانات الجدول المحوري وإعداداته من مصدر البيانات الخاص به باستخدام الخيارات.|
| [`calculate_data(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/calculate_data/#) | حساب بيانات الجدول المحوري للخلايا.|
| [`calculate_data(self, option)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) | حساب جداول المحور مع الخيارات|
| [`format(self, pivot_area, style)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) | تنسيق المنطقة المحددة من الجدول المحوري.|
| [`format(self, ca, style)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) | تنسيق المنطقة المحددة من الجدول المحوري.|
| [`format(self, row, column, style)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) | تنسيق الخلية في منطقة الجدول المحوري|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | تعيين مجموعة الحقول التلقائية حسب جدول البيانات المحوري.|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) | تعيين مجموعة الحقول التلقائية حسب جدول البيانات المحوري.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | تعيين مجموعة الحقول اليدوية حسب جدول البيانات المحوري.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) | تعيين مجموعة الحقول اليدوية حسب جدول البيانات المحوري.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) | تعيين مجموعة الحقول اليدوية حسب جدول البيانات المحوري.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) | تعيين مجموعة الحقول اليدوية حسب جدول البيانات المحوري.|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_ungroup/#int) | تعيين إلغاء التجميع حسب جدول البيانات المحوري|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) | تعيين إلغاء التجميع حسب جدول البيانات المحوري|
| [`copy_style(self, pivot_table)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) | نسخ النمط المسمى من جدول محوري آخر.|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) | إظهار جميع صفحات مرشح التقرير وفقًا لـ PivotField، ويجب أن يكون PivotField موجودًا في PageFields.|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | إظهار جميع صفحات مرشح التقرير وفقًا لاسم PivotField، ويجب أن يكون PivotField موجودًا في PageFields.|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | إظهار جميع صفحات مرشح التقرير وفقًا لمؤشر الموضع في PageFields|
| [`get_fields(self, field_type)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) | يحصل على قائمة حقول المحور المحددة حسب المنطقة.|
| [`fields(self, field_type)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) | يحصل على الحقول المحددة حسب نوع الحقل.|
| [`get_source_data_connections(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_source_data_connections/#) |يحصل على مصادر بيانات الاتصال الخارجية.|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) | يحصل على اسم اتصالات البيانات المصدرية الخارجية.|
| [`change_data_source(self, source)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/change_data_source/#list) | تعيين بيانات المصدر لجدول محوري.|
| [`clear_data(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/clear_data/#) | مسح بيانات وتنسيق PivotTable|
| [`calculate_range(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/calculate_range/#) | يحسب نطاق الجدول المحوري.|
| [`format_all(self, style)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) | تنسيق كافة الخلايا في منطقة الجدول المحوري|
| [`format_row(self, row, style)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) | تنسيق بيانات الصف في منطقة الجدول المحوري|
| [`select_area(self, ca)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) | حدد منطقة عرض جدول المحور.|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) | إظهار تفاصيل عنصر واحد في منطقة البيانات في جدول جديد.|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) | يحصل على فواصل الصفحات الأفقية لهذا الجدول المحوري.|
| [`get_horizontal_breaks(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | يحصل على قائمة فهرس الصفوف في جدول محوري لفواصل الصفحات الأفقية|
| [`show_in_compact_form(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_in_compact_form/#) | تخطيط جدول البيانات المحوري في شكل مضغوط.|
| [`show_in_outline_form(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_in_outline_form/#) | تخطيط جدول البيانات المحوري في شكل مخطط تفصيلي.|
| [`show_in_tabular_form(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | تخطيط الجدول المحوري في شكل جدول.|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | يحصل على الكائن [`Cell`](/cells/python-net/ar/aspose.cells/cell) حسب اسم العرض PivotField.|
| [`get_children(self)`](/cells/python-net/ar/aspose.cells.pivot/pivottable/get_children/#) | يحصل على جداول البيانات المحورية للأطفال التي تستخدم بيانات جدول البيانات المحوري هذا كمصدر للبيانات.|



###  مثال

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](..)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
* فئة [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea)
* فئة [`PivotField`](/cells/python-net/ar/aspose.cells.pivot/pivotfield)
