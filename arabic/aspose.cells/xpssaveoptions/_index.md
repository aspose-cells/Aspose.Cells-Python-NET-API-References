---
title: XpsSaveOptions الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1730
url: /ar/aspose.cells/xpssaveoptions/
is_root: false
---
##  XpsSaveOptions الدرجة
يمثل الخيارات الإضافية عند حفظ الملف بتنسيق Xps.



**ميراث:** [XpsSaveOptions](/cells/python-net/aspose.cells/xpssaveoptions) → 
[PaginatedSaveOptions](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[SaveOptions](/cells/python-net/ar/aspose.cells/saveoptions)



يكشف نوع XpsSaveOptions الأعضاء التالية:

###  المنشئون
| البناء| وصف|
| :- | :- |
| [XpsSaveOptions()](/cells/python-net/ar/aspose.cells/xpssaveoptions/__init__/#) | يخلق خيارات لحفظ ملف xps.|
| [XpsSaveOptions(save_format)](/cells/python-net/ar/aspose.cells/xpssaveoptions/__init__/#SaveFormat) | يخلق خيارات لحفظ ملف xps.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells/xpssaveoptions/save_format) | يحصل على تنسيق ملف الحفظ.|
| [clear_data](/cells/python-net/ar/aspose.cells/xpssaveoptions/clear_data) | اجعل المصنف فارغًا بعد حفظ الملف.|
| [cached_file_folder](/cells/python-net/ar/aspose.cells/xpssaveoptions/cached_file_folder) | يتم استخدام مجلد الملف المخزن مؤقتًا لتخزين بعض البيانات الكبيرة.|
| [validate_merged_areas](/cells/python-net/ar/aspose.cells/xpssaveoptions/validate_merged_areas) | يشير إلى ما إذا كان يجب التحقق من صحة الخلايا المدمجة قبل حفظ الملف.|
| [merge_areas](/cells/python-net/ar/aspose.cells/xpssaveoptions/merge_areas) | يشير إلى ما إذا كان يتم دمج مناطق التنسيق الشرطي والتحقق من الصحة قبل حفظ الملف.|
| [create_directory](/cells/python-net/ar/aspose.cells/xpssaveoptions/create_directory) | إذا كان صحيحًا وكان الدليل غير موجود ، فسيتم إنشاء الدليل تلقائيًا قبل حفظ الملف.|
| [sort_names](/cells/python-net/ar/aspose.cells/xpssaveoptions/sort_names) | يشير إلى ما إذا كان يتم فرز الأسماء المعرفة قبل حفظ الملف.|
| [sort_external_names](/cells/python-net/ar/aspose.cells/xpssaveoptions/sort_external_names) |يشير إلى ما إذا كان يتم فرز الأسماء المعرفة الخارجية قبل حفظ الملف.|
| [refresh_chart_cache](/cells/python-net/ar/aspose.cells/xpssaveoptions/refresh_chart_cache) | يشير إلى ما إذا كان يتم تحديث بيانات ذاكرة التخزين المؤقت للرسم البياني أم لا|
| [warning_callback](/cells/python-net/ar/aspose.cells/xpssaveoptions/warning_callback) | يحصل أو يحدد رد الاتصال التحذيري.|
| [update_smart_art](/cells/python-net/ar/aspose.cells/xpssaveoptions/update_smart_art) | يشير إلى ما إذا كان يتم تحديث إعداد الفن الذكي.<br/> القيمة الافتراضية هي كاذبة.|
| [default_font](/cells/python-net/ar/aspose.cells/xpssaveoptions/default_font) | عندما تكون الأحرف في Excel Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية ،<br/>قد تظهر على شكل كتلة في صورة pdf.<br/>قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف.<br/> إذا لم يتم تعيين هذه الخاصية ، فسيستخدم Aspose.Cells الخط الافتراضي للنظام لإظهار أحرف unicode هذه.|
| [check_workbook_default_font](/cells/python-net/ar/aspose.cells/xpssaveoptions/check_workbook_default_font) | عندما تكون الأحرف في Excel Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية ،<br/>قد تظهر على شكل كتلة في صورة pdf.<br/> اضبط هذا على صواب لمحاولة استخدام الخط الافتراضي للمصنف لإظهار هذه الأحرف أولاً.|
| [check_font_compatibility](/cells/python-net/ar/aspose.cells/xpssaveoptions/check_font_compatibility) |يشير إلى ما إذا كان سيتم التحقق من توافق الخط لكل حرف في النص.|
| [is_font_substitution_char_granularity](/cells/python-net/ar/aspose.cells/xpssaveoptions/is_font_substitution_char_granularity) | الإشارة إلى ما إذا كان سيتم استبدال خط الحرف فقط عندما لا يكون خط الخلية متوافقًا معه.|
| [one_page_per_sheet](/cells/python-net/ar/aspose.cells/xpssaveoptions/one_page_per_sheet) | إذا كانت OnePagePerSheet صحيحة ، فسيتم إخراج كل محتوى ورقة واحدة إلى صفحة واحدة فقط نتيجة لذلك.<br/> سيكون حجم الورق الخاص بإعداد الصفحات غير صالح ، والإعدادات الأخرى لإعداد الصفحات<br/> ستظل نافذة المفعول.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ar/aspose.cells/xpssaveoptions/all_columns_in_one_page_per_sheet) | إذا كانت AllColumnsInOnePagePerSheet صحيحة ، فسيتم إخراج محتوى العمود بالكامل في ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيتم تجاهل عرض حجم الورق الخاص بإعداد الصفحات والإعدادات الأخرى لإعداد الصفحات<br/> ستظل نافذة المفعول.|
| [ignore_error](/cells/python-net/ar/aspose.cells/xpssaveoptions/ignore_error) | يشير إلى ما إذا كنت بحاجة إلى إخفاء الخطأ أثناء العرض.<br/> يمكن أن يكون الخطأ خطأ في الشكل ، الصورة ، عرض المخطط ، إلخ.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ar/aspose.cells/xpssaveoptions/output_blank_page_when_nothing_to_print) | يشير إلى ما إذا كان سيتم إخراج صفحة فارغة في حالة عدم وجود شيء للطباعة.|
| [page_index](/cells/python-net/ar/aspose.cells/xpssaveoptions/page_index) | الحصول على أو تحديد الفهرس الذي يستند إلى 0 للصفحة الأولى لحفظها.|
| [page_count](/cells/python-net/ar/aspose.cells/xpssaveoptions/page_count) | الحصول على أو تحديد عدد الصفحات المراد حفظها.|
| [printing_page_type](/cells/python-net/ar/aspose.cells/xpssaveoptions/printing_page_type) | يشير إلى الصفحات التي لن تتم طباعتها.|
| [gridline_type](/cells/python-net/ar/aspose.cells/xpssaveoptions/gridline_type) | الحصول على نوع خط الشبكة أو تعيينه.|
| [text_cross_type](/cells/python-net/ar/aspose.cells/xpssaveoptions/text_cross_type) | الحصول على عرض نوع النص أو تعيينه عندما يكون عرض النص أكبر من عرض الخلية.|
| [default_edit_language](/cells/python-net/ar/aspose.cells/xpssaveoptions/default_edit_language) | الحصول على أو تعيين لغة التحرير الافتراضية.|
| [sheet_set](/cells/python-net/ar/aspose.cells/xpssaveoptions/sheet_set) |الحصول على الأوراق أو تعيينها للعرض. الافتراضي هو كل الأوراق المرئية في المصنف: [SheetSet.visible](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/ar/aspose.cells/xpssaveoptions/draw_object_event_handler) | تنفذ هذه الواجهة للحصول على DrawObject و Bound عند العرض.|
| [page_saving_callback](/cells/python-net/ar/aspose.cells/xpssaveoptions/page_saving_callback) | التحكم / الإشارة إلى التقدم المحرز في عملية حفظ الصفحة.|



###  أنظر أيضا
* وحدة [aspose.cells](..)
* فئة [PaginatedSaveOptions](/cells/python-net/ar/aspose.cells/paginatedsaveoptions)
* فئة [SaveOptions](/cells/python-net/ar/aspose.cells/saveoptions)
* فئة [XpsSaveOptions](/cells/python-net/ar/aspose.cells/xpssaveoptions)
