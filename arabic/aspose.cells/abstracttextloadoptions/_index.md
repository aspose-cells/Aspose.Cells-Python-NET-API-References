---
title: AbstractTextLoadOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells/abstracttextloadoptions/
is_root: false
---
##  AbstractTextLoadOptions صف
الخيارات الشائعة لتحميل القيم النصية



**ميراث:** [`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)



يكشف النوع AbstractTextLoadOptions عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [load_format](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/load_format) | يحصل على تنسيق التحميل.|
| [password](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/password) | الحصول على كلمة المرور الخاصة بالمصنف وتعيينها.|
| [parsing_formula_on_open](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/parsing_formula_on_open) | يشير إلى ما إذا كان سيتم تحليل الصيغة عند قراءة الملف.|
| [parsing_pivot_cached_records](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/parsing_pivot_cached_records) | يشير إلى ما إذا كان سيتم تحليل السجلات المحورية المخزنة مؤقتًا عند تحميل الملف.<br/> القيمة الافتراضية هي كاذبة.|
| [language_code](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/language_code) | الحصول على لغة واجهة المستخدم الخاصة بإصدار المصنف أو تعيينها بناءً على رمز البلد الذي قام بحفظ الملف.|
| [region](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/region) |الحصول على إعدادات النظام الإقليمية أو تعيينها بناءً على رمز البلد في وقت تحميل الملف.|
| [default_style_settings](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/default_style_settings) | الحصول على إعدادات النمط الافتراضية لتهيئة أنماط المصنف|
| [standard_font](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/standard_font) | يضبط اسم الخط القياسي الافتراضي|
| [standard_font_size](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/standard_font_size) | يضبط حجم الخط القياسي الافتراضي.|
| [interrupt_monitor](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/interrupt_monitor) | الحصول على جهاز مراقبة المقاطعة وتعيينه.|
| [ignore_not_printed](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/ignore_not_printed) | تجاهل البيانات التي لا تتم طباعتها في حالة طباعة الملف مباشرة|
| [check_data_valid](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/check_data_valid) | تحقق مما إذا كانت البيانات صالحة في ملف القالب.|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/check_excel_restriction) | ما إذا كان يجب التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات ذات الصلة بالخلايا.<br/>على سبيل المثال، لا يسمح برنامج Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/>عند إدخال قيمة أطول من 32 كيلو مثل Cell.PutValue(string)، إذا كانت هذه الخاصية صحيحة، فسوف تحصل على استثناء.<br/>إذا كانت هذه الخاصية خاطئة، فسنقبل قيمة سلسلة الإدخال الخاصة بك كقيمة للخلية، وذلك لاحقًا<br/>يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV.<br/>ومع ذلك، إذا قمت بتعيين هذا النوع من القيمة غير الصالحة لتنسيق ملف Excel،<br/> يجب ألا تقوم بحفظ المصنف بتنسيق ملف Excel لاحقًا. وإلا فقد يكون هناك خطأ غير متوقع لملف Excel الذي تم إنشاؤه.|
| [keep_unparsed_data](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/keep_unparsed_data) | ما إذا كان سيتم الاحتفاظ بالبيانات التي لم يتم تحليلها في الذاكرة للمصنف عند تحميله من ملف القالب. الافتراضي صحيح.|
| [load_filter](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/load_filter) | عامل التصفية للإشارة إلى كيفية تحميل البيانات.|
| [light_cells_data_handler](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/light_cells_data_handler) | معالج البيانات لمعالجة بيانات الخلايا عند قراءة ملف القالب.|
| [memory_setting](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/memory_setting) | الحصول على أو تعيين خيارات استخدام الذاكرة.|
| [warning_callback](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/warning_callback) | الحصول على رد اتصال تحذيري أو تعيينه.|
| [auto_fitter_options](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/auto_fitter_options) | الحصول على خيارات المثبت التلقائي وتعيينها|
| [auto_filter](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/auto_filter) | يشير إلى ما إذا كان سيتم تصفية البيانات تلقائيًا عند تحميل الملفات.|
| [font_configs](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/font_configs) | الحصول على تكوينات الخطوط الفردية وتعيينها.<br/> يعمل فقط مع [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) الذي يستخدم [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions) للتحميل.|
| [ignore_useless_shapes](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/ignore_useless_shapes) | يشير إلى ما إذا كان تجاهل الأشكال عديمة الفائدة.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/preserve_padding_spaces_in_formula) | يشير إلى ما إذا كان سيتم الاحتفاظ بالمسافات وفواصل الأسطر المحشوة بين الرموز المميزة للصيغة<br/>أثناء الحصول على الصيغ وإعدادها.<br/> القيمة الافتراضية خاطئة.|
| [encoding](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/encoding) |الحصول على الترميز الافتراضي وتعيينه. ينطبق فقط على ملف CSV.|
| [load_style_strategy](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/load_style_strategy) | يشير إلى استراتيجية تطبيق النمط على القيم التي تم تحليلها عند تحويل قيمة السلسلة إلى رقم أو تاريخ.|
| [convert_numeric_data](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/convert_numeric_data) | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت السلسلة الموجودة في الملف النصي قد تم تحويلها إلى بيانات رقمية.|
| [convert_date_time_data](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/convert_date_time_data) | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت السلسلة الموجودة في ملف نصي قد تم تحويلها إلى بيانات تاريخ.|
| [keep_precision](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/keep_precision) | يشير إلى ما إذا كان لا يمكن تحليل قيمة سلسلة إذا كان الطول 15.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_paper_size](/cells/python-net/ar/aspose.cells/abstracttextloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | يضبط حجم ورق الطباعة الافتراضي من إعدادات الطابعة الافتراضية.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`AbstractTextLoadOptions`](/cells/python-net/ar/aspose.cells/abstracttextloadoptions)
* فئة [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
