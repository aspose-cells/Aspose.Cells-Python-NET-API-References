---
title: TxtLoadOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1490
url: /ar/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions صف
يمثل خيارات تحميل ملف نصي.



**الميراث:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)



يكشف النوع TxtLoadOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/txtloadoptions/__init__/#) | إنشاء خيارات لتحميل ملف نصي.|
| [`__init__(self, load_format)`](/cells/python-net/ar/aspose.cells/txtloadoptions/__init__/#aspose.cells.loadformat) | إنشاء خيارات لتحميل ملف نصي.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [load_format](/cells/python-net/ar/aspose.cells/txtloadoptions/load_format) | يحصل على تنسيق التحميل.|
| [password](/cells/python-net/ar/aspose.cells/txtloadoptions/password) | يحصل على كلمة المرور الخاصة بالمصنف ويقوم بتعيينها.|
| [parsing_formula_on_open](/cells/python-net/ar/aspose.cells/txtloadoptions/parsing_formula_on_open) | يشير إلى ما إذا كان يتم تحليل الصيغة عند قراءة الملف.|
| [parsing_pivot_cached_records](/cells/python-net/ar/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | يشير إلى ما إذا كان يتم تحليل السجلات المخزنة مؤقتًا عند تحميل الملف.<br/> القيمة الافتراضية هي false.|
| [language_code](/cells/python-net/ar/aspose.cells/txtloadoptions/language_code) | يحصل على لغة واجهة المستخدم لإصدار المصنف أو يعينها استنادًا إلى رمز البلد الذي حفظ الملف.|
| [region](/cells/python-net/ar/aspose.cells/txtloadoptions/region) | يحصل على أو يعين الإعدادات الإقليمية المستخدمة في المصنف الذي سيتم تحميله.|
| [default_style_settings](/cells/python-net/ar/aspose.cells/txtloadoptions/default_style_settings) | يحصل على إعدادات النمط الافتراضية لتهيئة أنماط المصنف|
| [standard_font](/cells/python-net/ar/aspose.cells/txtloadoptions/standard_font) | تعيين اسم الخط القياسي الافتراضي|
| [standard_font_size](/cells/python-net/ar/aspose.cells/txtloadoptions/standard_font_size) | تعيين حجم الخط القياسي الافتراضي.|
| [ignore_not_printed](/cells/python-net/ar/aspose.cells/txtloadoptions/ignore_not_printed) | تجاهل البيانات التي لم تتم طباعتها إذا قمت بطباعة الملف مباشرة|
| [check_data_valid](/cells/python-net/ar/aspose.cells/txtloadoptions/check_data_valid) | التحقق من صحة البيانات الموجودة في ملف القالب.|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells/txtloadoptions/check_excel_restriction) | ما إذا كان يتم التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات المرتبطة بالخلايا.<br/>على سبيل المثال، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/>عندما تقوم بإدخال قيمة أطول من 32 كيلو بايت مثل Cell.PutValue(string)، إذا كانت هذه الخاصية صحيحة، فسوف تحصل على استثناء.<br/>إذا كانت هذه الخاصية خاطئة، فسنقبل قيمة السلسلة المدخلة كقيمة للخلية حتى نتمكن لاحقًا من<br/>يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV.<br/>ومع ذلك، إذا قمت بتعيين مثل هذا النوع من القيمة غير صالح لتنسيق ملف Excel،<br/>لا تحفظ المصنف بصيغة ملف إكسل لاحقًا، وإلا فقد يحدث خطأ غير متوقع في ملف إكسل الناتج.|
| [keep_unparsed_data](/cells/python-net/ar/aspose.cells/txtloadoptions/keep_unparsed_data) | هل سيتم الاحتفاظ بالبيانات غير المُحلَّلة في ذاكرة المصنف عند تحميلها من ملف القالب؟ الإعداد الافتراضي هو "صحيح".|
| [load_filter](/cells/python-net/ar/aspose.cells/txtloadoptions/load_filter) | الفلتر الذي يشير إلى كيفية تحميل البيانات.|
| [memory_setting](/cells/python-net/ar/aspose.cells/txtloadoptions/memory_setting) | يحصل على وضع الذاكرة لكتاب العمل المحمّل أو يعيّنه.|
| [auto_fitter_options](/cells/python-net/ar/aspose.cells/txtloadoptions/auto_fitter_options) | يحصل على خيارات التركيب التلقائي ويقوم بتعيينها|
| [auto_filter](/cells/python-net/ar/aspose.cells/txtloadoptions/auto_filter) | يشير إلى ما إذا كان يتم تصفية البيانات تلقائيًا عند تحميل الملفات.|
| [font_configs](/cells/python-net/ar/aspose.cells/txtloadoptions/font_configs) | يحصل على تكوينات الخطوط الفردية ويقوم بتعيينها.<br/> يعمل فقط مع [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) الذي يستخدم هذا [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions) للتحميل.|
| [ignore_useless_shapes](/cells/python-net/ar/aspose.cells/txtloadoptions/ignore_useless_shapes) | يشير إلى ما إذا كان يتم تجاهل الأشكال غير المفيدة.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ar/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | يشير إلى ما إذا كان سيتم الحفاظ على تلك المسافات وفواصل الأسطر المبطنة بين رموز الصيغة<br/>أثناء الحصول على الصيغ وتعيينها.<br/> القيمة الافتراضية هي false.|
| [encoding](/cells/python-net/ar/aspose.cells/txtloadoptions/encoding) | يحصل على الترميز الافتراضي ويضبطه. ينطبق فقط على ملفات csv.|
| [load_style_strategy](/cells/python-net/ar/aspose.cells/txtloadoptions/load_style_strategy) | يشير إلى الإستراتيجية لتطبيق النمط على القيم المحللة عند تحويل قيمة السلسلة إلى رقم أو تاريخ ووقت.|
| [convert_numeric_data](/cells/python-net/ar/aspose.cells/txtloadoptions/convert_numeric_data) |يحصل على قيمة أو يعينها تشير إلى ما إذا كان يتم تحويل السلسلة في ملف نصي إلى بيانات رقمية.|
| [convert_date_time_data](/cells/python-net/ar/aspose.cells/txtloadoptions/convert_date_time_data) | يحصل على قيمة أو يعينها تشير إلى ما إذا كان يتم تحويل السلسلة في ملف النص إلى بيانات تاريخ.|
| [keep_precision](/cells/python-net/ar/aspose.cells/txtloadoptions/keep_precision) | يشير إلى ما إذا كان سيتم تحليل قيمة السلسلة إذا كان الطول 15.|
| [separator](/cells/python-net/ar/aspose.cells/txtloadoptions/separator) | يحصل على فاصل الأحرف لملف النص ويقوم بتعيينه.|
| [separator_string](/cells/python-net/ar/aspose.cells/txtloadoptions/separator_string) | يحصل على قيمة سلسلة ويعينها كفاصل.|
| [is_multi_encoded](/cells/python-net/ar/aspose.cells/txtloadoptions/is_multi_encoded) | صحيح يعني أن الملف يحتوي على عدة ترميزات.|
| [preferred_parsers](/cells/python-net/ar/aspose.cells/txtloadoptions/preferred_parsers) | يحصل على محللات القيمة المفضلة ويقوم بتعيينها لتحميل ملف النص.|
| [has_formula](/cells/python-net/ar/aspose.cells/txtloadoptions/has_formula) | يشير إلى ما إذا كان النص عبارة عن صيغة إذا بدأ بـ "=".|
| [has_text_qualifier](/cells/python-net/ar/aspose.cells/txtloadoptions/has_text_qualifier) | هل يوجد مُؤهل نصي لقيمة الخلية؟ الإعداد الافتراضي هو "صحيح".|
| [text_qualifier](/cells/python-net/ar/aspose.cells/txtloadoptions/text_qualifier) | يُحدد مُؤهل النص لقيم الخلايا. المُؤهل الافتراضي هو '"'.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/ar/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | ما إذا كان ينبغي التعامل مع الفواصل المتتالية باعتبارها واحدة.|
| [treat_quote_prefix_as_value](/cells/python-net/ar/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | يشير إلى ما إذا كان ينبغي اعتبار علامة الاقتباس المفردة الرئيسية جزءًا من قيمة خلية واحدة.<br/>القيمة الافتراضية هي "صحيح". إذا كانت خاطئة، فسيتم إزالة علامة الاقتباس المفردة من قيمة الخلية المقابلة.<br/> وسيتم تعيين [`Style.quote_prefix`](/cells/python-net/ar/aspose.cells/style#quote_prefix) على أنه صحيح للخلية.|
| [extend_to_next_sheet](/cells/python-net/ar/aspose.cells/txtloadoptions/extend_to_next_sheet) | ما إذا كان سيتم تمديد البيانات إلى الورقة التالية عندما تتجاوز الصفوف أو الأعمدة من البيانات الحد الأقصى.<br/> الإفتراضي هو خطأ.|
| [header_rows_count](/cells/python-net/ar/aspose.cells/txtloadoptions/header_rows_count) |عدد صفوف الرأس التي يجب تكرارها للأوراق الممتدة.|
| [header_columns_count](/cells/python-net/ar/aspose.cells/txtloadoptions/header_columns_count) | عدد أعمدة الرأس التي يجب تكرارها للأوراق الممتدة.|
| [max_row_count](/cells/python-net/ar/aspose.cells/txtloadoptions/max_row_count) | الحد الأقصى لعدد الصفوف التي سيتم استيرادها لورقة واحدة.|
| [max_column_count](/cells/python-net/ar/aspose.cells/txtloadoptions/max_column_count) | الحد الأقصى لعدد الأعمدة التي سيتم استيرادها لورقة واحدة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/ar/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.papersizetype) | تعيين حجم ورق الطباعة الافتراضي من إعدادات الطابعة الافتراضية.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`AbstractTextLoadOptions`](/cells/python-net/ar/aspose.cells/abstracttextloadoptions)
* فئة [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)
* فئة [`TxtLoadOptions`](/cells/python-net/ar/aspose.cells/txtloadoptions)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
