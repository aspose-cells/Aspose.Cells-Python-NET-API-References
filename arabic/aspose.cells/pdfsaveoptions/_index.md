---
title: PdfSaveOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1220
url: /ar/aspose.cells/pdfsaveoptions/
is_root: false
---
##  PdfSaveOptions صف
يمثل خيارات حفظ ملف pdf.



**ميراث:** [`PdfSaveOptions`](/cells/python-net/aspose.cells/pdfsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)



يكشف النوع PdfSaveOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/pdfsaveoptions/__init__/#) | يخلق الخيارات لحفظ ملف pdf.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells/pdfsaveoptions/save_format) | يحصل على تنسيق ملف الحفظ.|
| [clear_data](/cells/python-net/ar/aspose.cells/pdfsaveoptions/clear_data) | اجعل المصنف فارغًا بعد حفظ الملف.|
| [cached_file_folder](/cells/python-net/ar/aspose.cells/pdfsaveoptions/cached_file_folder) | يتم استخدام مجلد الملفات المخزنة مؤقتًا لتخزين بعض البيانات الكبيرة.|
| [validate_merged_areas](/cells/python-net/ar/aspose.cells/pdfsaveoptions/validate_merged_areas) | يشير إلى ما إذا كان سيتم التحقق من صحة الخلايا المدمجة قبل حفظ الملف.|
| [merge_areas](/cells/python-net/ar/aspose.cells/pdfsaveoptions/merge_areas) | يشير إلى ما إذا كان سيتم دمج مناطق التنسيق الشرطي والتحقق من الصحة قبل حفظ الملف.|
| [create_directory](/cells/python-net/ar/aspose.cells/pdfsaveoptions/create_directory) | إذا كان صحيحًا وكان الدليل غير موجود، فسيتم إنشاء الدليل تلقائيًا قبل حفظ الملف.|
| [sort_names](/cells/python-net/ar/aspose.cells/pdfsaveoptions/sort_names) | يشير إلى ما إذا كان سيتم فرز الأسماء المحددة قبل حفظ الملف.|
| [sort_external_names](/cells/python-net/ar/aspose.cells/pdfsaveoptions/sort_external_names) | يشير إلى ما إذا كان سيتم فرز الأسماء المحددة الخارجية قبل حفظ الملف.|
| [refresh_chart_cache](/cells/python-net/ar/aspose.cells/pdfsaveoptions/refresh_chart_cache) | يشير إلى ما إذا كان سيتم تحديث بيانات ذاكرة التخزين المؤقت للمخطط أم لا|
| [warning_callback](/cells/python-net/ar/aspose.cells/pdfsaveoptions/warning_callback) | الحصول على رد اتصال تحذيري أو تعيينه.|
| [update_smart_art](/cells/python-net/ar/aspose.cells/pdfsaveoptions/update_smart_art) | يشير إلى ما إذا كان سيتم تحديث إعداد الفن الذكي.<br/> القيمة الافتراضية هي كاذبة.|
| [default_font](/cells/python-net/ar/aspose.cells/pdfsaveoptions/default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/>قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف.<br/> إذا لم يتم تعيين هذه الخاصية، فسيستخدم Aspose.Cells الخط الافتراضي للنظام لإظهار أحرف Unicode هذه.|
| [check_workbook_default_font](/cells/python-net/ar/aspose.cells/pdfsaveoptions/check_workbook_default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/> قم بتعيين هذا على "صحيح" لمحاولة استخدام الخط الافتراضي للمصنف لإظهار هذه الأحرف أولاً.|
| [check_font_compatibility](/cells/python-net/ar/aspose.cells/pdfsaveoptions/check_font_compatibility) | يشير إلى ما إذا كان سيتم التحقق من توافق الخط لكل حرف في النص.|
| [is_font_substitution_char_granularity](/cells/python-net/ar/aspose.cells/pdfsaveoptions/is_font_substitution_char_granularity) |يشير إلى ما إذا كان سيتم استبدال خط الحرف فقط عندما لا يكون خط الخلية متوافقًا معه.|
| [one_page_per_sheet](/cells/python-net/ar/aspose.cells/pdfsaveoptions/one_page_per_sheet) | إذا كان OnePagePerSheet صحيحًا، فسيتم إخراج كل محتوى ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيكون حجم الورق الخاص بإعداد الصفحات غير صالح، كما أن الإعدادات الأخرى لإعداد الصفحات غير صالحة<br/> سوف لا تزال نافذة المفعول.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ar/aspose.cells/pdfsaveoptions/all_columns_in_one_page_per_sheet) | إذا كانت قيمة AllColumnsInOnePagePerSheet صحيحة، فسيتم إخراج كل محتوى العمود في ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيتم تجاهل عرض حجم الورق لإعداد الصفحات، والإعدادات الأخرى لإعداد الصفحات<br/> سوف لا تزال نافذة المفعول.|
| [ignore_error](/cells/python-net/ar/aspose.cells/pdfsaveoptions/ignore_error) | يشير إلى ما إذا كنت بحاجة إلى إخفاء الخطأ أثناء العرض.<br/> يمكن أن يكون الخطأ خطأ في الشكل أو الصورة أو عرض المخطط وما إلى ذلك.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ar/aspose.cells/pdfsaveoptions/output_blank_page_when_nothing_to_print) | يشير إلى ما إذا كان سيتم إخراج صفحة فارغة عندما لا يكون هناك أي شيء لطباعته.|
| [page_index](/cells/python-net/ar/aspose.cells/pdfsaveoptions/page_index) | الحصول على أو تعيين الفهرس المستند إلى 0 للصفحة الأولى المراد حفظها.|
| [page_count](/cells/python-net/ar/aspose.cells/pdfsaveoptions/page_count) | الحصول على أو تعيين عدد الصفحات المراد حفظها.|
| [printing_page_type](/cells/python-net/ar/aspose.cells/pdfsaveoptions/printing_page_type) | يشير إلى الصفحات التي لن تتم طباعتها.|
| [gridline_type](/cells/python-net/ar/aspose.cells/pdfsaveoptions/gridline_type) | الحصول على أو تعيين نوع خط الشبكة.|
| [text_cross_type](/cells/python-net/ar/aspose.cells/pdfsaveoptions/text_cross_type) | الحصول على أو تعيين عرض نوع النص عندما يكون عرض النص أكبر من عرض الخلية.|
| [default_edit_language](/cells/python-net/ar/aspose.cells/pdfsaveoptions/default_edit_language) | الحصول على لغة التحرير الافتراضية أو تعيينها.|
| [sheet_set](/cells/python-net/ar/aspose.cells/pdfsaveoptions/sheet_set) |الحصول على الأوراق المراد عرضها أو تعيينها. الافتراضي هو كافة الأوراق المرئية في المصنف: [`SheetSet.visible`](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/ar/aspose.cells/pdfsaveoptions/draw_object_event_handler) | ينفذ هذه الواجهة للحصول على DrawObject وBound عند العرض.|
| [page_saving_callback](/cells/python-net/ar/aspose.cells/pdfsaveoptions/page_saving_callback) | التحكم/الإشارة إلى تقدم عملية حفظ الصفحة.|
| [emf_render_setting](/cells/python-net/ar/aspose.cells/pdfsaveoptions/emf_render_setting) | الإعداد لتقديم ملف التعريف Emf.|
| [embed_standard_windows_fonts](/cells/python-net/ar/aspose.cells/pdfsaveoptions/embed_standard_windows_fonts) | صحيح لتضمين الخطوط النوع الحقيقي.<br/>يؤثر فقط على أحرف ASCII 32-127.<br/>يتم دائمًا تضمين خطوط رموز الأحرف الأكبر من 127.<br/>يتم دائمًا تضمين الخطوط لمعيار PDF/A-1a وPDF/A-1b.<br/> الافتراضي صحيح.|
| [bookmark](/cells/python-net/ar/aspose.cells/pdfsaveoptions/bookmark) | الحصول على الكائن [`PdfBookmarkEntry`](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry) وتعيينه.|
| [compliance](/cells/python-net/ar/aspose.cells/pdfsaveoptions/compliance) | الحصول على أو تعيين مستوى الامتثال للمعايير PDF لمستندات المخرجات.|
| [security_options](/cells/python-net/ar/aspose.cells/pdfsaveoptions/security_options) | اضبط هذه الخيارات عندما تكون هناك حاجة إلى الأمان في نتيجة xls2pdf.|
| [image_type](/cells/python-net/ar/aspose.cells/pdfsaveoptions/image_type) |يمثل نوع الصورة عند تحويل المخطط والشكل.|
| [calculate_formula](/cells/python-net/ar/aspose.cells/pdfsaveoptions/calculate_formula) | يشير إلى ما إذا كان سيتم حساب الصيغ قبل حفظ ملف pdf.|
| [pdf_compression](/cells/python-net/ar/aspose.cells/pdfsaveoptions/pdf_compression) | أشر إلى خوارزمية الضغط|
| [created_time](/cells/python-net/ar/aspose.cells/pdfsaveoptions/created_time) | الحصول على وقت إنشاء مستند pdf وتعيينه.|
| [producer](/cells/python-net/ar/aspose.cells/pdfsaveoptions/producer) | الحصول على منتج مستند pdf الذي تم إنشاؤه وتعيينه.|
| [optimization_type](/cells/python-net/ar/aspose.cells/pdfsaveoptions/optimization_type) | الحصول على نوع تحسين pdf وتعيينه.|
| [custom_properties_export](/cells/python-net/ar/aspose.cells/pdfsaveoptions/custom_properties_export) | الحصول على قيمة أو تعيينها لتحديد طريقة تصدير [`CustomDocumentPropertyCollection`](/cells/python-net/ar/aspose.cells.properties/customdocumentpropertycollection) إلى ملف PDF. القيمة الافتراضية هي لا شيء.|
| [export_document_structure](/cells/python-net/ar/aspose.cells/pdfsaveoptions/export_document_structure) | يشير إلى ما إذا كان سيتم تصدير بنية المستند.|
| [display_doc_title](/cells/python-net/ar/aspose.cells/pdfsaveoptions/display_doc_title) | يشير إلى ما إذا كان شريط عنوان النافذة يجب أن يعرض عنوان المستند.|
| [font_encoding](/cells/python-net/ar/aspose.cells/pdfsaveoptions/font_encoding) | الحصول على أو تعيين ترميز الخط المضمن في ملف pdf.|
| [watermark](/cells/python-net/ar/aspose.cells/pdfsaveoptions/watermark) | الحصول على العلامة المائية أو تعيينها للإخراج.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_image_resample](/cells/python-net/ar/aspose.cells/pdfsaveoptions/set_image_resample/#int-int) | يضبط PPI المطلوب (بكسل في البوصة) لإعادة تشكيل الصور وجودة jpeg.<br/> سيتم تحويل جميع الصور إلى JPEG بإعدادات الجودة المحددة،<br/> وسيتم إعادة تشكيل الصور التي تكون أكبر من PPI المحدد (بكسل لكل بوصة).|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`CustomDocumentPropertyCollection`](/cells/python-net/ar/aspose.cells.properties/customdocumentpropertycollection)
* فئة [`PaginatedSaveOptions`](/cells/python-net/ar/aspose.cells/paginatedsaveoptions)
* فئة [`PdfBookmarkEntry`](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry)
* فئة [`PdfSaveOptions`](/cells/python-net/ar/aspose.cells/pdfsaveoptions)
* فئة [`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)
