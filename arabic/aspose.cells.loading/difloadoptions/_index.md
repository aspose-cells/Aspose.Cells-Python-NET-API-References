---
title: DifLoadOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.loading/difloadoptions/
is_root: false
---
##  DifLoadOptions صف
يمثل خيارات تحميل ملف .dif.



**الميراث:** [`DifLoadOptions`](/cells/python-net/aspose.cells.loading/difloadoptions) → 
[`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)



يكشف النوع DifLoadOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.loading/difloadoptions/__init__/#) | الخيارات.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [load_format](/cells/python-net/ar/aspose.cells.loading/difloadoptions/load_format) | يحصل على تنسيق التحميل.|
| [password](/cells/python-net/ar/aspose.cells.loading/difloadoptions/password) | يحصل على كلمة المرور الخاصة بالمصنف ويقوم بتعيينها.|
| [parsing_formula_on_open](/cells/python-net/ar/aspose.cells.loading/difloadoptions/parsing_formula_on_open) | يشير إلى ما إذا كان يتم تحليل الصيغة عند قراءة الملف.|
| [parsing_pivot_cached_records](/cells/python-net/ar/aspose.cells.loading/difloadoptions/parsing_pivot_cached_records) | يشير إلى ما إذا كان يتم تحليل السجلات المخزنة مؤقتًا عند تحميل الملف.<br/> القيمة الافتراضية هي false.|
| [language_code](/cells/python-net/ar/aspose.cells.loading/difloadoptions/language_code) | يحصل على لغة واجهة المستخدم لإصدار المصنف أو يعينها استنادًا إلى رمز البلد الذي حفظ الملف.|
| [region](/cells/python-net/ar/aspose.cells.loading/difloadoptions/region) | يحصل على أو يعين الإعدادات الإقليمية المستخدمة في المصنف الذي سيتم تحميله.|
| [default_style_settings](/cells/python-net/ar/aspose.cells.loading/difloadoptions/default_style_settings) | يحصل على إعدادات النمط الافتراضية لتهيئة أنماط المصنف|
| [standard_font](/cells/python-net/ar/aspose.cells.loading/difloadoptions/standard_font) | تعيين اسم الخط القياسي الافتراضي|
| [standard_font_size](/cells/python-net/ar/aspose.cells.loading/difloadoptions/standard_font_size) | تعيين حجم الخط القياسي الافتراضي.|
| [ignore_not_printed](/cells/python-net/ar/aspose.cells.loading/difloadoptions/ignore_not_printed) | تجاهل البيانات التي لم تتم طباعتها إذا قمت بطباعة الملف مباشرة|
| [check_data_valid](/cells/python-net/ar/aspose.cells.loading/difloadoptions/check_data_valid) | التحقق من صحة البيانات الموجودة في ملف القالب.|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells.loading/difloadoptions/check_excel_restriction) | ما إذا كان يتم التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات المرتبطة بالخلايا.<br/>على سبيل المثال، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/>عندما تقوم بإدخال قيمة أطول من 32 كيلو بايت مثل Cell.PutValue(string)، إذا كانت هذه الخاصية صحيحة، فسوف تحصل على استثناء.<br/>إذا كانت هذه الخاصية خاطئة، فسنقبل قيمة السلسلة المدخلة كقيمة للخلية حتى نتمكن لاحقًا من<br/>يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV.<br/>ومع ذلك، إذا قمت بتعيين مثل هذا النوع من القيمة غير صالح لتنسيق ملف Excel،<br/>لا تحفظ المصنف بصيغة ملف إكسل لاحقًا، وإلا فقد يحدث خطأ غير متوقع في ملف إكسل الناتج.|
| [keep_unparsed_data](/cells/python-net/ar/aspose.cells.loading/difloadoptions/keep_unparsed_data) | هل سيتم الاحتفاظ بالبيانات غير المُحلَّلة في ذاكرة المصنف عند تحميلها من ملف القالب؟ الإعداد الافتراضي هو "صحيح".|
| [load_filter](/cells/python-net/ar/aspose.cells.loading/difloadoptions/load_filter) | الفلتر الذي يشير إلى كيفية تحميل البيانات.|
| [memory_setting](/cells/python-net/ar/aspose.cells.loading/difloadoptions/memory_setting) | يحصل على وضع الذاكرة لكتاب العمل المحمّل أو يعيّنه.|
| [auto_fitter_options](/cells/python-net/ar/aspose.cells.loading/difloadoptions/auto_fitter_options) | يحصل على خيارات التركيب التلقائي ويقوم بتعيينها|
| [auto_filter](/cells/python-net/ar/aspose.cells.loading/difloadoptions/auto_filter) | يشير إلى ما إذا كان يتم تصفية البيانات تلقائيًا عند تحميل الملفات.|
| [font_configs](/cells/python-net/ar/aspose.cells.loading/difloadoptions/font_configs) | يحصل على تكوينات الخطوط الفردية ويقوم بتعيينها.<br/> يعمل فقط مع [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) الذي يستخدم هذا [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions) للتحميل.|
| [ignore_useless_shapes](/cells/python-net/ar/aspose.cells.loading/difloadoptions/ignore_useless_shapes) | يشير إلى ما إذا كان يتم تجاهل الأشكال غير المفيدة.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ar/aspose.cells.loading/difloadoptions/preserve_padding_spaces_in_formula) | يشير إلى ما إذا كان سيتم الحفاظ على تلك المسافات وفواصل الأسطر المبطنة بين رموز الصيغة<br/>أثناء الحصول على الصيغ وتعيينها.<br/> القيمة الافتراضية هي false.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/ar/aspose.cells.loading/difloadoptions/set_paper_size/#aspose.cells.papersizetype) | تعيين حجم ورق الطباعة الافتراضي من إعدادات الطابعة الافتراضية.|



###  أنظر أيضا
* الوحدة [`aspose.cells.loading`](..)
* فئة [`DifLoadOptions`](/cells/python-net/ar/aspose.cells.loading/difloadoptions)
* فئة [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
