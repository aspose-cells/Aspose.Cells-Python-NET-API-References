---
title: LoadOptions الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1020
url: /ar/aspose.cells/loadoptions/
is_root: false
---
##  LoadOptions الدرجة
يمثل خيارات تحميل الملف.



يكشف نوع LoadOptions الأعضاء التالية:

###  المنشئون
| البناء| وصف|
| :- | :- |
| [LoadOptions()](/cells/python-net/ar/aspose.cells/loadoptions/__init__/#) | ينشئ خيارات لتحميل الملف.|
| [LoadOptions(load_format)](/cells/python-net/ar/aspose.cells/loadoptions/__init__/#LoadFormat) | ينشئ خيارات لتحميل الملف.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [load_format](/cells/python-net/ar/aspose.cells/loadoptions/load_format) | يحصل على تنسيق التحميل.|
| [password](/cells/python-net/ar/aspose.cells/loadoptions/password) | الحصول على كلمة المرور الخاصة بالمصنف وتعيينها.|
| [parsing_formula_on_open](/cells/python-net/ar/aspose.cells/loadoptions/parsing_formula_on_open) | يشير إلى ما إذا كان سيتم تحليل الصيغة عند قراءة الملف.|
| [parsing_pivot_cached_records](/cells/python-net/ar/aspose.cells/loadoptions/parsing_pivot_cached_records) | يشير إلى ما إذا كان تحليل السجلات المحورية المخزنة مؤقتًا عند تحميل الملف.<br/> القيمة الافتراضية هي كاذبة.|
| [language_code](/cells/python-net/ar/aspose.cells/loadoptions/language_code) | الحصول على أو تعيين لغة واجهة المستخدم لإصدار المصنف بناءً على كود البلد الذي حفظ الملف.|
| [region](/cells/python-net/ar/aspose.cells/loadoptions/region) | الحصول على أو تعيين الإعدادات الإقليمية للنظام بناءً على رمز البلد في وقت تحميل الملف.|
| [default_style_settings](/cells/python-net/ar/aspose.cells/loadoptions/default_style_settings) | الحصول على إعدادات النمط الافتراضية لتهيئة أنماط المصنف|
| [standard_font](/cells/python-net/ar/aspose.cells/loadoptions/standard_font) | يعيّن اسم الخط القياسي الافتراضي|
| [standard_font_size](/cells/python-net/ar/aspose.cells/loadoptions/standard_font_size) | يعيّن حجم الخط القياسي الافتراضي.|
| [interrupt_monitor](/cells/python-net/ar/aspose.cells/loadoptions/interrupt_monitor) | يحصل على جهاز مراقبة المقاطعة ويضبطه.|
| [ignore_not_printed](/cells/python-net/ar/aspose.cells/loadoptions/ignore_not_printed) | تجاهل البيانات التي لم تتم طباعتها إذا قمت بطباعة الملف مباشرة|
| [check_data_valid](/cells/python-net/ar/aspose.cells/loadoptions/check_data_valid) |تحقق مما إذا كانت البيانات صالحة في ملف القالب.|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells/loadoptions/check_excel_restriction) | ما إذا كان التحقق من تقييد ملف Excel عند تعديل المستخدم للكائنات ذات الصلة بالخلايا.<br/>على سبيل المثال ، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/>عند إدخال قيمة أطول من 32 كيلو بايت مثل Cell.PutValue (سلسلة) ، إذا كانت هذه الخاصية صحيحة ، فستحصل على استثناء.<br/>إذا كانت هذه الخاصية خاطئة ، فسنقبل قيمة سلسلة الإدخال كقيمة للخلية حتى يتم ذلك لاحقًا<br/>يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات ملفات أخرى مثل CSV.<br/>ومع ذلك ، إذا قمت بتعيين مثل هذا النوع من القيمة غير الصالحة لتنسيق ملف Excel ،<br/> يجب ألا تحفظ المصنف بتنسيق ملف excel لاحقًا. وإلا فقد يكون هناك خطأ غير متوقع لملف Excel الذي تم إنشاؤه.|
| [keep_unparsed_data](/cells/python-net/ar/aspose.cells/loadoptions/keep_unparsed_data) | ما إذا كان سيتم الاحتفاظ بالبيانات التي لم يتم تحليلها في الذاكرة للمصنف عند تحميله من ملف القالب أم لا. الافتراضي هو الصحيح.|
| [load_filter](/cells/python-net/ar/aspose.cells/loadoptions/load_filter) | عامل التصفية للدلالة على كيفية تحميل البيانات.|
| [light_cells_data_handler](/cells/python-net/ar/aspose.cells/loadoptions/light_cells_data_handler) | معالج البيانات لمعالجة بيانات الخلايا عند قراءة ملف القالب.|
| [memory_setting](/cells/python-net/ar/aspose.cells/loadoptions/memory_setting) | الحصول على أو تعيين خيارات استخدام الذاكرة.|
| [warning_callback](/cells/python-net/ar/aspose.cells/loadoptions/warning_callback) | يحصل أو يحدد رد الاتصال التحذيري.|
| [auto_fitter_options](/cells/python-net/ar/aspose.cells/loadoptions/auto_fitter_options) | الحصول على خيارات التركيب التلقائي وتعيينها|
| [auto_filter](/cells/python-net/ar/aspose.cells/loadoptions/auto_filter) | يشير إلى ما إذا كانت التصفية التلقائية للبيانات عند تحميل الملفات.|
| [font_configs](/cells/python-net/ar/aspose.cells/loadoptions/font_configs) | يحصل ويضبط تكوينات الخطوط الفردية.<br/> يعمل فقط مع [Workbook](/cells/python-net/ar/aspose.cells/workbook) الذي يستخدم [LoadOptions](/cells/python-net/ar/aspose.cells/loadoptions) للتحميل.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/ar/aspose.cells/loadoptions/set_paper_size/#PaperSizeType) | يضبط حجم ورق الطباعة الافتراضي من إعداد الطابعة الافتراضية.|



###  أنظر أيضا
* وحدة [aspose.cells](..)
* فئة [LoadOptions](/cells/python-net/ar/aspose.cells/loadoptions)
* فئة [Workbook](/cells/python-net/ar/aspose.cells/workbook)
