---
title: EbookSaveOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
##  EbookSaveOptions صف
يمثل خيارات حفظ ملف الكتاب الإلكتروني.



**الميراث:** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)



يكشف النوع EbookSaveOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/__init__/#) | إنشاء خيارات لحفظ ملف الكتاب الإلكتروني.|
| [`__init__(self, save_format)`](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/__init__/#aspose.cells.saveformat) | إنشاء خيارات لحفظ ملف الكتاب الإلكتروني.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/save_format) | يحصل على تنسيق ملف الحفظ.|
| [clear_data](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/clear_data) | اجعل المصنف فارغًا بعد حفظ الملف.|
| [cached_file_folder](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/cached_file_folder) | المجلد للملفات المؤقتة التي يمكن استخدامها كذاكرة تخزين مؤقتة للبيانات.|
| [validate_merged_areas](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) | يشير إلى ما إذا كان يجب التحقق من صحة الخلايا المدمجة قبل حفظ الملف.|
| [merge_areas](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/merge_areas) | يشير إلى ما إذا كان سيتم دمج مناطق التنسيق الشرطي والتحقق قبل حفظ الملف.|
| [create_directory](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/create_directory) | إذا كانت القيمة صحيحة ولم يكن الدليل موجودًا، فسيتم إنشاء الدليل تلقائيًا قبل حفظ الملف.|
| [sort_names](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/sort_names) |يشير إلى ما إذا كان يتم فرز الأسماء المحددة قبل حفظ الملف.|
| [sort_external_names](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/sort_external_names) | يشير إلى ما إذا كان يتم فرز الأسماء المحددة خارجيًا قبل حفظ الملف.|
| [refresh_chart_cache](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) | يشير إلى ما إذا كان يتم تحديث بيانات ذاكرة التخزين المؤقت للرسم البياني|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/check_excel_restriction) | ما إذا كان يتم التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات المرتبطة بالخلايا.<br/>على سبيل المثال، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/> عند إدخال قيمة أطول من 32 كيلو بايت، سيتم اقتطاعها.|
| [update_smart_art](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/update_smart_art) | يشير إلى ما إذا كان يتم تحديث إعدادات الفن الذكي.<br/> القيمة الافتراضية هي false.|
| [encrypt_document_properties](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/encrypt_document_properties) | يشير إلى ما إذا كان سيتم تشفير خصائص المستند عند الحفظ كملف .xls.<br/> القيمة الافتراضية هي true.|
| [ignore_invisible_shapes](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) | أشر إلى ما إذا كان يتم تصدير تلك الأشكال غير المرئية|
| [page_title](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/page_title) | عنوان صفحة HTML.<br/> للحفظ في دفق HTML فقط.|
| [attached_files_directory](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/attached_files_directory) | الدليل الذي سيتم حفظ الملفات المرفقة فيه.<br/> للحفظ في دفق HTML فقط.|
| [attached_files_url_prefix](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) | قم بتحديد بادئة عنوان URL للملفات المرفقة مثل الصورة في ملف html.<br/> للحفظ في دفق HTML فقط.|
| [default_font_name](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/default_font_name) | حدد اسم الخط الافتراضي لتصدير html، سيتم استخدام الخط الافتراضي عندما لا يكون خط النمط موجودًا،<br/>إذا كانت هذه الخاصية فارغة، فسوف يستخدم Aspose.Cells خطًا عالميًا له نفس عائلة الخط الأصلي،<br/> القيمة الافتراضية هي null.|
| [add_generic_font](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/add_generic_font) |يشير إلى ما إذا كان يجب إضافة خط عام إلى عائلة خطوط CSS.<br/> القيمة الافتراضية هي true|
| [worksheet_scalable](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) | يشير إلى ما إذا كان يتم تكبير أو تصغير HTML عبر مستوى تكبير ورقة العمل عند حفظ الملف في HTML، والقيمة الافتراضية هي False.|
| [is_export_comments](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/is_export_comments) | يشير إلى ما إذا كان يتم تصدير التعليقات عند حفظ الملف إلى html، والقيمة الافتراضية هي false.|
| [export_comments_type](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_comments_type) | يمثل نوع من تصدير التعليقات إلى ملفات HTML.|
| [disable_downlevel_revealed_comments](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) | يشير إلى ما إذا كان يتم تعطيل التعليقات الشرطية التي تم الكشف عنها في المستوى الأدنى عند تصدير الملف إلى html، والقيمة الافتراضية هي false.|
| [is_exp_image_to_temp_dir](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) | يشير إلى ما إذا كان يتم تصدير ملفات الصور إلى الدليل المؤقت.<br/> للحفظ في دفق HTML فقط.|
| [image_scalable](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/image_scalable) | يشير إلى ما إذا كان يتم استخدام وحدة قابلة للتطوير لوصف عرض الصورة<br/>عند استخدام وحدة قابلة للتطوير لوصف عرض العمود.<br/> القيمة الافتراضية هي true.|
| [width_scalable](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/width_scalable) | يشير إلى ما إذا كان يتم تصدير عرض العمود بوحدة المقياس إلى html.<br/> القيمة الافتراضية هي false.|
| [export_single_tab](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_single_tab) | يشير إلى ما إذا كان سيتم تصدير علامة تبويب واحدة عندما يحتوي الملف على ورقة عمل واحدة فقط.<br/> القيمة الافتراضية هي false.|
| [export_images_as_base64](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) | يحدد ما إذا كان سيتم حفظ الصور بتنسيق Base64 إلى HTML أو MHTML أو EPUB.|
| [export_active_worksheet_only](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) | يشير إلى ما إذا كان يتم تصدير ورقة العمل النشطة إلى ملف html فقط.<br/>إذا كانت هذه القيمة صحيحة، فسيتم تصدير ورقة العمل النشطة فقط إلى ملف html؛<br/>إذا كانت القيمة خاطئة، فسيتم تصدير المصنف بأكمله إلى ملف html.<br/> القيمة الافتراضية هي false.|
| [export_print_area_only](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_print_area_only) |يشير إلى تصدير منطقة الطباعة إلى ملف HTML فقط. القيمة الافتراضية هي خطأ.|
| [export_area](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_area) | يحصل على أو يعين منطقة الخلية المصدرة للورقة النشطة الحالية.<br/>إذا قمت بتعيين هذه الخاصية، فسيتم حذف منطقة الطباعة الخاصة بجدول العمل النشط الحالي.<br/> سيتم تصدير المنطقة المحددة فقط عند حفظ الملف بتنسيق html.|
| [parse_html_tag_in_cell](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) | يشير إلى ما إذا كان يجب تحليل علامة html (مثل `<div></div>`) في الخلية كقيمة خلية أو الحفاظ عليها كما هي.<br/> القيمة الافتراضية هي true.|
| [html_cross_string_type](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) | يشير إلى ما إذا كان سيتم عرض سلسلة عبر الخلايا بنفس الطريقة كما هو الحال في MS Excel عند حفظ ملف Excel بتنسيق html.<br/>بشكل افتراضي، القيمة هي Default، وبالتالي، بالنسبة لسلاسل الخلايا المتقاطعة، هناك فرق بسيط بين ملفات html التي تم إنشاؤها بواسطة Aspose.Cells وMS Excel.<br/> ولكن الأداء لإنشاء ملفات HTML كبيرة، وتعيين القيمة إلى Cross سيكون أسرع بعدة مرات من تعيينها إلى Default أو Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | عمود مخفي (عرض هذا العمود هو 0) في excel، قبل حفظه بتنسيق html،<br/>إذا كان HtmlHiddenColDisplayType هو "Remove"، فلن يتم إخراج العمود المخفي،<br/> إذا كانت القيمة "مخفي"، فسيتم إخراج العمود، ولكن تم إخفاؤه، والقيمة الافتراضية هي "مخفي"|
| [hidden_row_display_type](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | الصف المخفي (ارتفاع هذا الصف هو 0) في excel، قبل حفظه بتنسيق html،<br/>إذا كان HtmlHiddenRowDisplayType هو "Remove"، فلن يتم إخراج الصف المخفي،<br/>إذا كانت القيمة "مخفي"، فسيتم إخراج الصف، ولكن تم إخفاؤه، والقيمة الافتراضية هي "مخفي"|
| [encoding](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/encoding) | إذا لم يتم تعيينه، استخدم Encoding.UTF8 كنوع ترميز افتراضي.|
| [image_options](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/image_options) | احصل على كائن ImageOrPrintOptions قبل التصدير|
| [save_as_single_file](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/save_as_single_file) | يشير إلى ما إذا كان سيتم حفظ HTML كملف واحد.<br/> القيمة الافتراضية هي false.|
| [show_all_sheets](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/show_all_sheets) | يشير إلى ما إذا كان سيتم عرض جميع الأوراق عند الحفظ كملف HTML واحد.|
| [export_page_headers](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_page_headers) | يشير إلى ما إذا كان يتم تصدير رؤوس الصفحات.|
| [export_page_footers](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_page_footers) | يشير إلى ما إذا كان يتم تصدير رؤوس الصفحات.|
| [export_hidden_worksheet](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) | يشير إلى ما إذا كان سيتم تصدير محتوى ورقة العمل المخفية. القيمة الافتراضية هي true.|
| [presentation_preference](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/presentation_preference) | يشير إلى ما إذا كان ملف html أو mht هو تفضيل العرض التقديمي.<br/>القيمة الافتراضية هي false.<br/> إذا كنت تريد الحصول على عرض تقديمي أكثر جمالا، فيرجى تعيين القيمة على true.|
| [cell_css_prefix](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) | يحصل على بادئة اسم css ويقوم بتعيينها، والقيمة الافتراضية هي "".|
| [table_css_id](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/table_css_id) | يحصل على ويعين بادئة اسم نوع css مثل tr، col، td وما إلى ذلك، وهي موجودة في عنصر الجدول<br/> الذي يحتوي على سمة TableCssId المحددة. القيمة الافتراضية هي "".|
| [is_full_path_link](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/is_full_path_link) |يشير إلى ما إذا كان يتم استخدام رابط المسار الكامل في sheet00x.htm وfilelist.xml وtabstrip.htm.<br/> القيمة الافتراضية هي false.|
| [export_worksheet_css_separately](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) | يشير إلى ما إذا كان سيتم تصدير ورقة العمل css بشكل منفصل. القيمة الافتراضية هي false.|
| [export_similar_border_style](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) | يشير إلى ما إذا كان تصدير نمط الحدود المماثل عندما لا يدعم المتصفحات نمط الحدود.<br/>إذا كنت تريد استيراد ملف html أو mht إلى excel، يرجى الاحتفاظ بالقيمة الافتراضية.<br/> القيمة الافتراضية هي false.|
| [merge_empty_td_forcely](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) | يشير إلى ما إذا كان سيتم دمج عنصر TD الفارغ قسريًا عند تصدير الملف إلى html.<br/> سيتم تقليل حجم ملف HTML بشكل ملحوظ بعد ضبط القيمة على "صحيح". القيمة الافتراضية هي "خطأ".<br/> إذا كنت تريد استيراد ملف html إلى excel أو تصدير خطوط الشبكة المثالية عند حفظ الملف إلى html،<br/> يرجى الاحتفاظ بالقيمة الافتراضية.|
| [merge_empty_td_type](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) | خيار دمج الخلايا الفارغة المتجاورة (عناصر td الفارغة)<br/> القيمة الافتراضية هي MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) | يُشير إلى إمكانية تصدير إحداثيات خلايا Excel غير الفارغة عند حفظ الملف بتنسيق HTML. القيمة الافتراضية هي خطأ.<br/> إذا كنت تريد استيراد الناتج html إلى excel، يرجى الاحتفاظ بالقيمة الافتراضية.|
| [export_extra_headings](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_extra_headings) | يشير إلى ما إذا كان سيتم تصدير عناوين إضافية عندما يكون طول النص أطول من الحد الأقصى لعمود العرض.<br/> القيمة الافتراضية هي خطأ. إذا كنت ترغب في استيراد ملف HTML إلى إكسل، يُرجى الاحتفاظ بالقيمة الافتراضية.|
| [export_headings](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_headings) |يشير إلى ما إذا كان يتم تصدير عناوين الصفوف والأعمدة الخاصة بالورقة عند الحفظ في الملفات HTML.|
| [export_row_column_headings](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |يشير إلى ما إذا كان يتم تصدير عناوين الصفوف والأعمدة الخاصة بالورقة عند الحفظ في الملفات HTML.|
| [export_formula](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_formula) | يشير إلى ما إذا كان سيتم تصدير الصيغة عند حفظ الملف بتنسيق HTML. القيمة الافتراضية هي "صحيح".<br/> إذا كنت تريد استيراد الناتج html إلى excel، يرجى الاحتفاظ بالقيمة الافتراضية.|
| [add_tooltip_text](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) | يشير إلى ما إذا كان من الممكن إضافة نص إرشادي عندما لا يمكن عرض البيانات بالكامل.<br/> القيمة الافتراضية هي false.|
| [export_grid_lines](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_grid_lines) | يشير إلى ما إذا كان يتم تصدير خطوط الشبكة. القيمة الافتراضية هي false.|
| [export_bogus_row_data](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) | يُشير إلى ما إذا كان يتم تصدير بيانات الصف السفلي غير صحيحة. القيمة الافتراضية هي "صحيح". إذا كنت ترغب في استيراد ملف HTML أو MHT،<br/> للتفوق، يرجى الاحتفاظ بالقيمة الافتراضية.|
| [exclude_unused_styles](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) | يشير إلى ما إذا كان يستبعد الأنماط غير المستخدمة.<br/>بالنسبة لملفات HTML المولدة، فإن استبعاد الأنماط غير المستخدمة قد يؤدي إلى تقليل حجم الملف<br/>دون التأثير على التأثيرات المرئية. لذا، القيمة الافتراضية لهذه الخاصية هي "صحيح".<br/>إذا كان المستخدم بحاجة إلى الاحتفاظ بجميع الأنماط في المصنف الخاص بـ HTML الناتج (مثل السيناريو الذي يحتاجه المستخدم<br/> يحتاج إلى استعادة المصنف من HTML الناتج لاحقًا، يرجى تعيين هذه الخاصية على false.|
| [export_document_properties](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_document_properties) | يشير إلى ما إذا كان يتم تصدير خصائص المستند. القيمة الافتراضية هي true. إذا كنت تريد الاستيراد<br/> ملف html أو mht إلى excel، يرجى الاحتفاظ بالقيمة الافتراضية.|
| [export_worksheet_properties](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) | يشير إلى ما إذا كان يتم تصدير خصائص ورقة العمل. القيمة الافتراضية هي true. إذا كنت تريد الاستيراد<br/> ملف html أو mht إلى excel، يرجى الاحتفاظ بالقيمة الافتراضية.|
| [export_workbook_properties](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |يشير إلى ما إذا كان يتم تصدير خصائص المصنف. القيمة الافتراضية هي true. إذا كنت تريد الاستيراد<br/> ملف html أو mht إلى excel، يرجى الاحتفاظ بالقيمة الافتراضية.|
| [export_frame_scripts_and_properties](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) | يُشير إلى إمكانية تصدير نصوص الإطارات وخصائص المستندات. القيمة الافتراضية هي "صحيح". إذا كنت ترغب في استيراد ملف HTML أو MHT،<br/> للتفوق، يرجى الاحتفاظ بالقيمة الافتراضية.|
| [export_data_options](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/export_data_options) | يشير إلى قاعدة تصدير بيانات ملف html. القيمة الافتراضية هي الكل.|
| [link_target_type](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/link_target_type) | يُشير إلى نوع سمة الهدف في الرابط `<a>`. القيمة الافتراضية هي HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) | يشير إلى ما إذا كان الإخراج HTML متوافقًا مع متصفح IE.<br/> القيمة الافتراضية هي false|
| [format_data_ignore_column_width](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) | يشير إلى ما إذا كان سيتم عرض البيانات المنسقة بالكامل للخلية عند تجاوز العمود.<br/>إذا كانت هذه القيمة صحيحة، فتجاهل عرض العمود وسيتم تصدير بيانات الخلية بأكملها.<br/>إذا كانت القيمة خاطئة، فسيتم تصدير البيانات بنفس طريقة تصدير Excel.<br/> القيمة الافتراضية هي false.|
| [calculate_formula](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/calculate_formula) | يشير إلى ما إذا كان سيتم حساب الصيغ قبل حفظ ملف HTML.|
| [is_js_browser_compatible](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) | يشير إلى ما إذا كان JavaScript متوافقًا مع المتصفحات التي لا تدعم JavaScript.<br/> القيمة الافتراضية هي true.|
| [is_mobile_compatible](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) | يشير إلى ما إذا كان الإخراج HTML متوافقًا مع الأجهزة المحمولة.<br/> القيمة الافتراضية هي false.|
| [css_styles](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/css_styles) | يحصل على أنماط CSS الإضافية للمنسق أو يعينها.<br/>يعمل فقط عندما يكون [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/ar/aspose.cells/htmlsaveoptions#save_as_single_file) صحيحًا.<br/><br/> CssStyles="الجسم { الحشو: 5 بكسل }";|
| [hide_overflow_wrapped_text](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/hide_overflow_wrapped_text) |يشير إلى ما إذا كان سيتم إخفاء النص الزائد عند تعيين تنسيق الخلية على التفاف النص.<br/> القيمة الافتراضية هي false|
| [is_border_collapsed](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/is_border_collapsed) | يشير إلى ما إذا كانت حدود الجدول متقلصة.<br/> القيمة الافتراضية هي true.|
| [encode_entity_as_code](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/encode_entity_as_code) | يشير إلى ما إذا كان يتم استبدال كيانات أحرف HTML برمز عشري.<br/>(على سبيل المثال، يتم استبدال "&nbsp;" بـ "&#160; ").<br/> القيمة الافتراضية هي false.|
| [office_math_output_mode](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/office_math_output_mode) | يشير إلى كيفية تصدير كائنات OfficeMath إلى HTML، والقيمة الافتراضية هي صورة.|
| [cell_name_attribute](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/cell_name_attribute) | يقوم بتحديد السمة التي تشير إلى CellName الذي سيتم كتابته.<br/>(على سبيل المثال، إذا كانت القيمة هي "id"، فبالنسبة للخلية "A1"، سيكون الناتج:<td id='A1'>).<br/> القيمة الافتراضية هي null.|
| [disable_css](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/disable_css) | يشير إلى ما إذا كان سيتم تطبيق الأنماط المضمنة فقط، دون الاعتماد على CSS.<br/> القيمة الافتراضية هي false.|
| [enable_css_custom_properties](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/enable_css_custom_properties) | حسّن مخرجات HTML باستخدام خصائص CSS المخصصة. على سبيل المثال، في حالة وجود تكرارات متعددة لصورة base64 واحدة، باستخدام الخاصية المخصصة، يلزم حفظ بيانات الصورة مرة واحدة فقط لتحسين أداء HTML الناتج.<br/> القيمة الافتراضية هي false.|
| [html_version](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/html_version) | يحدد إصدار المعيار HTML الذي يجب استخدامه عند حفظ تنسيق HTML.<br/> القيمة الافتراضية هي HtmlVersion.Default.|
| [sheet_set](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions/sheet_set) | يُعرِّف أو يُعيِّن الأوراق المراد عرضها. الإعداد الافتراضي هو جميع الأوراق المرئية في المصنف: [`SheetSet.visible`](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).|



###  أنظر أيضا
* الوحدة [`aspose.cells.saving`](..)
* فئة [`EbookSaveOptions`](/cells/python-net/ar/aspose.cells.saving/ebooksaveoptions)
* فئة [`HtmlSaveOptions`](/cells/python-net/ar/aspose.cells/htmlsaveoptions)
* فئة [`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)
