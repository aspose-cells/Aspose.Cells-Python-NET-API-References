---
title: PptxSaveOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1230
url: /ar/aspose.cells/pptxsaveoptions/
is_root: false
---
##  PptxSaveOptions صف
يمثل خيارات حفظ pptx.



**ميراث:** [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)



يكشف النوع PptxSaveOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/pptxsaveoptions/__init__/#) | يمثل خيارات حفظ pptx.|
| [__init__](/cells/python-net/ar/aspose.cells/pptxsaveoptions/__init__/#bool) | يمثل خيارات حفظ ملف .pptx.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells/pptxsaveoptions/save_format) | يحصل على تنسيق ملف الحفظ.|
| [clear_data](/cells/python-net/ar/aspose.cells/pptxsaveoptions/clear_data) | اجعل المصنف فارغًا بعد حفظ الملف.|
| [cached_file_folder](/cells/python-net/ar/aspose.cells/pptxsaveoptions/cached_file_folder) | يتم استخدام مجلد الملفات المخزنة مؤقتًا لتخزين بعض البيانات الكبيرة.|
| [validate_merged_areas](/cells/python-net/ar/aspose.cells/pptxsaveoptions/validate_merged_areas) | يشير إلى ما إذا كان سيتم التحقق من صحة الخلايا المدمجة قبل حفظ الملف.|
| [merge_areas](/cells/python-net/ar/aspose.cells/pptxsaveoptions/merge_areas) | يشير إلى ما إذا كان سيتم دمج مناطق التنسيق الشرطي والتحقق من الصحة قبل حفظ الملف.|
| [create_directory](/cells/python-net/ar/aspose.cells/pptxsaveoptions/create_directory) | إذا كان صحيحًا وكان الدليل غير موجود، فسيتم إنشاء الدليل تلقائيًا قبل حفظ الملف.|
| [sort_names](/cells/python-net/ar/aspose.cells/pptxsaveoptions/sort_names) | يشير إلى ما إذا كان سيتم فرز الأسماء المحددة قبل حفظ الملف.|
| [sort_external_names](/cells/python-net/ar/aspose.cells/pptxsaveoptions/sort_external_names) | يشير إلى ما إذا كان سيتم فرز الأسماء المحددة الخارجية قبل حفظ الملف.|
| [refresh_chart_cache](/cells/python-net/ar/aspose.cells/pptxsaveoptions/refresh_chart_cache) | يشير إلى ما إذا كان سيتم تحديث بيانات ذاكرة التخزين المؤقت للمخطط أم لا|
| [warning_callback](/cells/python-net/ar/aspose.cells/pptxsaveoptions/warning_callback) | الحصول على رد اتصال تحذيري أو تعيينه.|
| [update_smart_art](/cells/python-net/ar/aspose.cells/pptxsaveoptions/update_smart_art) | يشير إلى ما إذا كان سيتم تحديث إعداد الفن الذكي.<br/> القيمة الافتراضية هي كاذبة.|
| [default_font](/cells/python-net/ar/aspose.cells/pptxsaveoptions/default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/>قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف.<br/> إذا لم يتم تعيين هذه الخاصية، فسيستخدم Aspose.Cells الخط الافتراضي للنظام لإظهار أحرف Unicode هذه.|
| [check_workbook_default_font](/cells/python-net/ar/aspose.cells/pptxsaveoptions/check_workbook_default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/> قم بتعيين هذا على "صحيح" لمحاولة استخدام الخط الافتراضي للمصنف لإظهار هذه الأحرف أولاً.|
| [check_font_compatibility](/cells/python-net/ar/aspose.cells/pptxsaveoptions/check_font_compatibility) | يشير إلى ما إذا كان سيتم التحقق من توافق الخط لكل حرف في النص.|
| [is_font_substitution_char_granularity](/cells/python-net/ar/aspose.cells/pptxsaveoptions/is_font_substitution_char_granularity) |يشير إلى ما إذا كان سيتم استبدال خط الحرف فقط عندما لا يكون خط الخلية متوافقًا معه.|
| [one_page_per_sheet](/cells/python-net/ar/aspose.cells/pptxsaveoptions/one_page_per_sheet) | إذا كان OnePagePerSheet صحيحًا، فسيتم إخراج كل محتوى ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيكون حجم الورق الخاص بإعداد الصفحات غير صالح، كما أن الإعدادات الأخرى لإعداد الصفحات غير صالحة<br/> سوف لا تزال نافذة المفعول.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ar/aspose.cells/pptxsaveoptions/all_columns_in_one_page_per_sheet) | إذا كانت قيمة AllColumnsInOnePagePerSheet صحيحة، فسيتم إخراج كل محتوى العمود في ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيتم تجاهل عرض حجم الورق لإعداد الصفحات، والإعدادات الأخرى لإعداد الصفحات<br/> سوف لا تزال نافذة المفعول.|
| [ignore_error](/cells/python-net/ar/aspose.cells/pptxsaveoptions/ignore_error) | يشير إلى ما إذا كنت بحاجة إلى إخفاء الخطأ أثناء العرض.<br/> يمكن أن يكون الخطأ خطأ في الشكل أو الصورة أو عرض المخطط وما إلى ذلك.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ar/aspose.cells/pptxsaveoptions/output_blank_page_when_nothing_to_print) | يشير إلى ما إذا كان سيتم إخراج صفحة فارغة عندما لا يكون هناك أي شيء لطباعته.|
| [page_index](/cells/python-net/ar/aspose.cells/pptxsaveoptions/page_index) | الحصول على أو تعيين الفهرس المستند إلى 0 للصفحة الأولى المراد حفظها.|
| [page_count](/cells/python-net/ar/aspose.cells/pptxsaveoptions/page_count) | الحصول على أو تعيين عدد الصفحات المراد حفظها.|
| [printing_page_type](/cells/python-net/ar/aspose.cells/pptxsaveoptions/printing_page_type) | يشير إلى الصفحات التي لن تتم طباعتها.|
| [gridline_type](/cells/python-net/ar/aspose.cells/pptxsaveoptions/gridline_type) | الحصول على أو تعيين نوع خط الشبكة.|
| [text_cross_type](/cells/python-net/ar/aspose.cells/pptxsaveoptions/text_cross_type) | الحصول على أو تعيين عرض نوع النص عندما يكون عرض النص أكبر من عرض الخلية.|
| [default_edit_language](/cells/python-net/ar/aspose.cells/pptxsaveoptions/default_edit_language) | الحصول على لغة التحرير الافتراضية أو تعيينها.|
| [sheet_set](/cells/python-net/ar/aspose.cells/pptxsaveoptions/sheet_set) |الحصول على الأوراق المراد عرضها أو تعيينها. الافتراضي هو كافة الأوراق المرئية في المصنف: [`SheetSet.visible`](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/ar/aspose.cells/pptxsaveoptions/draw_object_event_handler) | ينفذ هذه الواجهة للحصول على DrawObject وBound عند العرض.|
| [page_saving_callback](/cells/python-net/ar/aspose.cells/pptxsaveoptions/page_saving_callback) | التحكم/الإشارة إلى تقدم عملية حفظ الصفحة.|
| [emf_render_setting](/cells/python-net/ar/aspose.cells/pptxsaveoptions/emf_render_setting) | الإعداد لتقديم ملف التعريف Emf.|
| [ignore_hidden_rows](/cells/python-net/ar/aspose.cells/pptxsaveoptions/ignore_hidden_rows) | يشير إلى ما إذا كان سيتم تجاهل الصفوف المخفية عند تحويل Excel إلى PowerPoint.|
| [adjust_font_size_for_row_type](/cells/python-net/ar/aspose.cells/pptxsaveoptions/adjust_font_size_for_row_type) | يمثل نوع الخط الذي يحتاج إلى تعديل حجم الخط إذا كان ارتفاع الصف صغيرًا.|
| [export_view_type](/cells/python-net/ar/aspose.cells/pptxsaveoptions/export_view_type) | الحصول على نوع العرض وتعيينه عند التصدير إلى PowerPoint.<br/> نوع التصدير الافتراضي يعمل كطباعة.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`PaginatedSaveOptions`](/cells/python-net/ar/aspose.cells/paginatedsaveoptions)
* فئة [`PptxSaveOptions`](/cells/python-net/ar/aspose.cells/pptxsaveoptions)
* فئة [`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)
