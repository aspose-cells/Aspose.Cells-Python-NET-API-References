---
title: HtmlLoadOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 800
url: /ar/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions صف
يمثل الخيارات عند استيراد ملف HTML.



**ميراث:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)



يكشف النوع HtmlLoadOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/htmlloadoptions/__init__/#) | يخلق خيارات لتحميل الملف.|
| [__init__](/cells/python-net/ar/aspose.cells/htmlloadoptions/__init__/#aspose.cells.LoadFormat) | يخلق خيارات لتحميل الملف.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [load_format](/cells/python-net/ar/aspose.cells/htmlloadoptions/load_format) | يحصل على تنسيق التحميل.|
| [password](/cells/python-net/ar/aspose.cells/htmlloadoptions/password) | الحصول على كلمة المرور الخاصة بالمصنف وتعيينها.|
| [parsing_formula_on_open](/cells/python-net/ar/aspose.cells/htmlloadoptions/parsing_formula_on_open) | يشير إلى ما إذا كان سيتم تحليل الصيغة عند قراءة الملف.|
| [parsing_pivot_cached_records](/cells/python-net/ar/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | يشير إلى ما إذا كان سيتم تحليل السجلات المحورية المخزنة مؤقتًا عند تحميل الملف.<br/> القيمة الافتراضية هي كاذبة.|
| [language_code](/cells/python-net/ar/aspose.cells/htmlloadoptions/language_code) | الحصول على لغة واجهة المستخدم الخاصة بإصدار المصنف أو تعيينها بناءً على رمز البلد الذي قام بحفظ الملف.|
| [region](/cells/python-net/ar/aspose.cells/htmlloadoptions/region) |الحصول على إعدادات النظام الإقليمية أو تعيينها بناءً على رمز البلد في وقت تحميل الملف.|
| [default_style_settings](/cells/python-net/ar/aspose.cells/htmlloadoptions/default_style_settings) | الحصول على إعدادات النمط الافتراضية لتهيئة أنماط المصنف|
| [standard_font](/cells/python-net/ar/aspose.cells/htmlloadoptions/standard_font) | يضبط اسم الخط القياسي الافتراضي|
| [standard_font_size](/cells/python-net/ar/aspose.cells/htmlloadoptions/standard_font_size) | يضبط حجم الخط القياسي الافتراضي.|
| [interrupt_monitor](/cells/python-net/ar/aspose.cells/htmlloadoptions/interrupt_monitor) | الحصول على جهاز مراقبة المقاطعة وتعيينه.|
| [ignore_not_printed](/cells/python-net/ar/aspose.cells/htmlloadoptions/ignore_not_printed) | تجاهل البيانات التي لا تتم طباعتها في حالة طباعة الملف مباشرة|
| [check_data_valid](/cells/python-net/ar/aspose.cells/htmlloadoptions/check_data_valid) | تحقق مما إذا كانت البيانات صالحة في ملف القالب.|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells/htmlloadoptions/check_excel_restriction) | ما إذا كان يجب التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات ذات الصلة بالخلايا.<br/>على سبيل المثال، لا يسمح برنامج Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/>عند إدخال قيمة أطول من 32 كيلو مثل Cell.PutValue(string)، إذا كانت هذه الخاصية صحيحة، فسوف تحصل على استثناء.<br/>إذا كانت هذه الخاصية خاطئة، فسنقبل قيمة سلسلة الإدخال الخاصة بك كقيمة للخلية، وذلك لاحقًا<br/>يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV.<br/>ومع ذلك، إذا قمت بتعيين هذا النوع من القيمة غير الصالحة لتنسيق ملف Excel،<br/> يجب ألا تقوم بحفظ المصنف بتنسيق ملف Excel لاحقًا. وإلا فقد يكون هناك خطأ غير متوقع لملف Excel الذي تم إنشاؤه.|
| [keep_unparsed_data](/cells/python-net/ar/aspose.cells/htmlloadoptions/keep_unparsed_data) | ما إذا كان سيتم الاحتفاظ بالبيانات التي لم يتم تحليلها في الذاكرة للمصنف عند تحميله من ملف القالب. الافتراضي صحيح.|
| [load_filter](/cells/python-net/ar/aspose.cells/htmlloadoptions/load_filter) | عامل التصفية للإشارة إلى كيفية تحميل البيانات.|
| [light_cells_data_handler](/cells/python-net/ar/aspose.cells/htmlloadoptions/light_cells_data_handler) | معالج البيانات لمعالجة بيانات الخلايا عند قراءة ملف القالب.|
| [memory_setting](/cells/python-net/ar/aspose.cells/htmlloadoptions/memory_setting) | الحصول على أو تعيين خيارات استخدام الذاكرة.|
| [warning_callback](/cells/python-net/ar/aspose.cells/htmlloadoptions/warning_callback) | الحصول على رد اتصال تحذيري أو تعيينه.|
| [auto_fitter_options](/cells/python-net/ar/aspose.cells/htmlloadoptions/auto_fitter_options) | الحصول على خيارات المثبت التلقائي وتعيينها|
| [auto_filter](/cells/python-net/ar/aspose.cells/htmlloadoptions/auto_filter) | يشير إلى ما إذا كان سيتم تصفية البيانات تلقائيًا عند تحميل الملفات.|
| [font_configs](/cells/python-net/ar/aspose.cells/htmlloadoptions/font_configs) | الحصول على تكوينات الخطوط الفردية وتعيينها.<br/> يعمل فقط مع [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) الذي يستخدم [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions) للتحميل.|
| [ignore_useless_shapes](/cells/python-net/ar/aspose.cells/htmlloadoptions/ignore_useless_shapes) | يشير إلى ما إذا كان تجاهل الأشكال عديمة الفائدة.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ar/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | يشير إلى ما إذا كان سيتم الاحتفاظ بالمسافات وفواصل الأسطر المحشوة بين الرموز المميزة للصيغة<br/>أثناء الحصول على الصيغ وإعدادها.<br/> القيمة الافتراضية خاطئة.|
| [encoding](/cells/python-net/ar/aspose.cells/htmlloadoptions/encoding) |الحصول على الترميز الافتراضي وتعيينه. ينطبق فقط على ملف CSV.|
| [load_style_strategy](/cells/python-net/ar/aspose.cells/htmlloadoptions/load_style_strategy) | يشير إلى استراتيجية تطبيق النمط على القيم التي تم تحليلها عند تحويل قيمة السلسلة إلى رقم أو تاريخ.|
| [convert_numeric_data](/cells/python-net/ar/aspose.cells/htmlloadoptions/convert_numeric_data) | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت السلسلة الموجودة في الملف النصي قد تم تحويلها إلى بيانات رقمية.|
| [convert_date_time_data](/cells/python-net/ar/aspose.cells/htmlloadoptions/convert_date_time_data) | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت السلسلة الموجودة في ملف نصي قد تم تحويلها إلى بيانات تاريخ.|
| [keep_precision](/cells/python-net/ar/aspose.cells/htmlloadoptions/keep_precision) | يشير إلى ما إذا كان لا يمكن تحليل قيمة سلسلة إذا كان الطول 15.|
| [attached_files_directory](/cells/python-net/ar/aspose.cells/htmlloadoptions/attached_files_directory) | الدليل الذي سيتم حفظ الملفات المرفقة فيه.|
| [load_formulas](/cells/python-net/ar/aspose.cells/htmlloadoptions/load_formulas) | يشير إلى ما إذا كان سيتم استيراد الصيغ إذا كان ملف html الأصلي يحتوي على صيغ|
| [support_div_tag](/cells/python-net/ar/aspose.cells/htmlloadoptions/support_div_tag) |يشير إلى ما إذا كان يدعم تخطيط علامة `<div>` عندما يحتوي عليه ملف html.<br/> القيمة الافتراضية هي كاذبة.|
| [delete_redundant_spaces](/cells/python-net/ar/aspose.cells/htmlloadoptions/delete_redundant_spaces) | يشير إلى ما إذا كان سيتم حذف المسافات الزائدة عند التفاف النص للأسطر باستخدام علامة `<br>`.<br/> القيمة الافتراضية هي كاذبة.|
| [auto_fit_cols_and_rows](/cells/python-net/ar/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | يشير إلى ما إذا كان سيتم احتواء الأعمدة والصفوف تلقائيًا أم لا. القيمة الافتراضية هي كاذبة.|
| [convert_formulas_data](/cells/python-net/ar/aspose.cells/htmlloadoptions/convert_formulas_data) | إذا كان صحيحًا، فقم بتحويل السلسلة إلى صيغة عندما تبدأ قيمة السلسلة بالحرف '='، وتكون القيمة الافتراضية خاطئة.|
| [has_formula](/cells/python-net/ar/aspose.cells/htmlloadoptions/has_formula) | يشير إلى ما إذا كان النص عبارة عن صيغة إذا كان يبدأ بـ "=".|
| [stream_provider](/cells/python-net/ar/aspose.cells/htmlloadoptions/stream_provider) | الحصول على أو تعيين StreamProviderImportHtmlFile لاستيراد الكائنات.|
| [prog_id](/cells/python-net/ar/aspose.cells/htmlloadoptions/prog_id) | يحصل على معرف البرنامج لإنشاء الملف.<br/> فقط لملفات MHT.|
| [table_load_options](/cells/python-net/ar/aspose.cells/htmlloadoptions/table_load_options) | احصل على مثيل HtmlTableLoadOptionCollection|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_paper_size](/cells/python-net/ar/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | يضبط حجم ورق الطباعة الافتراضي من إعدادات الطابعة الافتراضية.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`AbstractTextLoadOptions`](/cells/python-net/ar/aspose.cells/abstracttextloadoptions)
* فئة [`HtmlLoadOptions`](/cells/python-net/ar/aspose.cells/htmlloadoptions)
* فئة [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
