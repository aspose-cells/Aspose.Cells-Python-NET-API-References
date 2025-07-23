---
title: EbookLoadOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 520
url: /ar/aspose.cells/ebookloadoptions/
is_root: false
---
##  EbookLoadOptions صف
يمثل الخيارات عند استيراد ملف الكتاب الإلكتروني.



**الميراث:** [`EbookLoadOptions`](/cells/python-net/aspose.cells/ebookloadoptions) → 
[`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)



يكشف النوع EbookLoadOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/ebookloadoptions/__init__/#) | إنشاء خيارات لتحميل ملف الكتاب الإلكتروني.|
| [`__init__(self, load_format)`](/cells/python-net/ar/aspose.cells/ebookloadoptions/__init__/#aspose.cells.loadformat) | إنشاء خيارات لتحميل ملف الكتاب الإلكتروني.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [load_format](/cells/python-net/ar/aspose.cells/ebookloadoptions/load_format) | يحصل على تنسيق التحميل.|
| [password](/cells/python-net/ar/aspose.cells/ebookloadoptions/password) | يحصل على كلمة المرور الخاصة بالمصنف ويقوم بتعيينها.|
| [parsing_formula_on_open](/cells/python-net/ar/aspose.cells/ebookloadoptions/parsing_formula_on_open) | يشير إلى ما إذا كان يتم تحليل الصيغة عند قراءة الملف.|
| [parsing_pivot_cached_records](/cells/python-net/ar/aspose.cells/ebookloadoptions/parsing_pivot_cached_records) | يشير إلى ما إذا كان يتم تحليل السجلات المخزنة مؤقتًا عند تحميل الملف.<br/> القيمة الافتراضية هي false.|
| [language_code](/cells/python-net/ar/aspose.cells/ebookloadoptions/language_code) | يحصل على لغة واجهة المستخدم لإصدار المصنف أو يعينها استنادًا إلى رمز البلد الذي حفظ الملف.|
| [region](/cells/python-net/ar/aspose.cells/ebookloadoptions/region) | يحصل على أو يعين الإعدادات الإقليمية المستخدمة في المصنف الذي سيتم تحميله.|
| [default_style_settings](/cells/python-net/ar/aspose.cells/ebookloadoptions/default_style_settings) | يحصل على إعدادات النمط الافتراضية لتهيئة أنماط المصنف|
| [standard_font](/cells/python-net/ar/aspose.cells/ebookloadoptions/standard_font) | تعيين اسم الخط القياسي الافتراضي|
| [standard_font_size](/cells/python-net/ar/aspose.cells/ebookloadoptions/standard_font_size) | تعيين حجم الخط القياسي الافتراضي.|
| [ignore_not_printed](/cells/python-net/ar/aspose.cells/ebookloadoptions/ignore_not_printed) | تجاهل البيانات التي لم تتم طباعتها إذا قمت بطباعة الملف مباشرة|
| [check_data_valid](/cells/python-net/ar/aspose.cells/ebookloadoptions/check_data_valid) | التحقق من صحة البيانات الموجودة في ملف القالب.|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells/ebookloadoptions/check_excel_restriction) | ما إذا كان يتم التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات المرتبطة بالخلايا.<br/>على سبيل المثال، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/>عندما تقوم بإدخال قيمة أطول من 32 كيلو بايت مثل Cell.PutValue(string)، إذا كانت هذه الخاصية صحيحة، فسوف تحصل على استثناء.<br/>إذا كانت هذه الخاصية خاطئة، فسنقبل قيمة السلسلة المدخلة كقيمة للخلية حتى نتمكن لاحقًا من<br/>يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV.<br/>ومع ذلك، إذا قمت بتعيين مثل هذا النوع من القيمة غير صالح لتنسيق ملف Excel،<br/>لا تحفظ المصنف بصيغة ملف إكسل لاحقًا، وإلا فقد يحدث خطأ غير متوقع في ملف إكسل الناتج.|
| [keep_unparsed_data](/cells/python-net/ar/aspose.cells/ebookloadoptions/keep_unparsed_data) | هل سيتم الاحتفاظ بالبيانات غير المُحلَّلة في ذاكرة المصنف عند تحميلها من ملف القالب؟ الإعداد الافتراضي هو "صحيح".|
| [load_filter](/cells/python-net/ar/aspose.cells/ebookloadoptions/load_filter) | الفلتر الذي يشير إلى كيفية تحميل البيانات.|
| [memory_setting](/cells/python-net/ar/aspose.cells/ebookloadoptions/memory_setting) | يحصل على وضع الذاكرة لكتاب العمل المحمّل أو يعيّنه.|
| [auto_fitter_options](/cells/python-net/ar/aspose.cells/ebookloadoptions/auto_fitter_options) | يحصل على خيارات التركيب التلقائي ويقوم بتعيينها|
| [auto_filter](/cells/python-net/ar/aspose.cells/ebookloadoptions/auto_filter) | يشير إلى ما إذا كان يتم تصفية البيانات تلقائيًا عند تحميل الملفات.|
| [font_configs](/cells/python-net/ar/aspose.cells/ebookloadoptions/font_configs) | يحصل على تكوينات الخطوط الفردية ويقوم بتعيينها.<br/> يعمل فقط مع [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) الذي يستخدم هذا [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions) للتحميل.|
| [ignore_useless_shapes](/cells/python-net/ar/aspose.cells/ebookloadoptions/ignore_useless_shapes) | يشير إلى ما إذا كان يتم تجاهل الأشكال غير المفيدة.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ar/aspose.cells/ebookloadoptions/preserve_padding_spaces_in_formula) | يشير إلى ما إذا كان سيتم الحفاظ على تلك المسافات وفواصل الأسطر المبطنة بين رموز الصيغة<br/>أثناء الحصول على الصيغ وتعيينها.<br/> القيمة الافتراضية هي false.|
| [encoding](/cells/python-net/ar/aspose.cells/ebookloadoptions/encoding) | يحصل على الترميز الافتراضي ويضبطه. ينطبق فقط على ملفات csv.|
| [load_style_strategy](/cells/python-net/ar/aspose.cells/ebookloadoptions/load_style_strategy) | يشير إلى الإستراتيجية لتطبيق النمط على القيم المحللة عند تحويل قيمة السلسلة إلى رقم أو تاريخ ووقت.|
| [convert_numeric_data](/cells/python-net/ar/aspose.cells/ebookloadoptions/convert_numeric_data) |يحصل على قيمة أو يعينها تشير إلى ما إذا كان يتم تحويل السلسلة في ملف نصي إلى بيانات رقمية.|
| [convert_date_time_data](/cells/python-net/ar/aspose.cells/ebookloadoptions/convert_date_time_data) | يحصل على قيمة أو يعينها تشير إلى ما إذا كان يتم تحويل السلسلة في ملف النص إلى بيانات تاريخ.|
| [keep_precision](/cells/python-net/ar/aspose.cells/ebookloadoptions/keep_precision) | يشير إلى ما إذا كان سيتم تحليل قيمة السلسلة إذا كان الطول 15.|
| [attached_files_directory](/cells/python-net/ar/aspose.cells/ebookloadoptions/attached_files_directory) | الدليل الذي سيتم حفظ الملفات المرفقة فيه.|
| [load_formulas](/cells/python-net/ar/aspose.cells/ebookloadoptions/load_formulas) | يشير إلى ما إذا كان يتم استيراد الصيغ إذا كان ملف HTML الأصلي يحتوي على صيغ|
| [support_div_tag](/cells/python-net/ar/aspose.cells/ebookloadoptions/support_div_tag) | يشير إلى ما إذا كان يدعم تخطيط العلامة `<div>` عندما يحتوي ملف html عليها.<br/> القيمة الافتراضية هي false.|
| [delete_redundant_spaces](/cells/python-net/ar/aspose.cells/ebookloadoptions/delete_redundant_spaces) | يشير إلى ما إذا كان سيتم حذف المسافات الزائدة عند التفاف النص حول الأسطر باستخدام العلامة `<br>`.<br/> القيمة الافتراضية هي false.|
| [auto_fit_cols_and_rows](/cells/python-net/ar/aspose.cells/ebookloadoptions/auto_fit_cols_and_rows) | يُشير إلى إمكانية ملاءمة الأعمدة والصفوف تلقائيًا. القيمة الافتراضية هي خطأ.|
| [convert_formulas_data](/cells/python-net/ar/aspose.cells/ebookloadoptions/convert_formulas_data) |إذا كانت القيمة صحيحة، قم بتحويل السلسلة إلى صيغة عندما تبدأ قيمة السلسلة بالحرف '='، والقيمة الافتراضية هي false.|
| [has_formula](/cells/python-net/ar/aspose.cells/ebookloadoptions/has_formula) | يشير إلى ما إذا كان النص عبارة عن صيغة إذا بدأ بـ "=".|
| [prog_id](/cells/python-net/ar/aspose.cells/ebookloadoptions/prog_id) | يحصل على معرف البرنامج الذي يقوم بإنشاء الملف.<br/> فقط لملفات MHT.|
| [table_load_options](/cells/python-net/ar/aspose.cells/ebookloadoptions/table_load_options) | احصل على مثيل HtmlTableLoadOptionCollection|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/ar/aspose.cells/ebookloadoptions/set_paper_size/#aspose.cells.papersizetype) | تعيين حجم ورق الطباعة الافتراضي من إعدادات الطابعة الافتراضية.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`AbstractTextLoadOptions`](/cells/python-net/ar/aspose.cells/abstracttextloadoptions)
* فئة [`EbookLoadOptions`](/cells/python-net/ar/aspose.cells/ebookloadoptions)
* فئة [`HtmlLoadOptions`](/cells/python-net/ar/aspose.cells/htmlloadoptions)
* فئة [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
