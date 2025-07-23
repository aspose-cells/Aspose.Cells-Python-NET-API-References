---
title: TxtSaveOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1500
url: /ar/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions صف
يمثل خيارات الحفظ لتنسيق csv/المحدد بعلامات التبويب/تنسيق نص آخر.



**الميراث:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)



يكشف النوع TxtSaveOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/txtsaveoptions/__init__/#) | إنشاء خيارات حفظ ملف نصي.|
| [`__init__(self, save_format)`](/cells/python-net/ar/aspose.cells/txtsaveoptions/__init__/#aspose.cells.saveformat) | إنشاء خيارات حفظ ملف نصي.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells/txtsaveoptions/save_format) | يحصل على تنسيق ملف الحفظ.|
| [clear_data](/cells/python-net/ar/aspose.cells/txtsaveoptions/clear_data) | اجعل المصنف فارغًا بعد حفظ الملف.|
| [cached_file_folder](/cells/python-net/ar/aspose.cells/txtsaveoptions/cached_file_folder) | المجلد للملفات المؤقتة التي يمكن استخدامها كذاكرة تخزين مؤقتة للبيانات.|
| [validate_merged_areas](/cells/python-net/ar/aspose.cells/txtsaveoptions/validate_merged_areas) | يشير إلى ما إذا كان يجب التحقق من صحة الخلايا المدمجة قبل حفظ الملف.|
| [merge_areas](/cells/python-net/ar/aspose.cells/txtsaveoptions/merge_areas) | يشير إلى ما إذا كان سيتم دمج مناطق التنسيق الشرطي والتحقق قبل حفظ الملف.|
| [create_directory](/cells/python-net/ar/aspose.cells/txtsaveoptions/create_directory) | إذا كانت القيمة صحيحة ولم يكن الدليل موجودًا، فسيتم إنشاء الدليل تلقائيًا قبل حفظ الملف.|
| [sort_names](/cells/python-net/ar/aspose.cells/txtsaveoptions/sort_names) |يشير إلى ما إذا كان يتم فرز الأسماء المحددة قبل حفظ الملف.|
| [sort_external_names](/cells/python-net/ar/aspose.cells/txtsaveoptions/sort_external_names) | يشير إلى ما إذا كان يتم فرز الأسماء المحددة خارجيًا قبل حفظ الملف.|
| [refresh_chart_cache](/cells/python-net/ar/aspose.cells/txtsaveoptions/refresh_chart_cache) | يشير إلى ما إذا كان يتم تحديث بيانات ذاكرة التخزين المؤقت للرسم البياني|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells/txtsaveoptions/check_excel_restriction) | ما إذا كان يتم التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات المرتبطة بالخلايا.<br/>على سبيل المثال، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/> عند إدخال قيمة أطول من 32 كيلو بايت، سيتم اقتطاعها.|
| [update_smart_art](/cells/python-net/ar/aspose.cells/txtsaveoptions/update_smart_art) | يشير إلى ما إذا كان يتم تحديث إعدادات الفن الذكي.<br/> القيمة الافتراضية هي false.|
| [encrypt_document_properties](/cells/python-net/ar/aspose.cells/txtsaveoptions/encrypt_document_properties) | يشير إلى ما إذا كان سيتم تشفير خصائص المستند عند الحفظ كملف .xls.<br/> القيمة الافتراضية هي true.|
| [separator](/cells/python-net/ar/aspose.cells/txtsaveoptions/separator) | يحصل على فاصل الأحرف لملف النص ويقوم بتعيينه.|
| [separator_string](/cells/python-net/ar/aspose.cells/txtsaveoptions/separator_string) | يحصل على قيمة سلسلة ويعينها كفاصل.|
| [encoding](/cells/python-net/ar/aspose.cells/txtsaveoptions/encoding) | يحصل على الترميز الافتراضي ويقوم بتعيينه.|
| [always_quoted](/cells/python-net/ar/aspose.cells/txtsaveoptions/always_quoted) | يشير إلى ما إذا كان سيتم دائمًا إضافة '"' لكل حقل.<br/>إذا كانت القيمة صحيحة، فسيتم اقتباس جميع القيم؛<br/>إذا كانت القيمة خاطئة، فسيتم اقتباس القيم فقط عند الحاجة إليها (على سبيل المثال،<br/>عندما تحتوي القيم على أحرف خاصة مثل '"' أو '\n' أو حرف فاصل).<br/> الإفتراضي هو خطأ.|
| [quote_type](/cells/python-net/ar/aspose.cells/txtsaveoptions/quote_type) |يحصل على أو يحدد كيفية اقتباس القيم في ملف النص المُصدَّر.|
| [format_strategy](/cells/python-net/ar/aspose.cells/txtsaveoptions/format_strategy) | يحصل على استراتيجية التنسيق ويقوم بتعيينها عند تصدير قيمة الخلية كسلسلة.|
| [trim_leading_blank_row_and_column](/cells/python-net/ar/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | يشير إلى ما إذا كان يجب تقليم الصفوف والأعمدة الفارغة الرئيسية مثلما يفعل برنامج Excel.<br/> الإفتراضي هو الصحيح.|
| [trim_tailing_blank_cells](/cells/python-net/ar/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | يشير إلى ما إذا كان يجب تقليم الخلايا الفارغة في نهاية صف واحد. القيمة الافتراضية هي خطأ.|
| [keep_separators_for_blank_row](/cells/python-net/ar/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | يشير إلى ما إذا كان يجب إخراج الفواصل للصف الفارغ.<br/> القيمة الافتراضية هي false، وبالتالي سيكون محتوى الصف الفارغ فارغًا بشكل افتراضي.|
| [export_area](/cells/python-net/ar/aspose.cells/txtsaveoptions/export_area) | نطاق الخلايا المراد تصديرها.|
| [export_quote_prefix](/cells/python-net/ar/aspose.cells/txtsaveoptions/export_quote_prefix) | يشير إلى ما إذا كان يجب تصدير علامة الاقتباس المفردة كجزء من قيمة خلية واحدة<br/> عندما يكون [`Style.quote_prefix`](/cells/python-net/ar/aspose.cells/style#quote_prefix) صحيحًا. القيمة الافتراضية هي خطأ.|
| [export_all_sheets](/cells/python-net/ar/aspose.cells/txtsaveoptions/export_all_sheets) | يشير إلى ما إذا كان سيتم تصدير كافة الأوراق إلى ملف نصي.<br/> إذا كان خطأ، قم فقط بتصدير ورقة العمل النشطة، تمامًا مثل MS Excel.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)
* فئة [`TxtSaveOptions`](/cells/python-net/ar/aspose.cells/txtsaveoptions)
