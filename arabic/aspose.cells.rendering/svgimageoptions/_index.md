---
title: SvgImageOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 130
url: /ar/aspose.cells.rendering/svgimageoptions/
is_root: false
---
##  SvgImageOptions صف
خيارات لإنشاء صورة Svg.



**الميراث:** [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions) → 
[`ImageOrPrintOptions`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions)



يكشف النوع SvgImageOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/__init__/#) | ممرضة|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/save_format) | يحصل على نوع تنسيق ملف الإخراج أو يعينه<br/> دعم Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/print_with_status_dialog) | إذا كان PrintWithStatusDialog = true، فسيكون هناك مربع حوار يعرض حالة الطباعة الحالية.<br/> وإلا فلن يظهر مثل هذا الحوار.|
| [horizontal_resolution](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/horizontal_resolution) | يحصل على الدقة الأفقية للصور المولدة أو يضبطها، بنقاط لكل بوصة.|
| [vertical_resolution](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/vertical_resolution) | يحصل على الدقة الرأسية للصور المولدة أو يضبطها، بنقاط لكل بوصة.|
| [tiff_compression](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/tiff_compression) | يحصل على نوع الضغط الذي سيتم تطبيقه فقط عند حفظ الصفحات بتنسيق `Tiff` أو يعينه.|
| [tiff_color_depth](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/tiff_color_depth) | يحصل على عمق البت أو يعينه ليتم تطبيقه فقط عند حفظ الصفحات بتنسيق `Tiff`.|
| [tiff_binarization_method](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/tiff_binarization_method) | يحصل على الطريقة المستخدمة أثناء تحويل الصور إلى تنسيق 1 بت لكل بوصة أو يعينها<br/>عندما يكون [`ImageOrPrintOptions.image_type`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions#image_type) هو Tiff و [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions#tiff_compression) يساوي Ccitt3 أو Ccitt4.|
| [printing_page](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/printing_page) | يشير إلى الصفحات التي لن تتم طباعتها.|
| [quality](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/quality) | يحصل على قيمة تحدد جودة الصور المولدة أو يحددها<br/> يُطبّق فقط عند حفظ الصفحات بتنسيق `Jpeg`. القيمة الافتراضية هي 100|
| [image_type](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/image_type) | يحصل على تنسيق الصور المولدة أو يعينه.<br/> القيمة الافتراضية: PNG.|
| [is_cell_auto_fit](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/is_cell_auto_fit) | يشير إلى ما إذا كان عرض وارتفاع الخلايا يتناسبان تلقائيًا مع قيمة الخلية.<br/> القيمة الافتراضية هي false.|
| [one_page_per_sheet](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/one_page_per_sheet) | إذا كانت قيمة OnePagePerSheet صحيحة، فسيتم إخراج كل محتوى ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيكون حجم الورق في إعداد الصفحة غير صالح، والإعدادات الأخرى لإعداد الصفحة<br/> سوف تظل سارية المفعول.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/all_columns_in_one_page_per_sheet) | إذا كانت قيمة AllColumnsInOnePagePerSheet صحيحة، فسيتم إخراج كل محتوى العمود في ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيكون عرض حجم الورق لإعداد الصفحة غير صالح، والإعدادات الأخرى لإعداد الصفحة<br/> سوف تظل سارية المفعول.|
| [chart_image_type](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/chart_image_type) | قم بالإشارة إلى نوع صورة الرسم البياني عند التحويل.<br/> القيمة الافتراضية: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/embeded_image_name_in_svg) | أشر إلى اسم ملف الصورة المضمنة في svg.<br/> يجب أن يكون هذا المسار الكامل مع الدليل مثل "c:\\xpsEmbedded"|
| [svg_fit_to_view_port](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/svg_fit_to_view_port) | إذا كانت هذه الخاصية صحيحة، فسوف يتناسب ملف svg الناتج مع منفذ العرض.|
| [svg_css_prefix](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/svg_css_prefix) |يحصل على ويعين بادئة اسم css في svg، والقيمة الافتراضية هي سلسلة فارغة.|
| [only_area](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/only_area) | إذا كانت هذه الخاصية صحيحة، فسيتم إخراج منطقة واحدة، ولن يتم تطبيق أي مقياس.|
| [text_rendering_hint](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/text_rendering_hint) | يحدد جودة عرض النص.<br/> القيمة الافتراضية هي TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/smoothing_mode) | يحدد ما إذا كان سيتم تطبيق التنعيم (التنعيم المضاد للتعرج) على الخطوط والمنحنيات وحواف المناطق المملوءة.<br/> القيمة الافتراضية هي SmoothingMode.None|
| [transparent](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/transparent) | يشير إلى ما إذا كان ينبغي أن تكون خلفية الصورة المولدة شفافة.|
| [pixel_format](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/pixel_format) | يحصل على تنسيق البكسل للصور المولدة أو يعينه.|
| [is_font_substitution_char_granularity](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/is_font_substitution_char_granularity) | يشير إلى ما إذا كان سيتم استبدال خط الحرف فقط عندما لا يكون خط الخلية متوافقًا معه.|
| [page_index](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/page_index) | يحصل على أو يعين الفهرس المستند إلى 0 للصفحة الأولى التي سيتم حفظها.|
| [page_count](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/page_count) | يحصل على عدد الصفحات التي سيتم حفظها أو يحدده.|
| [is_optimized](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/is_optimized) | يشير إلى ما إذا كان سيتم تحسين عناصر الإخراج.|
| [default_font](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/default_font) | عندما تكون الأحرف في Excel عبارة عن Unicode ولا يتم ضبطها بالخط الصحيح في نمط الخلية،<br/>قد تظهر على شكل كتلة في ملف pdf أو صورة.<br/>قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف.<br/>إذا لم يتم تعيين هذه الخاصية، فسوف يستخدم Aspose.Cells الخط الافتراضي للنظام لإظهار أحرف Unicode هذه.|
| [check_workbook_default_font](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/check_workbook_default_font) | عندما تكون الأحرف في Excel عبارة عن Unicode ولا يتم ضبطها بالخط الصحيح في نمط الخلية،<br/>قد تظهر على شكل كتلة في ملف pdf أو صورة.<br/> قم بتعيين هذا على true لمحاولة استخدام الخط الافتراضي للمصنف لإظهار هذه الأحرف أولاً.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/output_blank_page_when_nothing_to_print) | يشير إلى ما إذا كان سيتم إخراج صفحة فارغة عندما لا يكون هناك شيء للطباعة.|
| [gridline_type](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/gridline_type) | يحصل على نوع خط الشبكة أو يعينه.|
| [gridline_color](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/gridline_color) | يحصل على أو يعين لون خطوط الشبكة.|
| [text_cross_type](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/text_cross_type) | يحصل على نوع النص المعروض أو يعينه عندما يكون عرض النص أكبر من عرض الخلية.|
| [emf_type](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/emf_type) | يحصل على أو يعين EmfType الذي يحدد تنسيق الملف التعريفي.<br/> القيمة الافتراضية هي EmfPlusDual.|
| [default_edit_language](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/default_edit_language) | يحصل على لغة التحرير الافتراضية أو يعينها.|
| [sheet_set](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/sheet_set) | يُعرِّف أو يُعيِّن الأوراق المراد عرضها. الإعداد الافتراضي هو جميع الأوراق المرئية في المصنف: [`SheetSet.visible`](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/emf_render_setting) | إعداد لعرض ملفات التعريف Emf في ملف المصدر.|
| [custom_render_settings](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/custom_render_settings) | يحصل على إعدادات مخصصة أو يعينها أثناء العرض.|
| [fit_to_view_port](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/fit_to_view_port) | إذا كانت هذه الخاصية صحيحة، فسوف يتناسب ملف svg الناتج مع منفذ العرض.|
| [css_prefix](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/css_prefix) |يحصل على ويعين بادئة اسم css في svg، والقيمة الافتراضية هي سلسلة فارغة.|
| [embedded_font_type](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/embedded_font_type) | يحصل على نوع الخط المضمن في Svg أو يعينه.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int) | تعيين العرض والارتفاع المطلوبين للصورة.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int-bool) | تعيين العرض والارتفاع المطلوبين للصورة.|



###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](..)
* فئة [`ImageOrPrintOptions`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions)
* فئة [`SvgImageOptions`](/cells/python-net/ar/aspose.cells.rendering/svgimageoptions)
