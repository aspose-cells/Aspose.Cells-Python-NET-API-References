---
title: ImageOrPrintOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions صف
يسمح بتحديد الخيارات عند عرض ورقة العمل على الصور أو طباعة ورقة العمل أو عرض المخطط على الصورة.



يكشف النوع ImageOrPrintOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/__init__/#) | إنشاء مثيل جديد لـ ImageOrPrintOptions|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/save_format) | الحصول على أو تعيين نوع تنسيق ملف الإخراج<br/> دعم تيف/XPS|
| [print_with_status_dialog](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | إذا كانت PrintWithStatusDialog = true، فسيكون هناك مربع حوار يوضح حالة الطباعة الحالية.<br/>وإلا فلن يظهر مثل هذا الحوار.|
| [horizontal_resolution](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | الحصول على أو تعيين الدقة الأفقية للصور التي تم إنشاؤها، بالنقاط في البوصة.<br/> يتم تطبيق طريقة إنشاء الصورة باستثناء الصور بتنسيق Emf.|
| [vertical_resolution](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | الحصول على أو تعيين الدقة الرأسية للصور التي تم إنشاؤها، بالنقاط في البوصة.<br/> يتم تطبيق طريقة إنشاء الصورة باستثناء الصورة بتنسيق Emf.|
| [tiff_compression](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/tiff_compression) | الحصول على أو تعيين نوع الضغط الذي سيتم تطبيقه فقط عند حفظ الصفحات بتنسيق `Tiff`.|
| [tiff_color_depth](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | الحصول على عمق البت أو تعيينه ليتم تطبيقه فقط عند حفظ الصفحات بتنسيق `Tiff`.|
| [tiff_binarization_method](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | يحصل أو يحدد الطريقة المستخدمة أثناء تحويل الصور إلى تنسيق 1 bpp<br/> عندما يكون [`ImageOrPrintOptions.image_type`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions#image_type) هو Tiff و[`ImageOrPrintOptions.tiff_compression`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions#tiff_compression) يساوي Ccitt3 أو Ccitt4.|
| [printing_page](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/printing_page) | يشير إلى الصفحات التي لن تتم طباعتها.|
| [quality](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/quality) | الحصول على أو تعيين قيمة تحدد جودة الصور التي تم إنشاؤها<br/> يتم تطبيقه فقط عند حفظ الصفحات بتنسيق `Jpeg`. القيمة الافتراضية هي 100|
| [image_type](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/image_type) | الحصول على أو تعيين تنسيق الصور التي تم إنشاؤها.<br/> القيمة الافتراضية: PNG.|
| [is_cell_auto_fit](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | يشير إلى ما إذا كان عرض الخلايا وارتفاعها يتم ملاءمتهما تلقائيًا بقيمة الخلية.<br/> القيمة الافتراضية هي كاذبة.|
| [one_page_per_sheet](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | إذا كان OnePagePerSheet صحيحًا، فسيتم إخراج كل محتوى ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/> سيكون حجم الورق الخاص بإعداد الصفحات غير صالح، كما أن الإعدادات الأخرى لإعداد الصفحات غير صالحة<br/> سوف لا تزال نافذة المفعول.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | إذا كانت قيمة AllColumnsInOnePagePerSheet صحيحة، فسيتم إخراج كل محتوى العمود في ورقة واحدة إلى صفحة واحدة فقط في النتيجة.<br/>سيكون عرض حجم الورق لإعداد الصفحات غير صالح، والإعدادات الأخرى لإعداد الصفحات<br/> سوف لا تزال نافذة المفعول.|
| [draw_object_event_handler](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/draw_object_event_handler) | ينفذ هذه الواجهة للحصول على DrawObject وBound عند العرض.|
| [chart_image_type](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/chart_image_type) | أشر إلى نوع صورة المخطط عند التحويل.<br/> القيمة الافتراضية: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | أشر إلى اسم ملف الصورة المضمنة في svg.<br/> يجب أن يكون هذا المسار كاملاً بدليل مثل "c:\\xpsEmbedded"|
| [svg_fit_to_view_port](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | إذا كانت هذه الخاصية صحيحة، فسيكون ملف svg الذي تم إنشاؤه مناسبًا لعرض المنفذ.|
| [only_area](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/only_area) | إذا كانت هذه الخاصية صحيحة، فسيتم إخراج منطقة واحدة، ولن يتم تفعيل أي مقياس.|
| [text_rendering_hint](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | يحدد جودة عرض النص.<br/> القيمة الافتراضية هي TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | يحدد ما إذا كان سيتم تطبيق التجانس (منع الحواف) على الخطوط والمنحنيات وحواف المساحات المعبأة.<br/> القيمة الافتراضية هي SmoothingMode.None|
| [transparent](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/transparent) | يشير إلى ما إذا كانت خلفية الصورة التي تم إنشاؤها يجب أن تكون شفافة.|
| [pixel_format](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/pixel_format) | الحصول على أو تعيين تنسيق البكسل للصور التي تم إنشاؤها.|
| [warning_callback](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/warning_callback) | الحصول على رد اتصال تحذيري أو تعيينه.|
| [page_saving_callback](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/page_saving_callback) | التحكم/الإشارة إلى تقدم عملية حفظ الصفحة.|
| [is_font_substitution_char_granularity](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) |يشير إلى ما إذا كان سيتم استبدال خط الحرف فقط عندما لا يكون خط الخلية متوافقًا معه.|
| [page_index](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/page_index) | الحصول على أو تعيين الفهرس المستند إلى 0 للصفحة الأولى المراد حفظها.|
| [page_count](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/page_count) | الحصول على أو تعيين عدد الصفحات المراد حفظها.|
| [is_optimized](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/is_optimized) | يشير إلى ما إذا كان سيتم تحسين عناصر الإخراج.|
| [default_font](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/>قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف.<br/> إذا لم يتم تعيين هذه الخاصية، فسيستخدم Aspose.Cells الخط الافتراضي للنظام لإظهار أحرف Unicode هذه.|
| [check_workbook_default_font](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | عندما تكون الأحرف في Excel هي Unicode ولا يتم تعيينها بالخط الصحيح في نمط الخلية،<br/>قد تظهر ككتلة في ملف pdf، صورة.<br/> قم بتعيين هذا على "صحيح" لمحاولة استخدام الخط الافتراضي للمصنف لإظهار هذه الأحرف أولاً.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | يشير إلى ما إذا كان سيتم إخراج صفحة فارغة عندما لا يكون هناك أي شيء لطباعته.|
| [gridline_type](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/gridline_type) | الحصول على أو تعيين نوع خط الشبكة.|
| [text_cross_type](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/text_cross_type) | الحصول على أو تعيين عرض نوع النص عندما يكون عرض النص أكبر من عرض الخلية.|
| [emf_type](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/emf_type) | الحصول على EmfType أو تعيينه الذي يحدد تنسيق ملف التعريف.<br/>القيمة الافتراضية هي EmfPlusDual.|
| [default_edit_language](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/default_edit_language) | الحصول على لغة التحرير الافتراضية أو تعيينها.|
| [sheet_set](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/sheet_set) |الحصول على الأوراق المراد عرضها أو تعيينها. الافتراضي هو كافة الأوراق المرئية في المصنف: [`SheetSet.visible`](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | الإعداد لتقديم ملف التعريف Emf.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_desired_size](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | يضبط العرض والارتفاع المطلوب للصورة.|
| [set_desired_size](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | يضبط العرض والارتفاع المطلوب للصورة.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](..)
