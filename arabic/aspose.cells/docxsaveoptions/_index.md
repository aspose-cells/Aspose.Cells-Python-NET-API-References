---
title: DocxSaveOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 510
url: /ar/aspose.cells/docxsaveoptions/
is_root: false
---
##  DocxSaveOptions صف
يمثل خيارات حفظ ملف .docx.



**ميراث:** [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)



يكشف النوع DocxSaveOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/docxsaveoptions/__init__/#) | يمثل خيارات حفظ ملف .docx.|
| [__init__](/cells/python-net/ar/aspose.cells/docxsaveoptions/__init__/#bool) | يمثل خيارات حفظ ملف .docx.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells/docxsaveoptions/save_format) | يحصل على تنسيق ملف الحفظ.|
| [clear_data](/cells/python-net/ar/aspose.cells/docxsaveoptions/clear_data) | اجعل المصنف فارغًا بعد حفظ الملف.|
| [cached_file_folder](/cells/python-net/ar/aspose.cells/docxsaveoptions/cached_file_folder) | يتم استخدام مجلد الملفات المخزنة مؤقتًا لتخزين بعض البيانات الكبيرة.|
| [validate_merged_areas](/cells/python-net/ar/aspose.cells/docxsaveoptions/validate_merged_areas) | يشير إلى ما إذا كان سيتم التحقق من صحة الخلايا المدمجة قبل حفظ الملف.|
| [merge_areas](/cells/python-net/ar/aspose.cells/docxsaveoptions/merge_areas) | يشير إلى ما إذا كان سيتم دمج مناطق التنسيق الشرطي والتحقق من الصحة قبل حفظ الملف.|
| [create_directory](/cells/python-net/ar/aspose.cells/docxsaveoptions/create_directory) | إذا كان صحيحًا وكان الدليل غير موجود، فسيتم إنشاء الدليل تلقائيًا قبل حفظ الملف.|
| [sort_names](/cells/python-net/ar/aspose.cells/docxsaveoptions/sort_names) | يشير إلى ما إذا كان سيتم فرز الأسماء المحددة قبل حفظ الملف.|
| [sort_external_names](/cells/python-net/ar/aspose.cells/docxsaveoptions/sort_external_names) | يشير إلى ما إذا كان سيتم فرز الأسماء المحددة الخارجية قبل حفظ الملف.|
| [refresh_chart_cache](/cells/python-net/ar/aspose.cells/docxsaveoptions/refresh_chart_cache) | يشير إلى ما إذا كان سيتم تحديث بيانات ذاكرة التخزين المؤقت للمخطط أم لا|
| [warning_callback](/cells/python-net/ar/aspose.cells/docxsaveoptions/warning_callback) | الحصول على رد اتصال تحذيري أو تعيينه.|
| [update_smart_art](/cells/python-net/ar/aspose.cells/docxsaveoptions/update_smart_art) | يشير إلى ما إذا كان سيتم تحديث إعداد الفن الذكي.<br/> القيمة الافتراضية هي كاذبة.|
| [default_font](/cells/python-net/ar/aspose.cells/docxsaveoptions/default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/>قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف.<br/> إذا لم يتم تعيين هذه الخاصية، فسيستخدم Aspose.Cells الخط الافتراضي للنظام لإظهار أحرف Unicode هذه.|
| [check_workbook_default_font](/cells/python-net/ar/aspose.cells/docxsaveoptions/check_workbook_default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/> قم بتعيين هذا على "صحيح" لمحاولة استخدام الخط الافتراضي للمصنف لإظهار هذه الأحرف أولاً.|
| [check_font_compatibility](/cells/python-net/ar/aspose.cells/docxsaveoptions/check_font_compatibility) | يشير إلى ما إذا كان سيتم التحقق من توافق الخط لكل حرف في النص.|
| [is_font_substitution_char_granularity](/cells/python-net/ar/aspose.cells/docxsaveoptions/is_font_substitution_char_granularity) |يشير إلى ما إذا كان سيتم استبدال خط الحرف فقط عندما لا يكون خط الخلية متوافقًا معه.|
| [one_page_per_sheet](/cells/python-net/ar/aspose.cells/docxsaveoptions/one_page_per_sheet) | إذا كان OnePagePerSheet صحيحًا، فسيتم إخراج كل محتوى ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيكون حجم الورق الخاص بإعداد الصفحات غير صالح، كما أن الإعدادات الأخرى لإعداد الصفحات غير صالحة<br/> سوف لا تزال نافذة المفعول.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ar/aspose.cells/docxsaveoptions/all_columns_in_one_page_per_sheet) | إذا كانت قيمة AllColumnsInOnePagePerSheet صحيحة، فسيتم إخراج كل محتوى العمود في ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيتم تجاهل عرض حجم الورق لإعداد الصفحات، والإعدادات الأخرى لإعداد الصفحات<br/> سوف لا تزال نافذة المفعول.|
| [ignore_error](/cells/python-net/ar/aspose.cells/docxsaveoptions/ignore_error) | يشير إلى ما إذا كنت بحاجة إلى إخفاء الخطأ أثناء العرض.<br/> يمكن أن يكون الخطأ خطأ في الشكل أو الصورة أو عرض المخطط وما إلى ذلك.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ar/aspose.cells/docxsaveoptions/output_blank_page_when_nothing_to_print) | يشير إلى ما إذا كان سيتم إخراج صفحة فارغة عندما لا يكون هناك أي شيء لطباعته.|
| [page_index](/cells/python-net/ar/aspose.cells/docxsaveoptions/page_index) | الحصول على أو تعيين الفهرس المستند إلى 0 للصفحة الأولى المراد حفظها.|
| [page_count](/cells/python-net/ar/aspose.cells/docxsaveoptions/page_count) | الحصول على أو تعيين عدد الصفحات المراد حفظها.|
| [printing_page_type](/cells/python-net/ar/aspose.cells/docxsaveoptions/printing_page_type) | يشير إلى الصفحات التي لن تتم طباعتها.|
| [gridline_type](/cells/python-net/ar/aspose.cells/docxsaveoptions/gridline_type) | الحصول على أو تعيين نوع خط الشبكة.|
| [text_cross_type](/cells/python-net/ar/aspose.cells/docxsaveoptions/text_cross_type) | الحصول على أو تعيين عرض نوع النص عندما يكون عرض النص أكبر من عرض الخلية.|
| [default_edit_language](/cells/python-net/ar/aspose.cells/docxsaveoptions/default_edit_language) | الحصول على لغة التحرير الافتراضية أو تعيينها.|
| [sheet_set](/cells/python-net/ar/aspose.cells/docxsaveoptions/sheet_set) |الحصول على الأوراق المراد عرضها أو تعيينها. الافتراضي هو كافة الأوراق المرئية في المصنف: [`SheetSet.visible`](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/ar/aspose.cells/docxsaveoptions/draw_object_event_handler) | ينفذ هذه الواجهة للحصول على DrawObject وBound عند العرض.|
| [page_saving_callback](/cells/python-net/ar/aspose.cells/docxsaveoptions/page_saving_callback) | التحكم/الإشارة إلى تقدم عملية حفظ الصفحة.|
| [emf_render_setting](/cells/python-net/ar/aspose.cells/docxsaveoptions/emf_render_setting) | الإعداد لتقديم ملف التعريف Emf.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`DocxSaveOptions`](/cells/python-net/ar/aspose.cells/docxsaveoptions)
* فئة [`PaginatedSaveOptions`](/cells/python-net/ar/aspose.cells/paginatedsaveoptions)
* فئة [`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)
