---
title: Config صف
second_title: Aspose.Cells.GridJs for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cellsgridjs/config/
is_root: false
---
##  Config صف

يمثل جميع إعدادات GridJs



يكشف النوع Config عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cellsgridjs/config/__init__/#) | إنشاء مثيل جديد للتكوين|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_html_as_zip](/cells/python-net/ar/aspose.cellsgridjs/config/save_html_as_zip) | يعين/يحصل على ما إذا كان سيتم حفظ ملف html كأرشيف مضغوط، الإعداد الافتراضي هو خطأ.|
| [same_image_detecting](/cells/python-net/ar/aspose.cellsgridjs/config/same_image_detecting) | يضبط/يحصل على ما إذا كان سيتم التحقق مما إذا كانت الصورة لها نفس المصدر أم لا، ويكون الإعداد الافتراضي صحيحًا<br/> القيمة الافتراضية هي الحقيقية.|
| [auto_optimize_for_large_cells](/cells/python-net/ar/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | يحدد/يحصل على ما إذا كان سيتم تحسين أداء التحميل لورقة العمل ذات الخلايا الكبيرة تلقائيًا<br/> تجاهل بعض الأنماط/الحدود لتقليل وقت التحميل<br/> القيمة الافتراضية هي الحقيقية.|
| [islimit_shape_or_image](/cells/python-net/ar/aspose.cellsgridjs/config/islimit_shape_or_image) |يحدد/يحصل على ما إذا كان سيتم تحديد إجمالي شكل العرض/عدد الصور داخل ورقة عمل واحدة، إذا تم التعيين على "صحيح"،<br/> ستحدد GridJs إجمالي شكل العرض/حجم الصورة داخل ورقة عمل واحدة إلى MaxShapeOrImageCount<br/> القيمة الافتراضية هي الحقيقية.|
| [max_shape_or_image_count](/cells/python-net/ar/aspose.cellsgridjs/config/max_shape_or_image_count) | يضبط/يحصل على إجمالي شكل العرض/عدد الصور داخل الورقة النشطة، وسوف يستغرق الأمر تأثيرًا عندما تكون IslimitShapes = true.<br/> القيمة الافتراضية هي 100.|
| [max_total_shape_or_image_count](/cells/python-net/ar/aspose.cellsgridjs/config/max_total_shape_or_image_count) | يقوم بتعيين/الحصول على إجمالي شكل العرض/عدد الصور داخل المصنف بأكمله، وسوف يستغرق الأمر تأثيرًا عندما يكون IslimitShapes = true.<br/> القيمة الافتراضية هي 300.|
| [max_shape_or_image_width_or_height](/cells/python-net/ar/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | يحدد/يحصل على الحد الأقصى للعرض أو الارتفاع للشكل/الصورة، سوف يتجاهل GridJs الشكل/الصورة ذات العرض أو الارتفاع الأكبر من هذا، وسوف يستغرق الأمر تأثيرًا عندما يكون IslimitShapes = true.<br/> القيمة الافتراضية هي 10000.|
| [max_pdf_save_seconds](/cells/python-net/ar/aspose.cellsgridjs/config/max_pdf_save_seconds) | يضبط/يحصل على الحد الأقصى للثواني المنقضية عند الحفظ بصيغة pdf.<br/> القيمة الافتراضية هي 10.|
| [ignore_empty_content](/cells/python-net/ar/aspose.cellsgridjs/config/ignore_empty_content) | يحدد/يحصل على ما إذا كان سيتم إظهار النطاق الأقصى الذي يتضمن البيانات والنمط والخلايا والأشكال المدمجة.<br/> إذا كان الصف أو العمود الأخير يحتوي على خلايا ليس لها قيمة وصيغة ولكن لها نمط مخصص<br/>فلن نعرض هذا الصف/العمود عندما تكون هذه القيمة صحيحة.<br/> القيمة الافتراضية هي الحقيقية .|
| [use_print_area](/cells/python-net/ar/aspose.cellsgridjs/config/use_print_area) |يضبط/يحصل على ما إذا كان سيتم استخدام PageSetup.PrintArea لنطاق عرض واجهة المستخدم عندما تحتوي ورقة العمل على إعداد PageSetup لمنطقة الطباعة.<br/> القيمة الافتراضية هي كاذبة .|
| [load_time_out](/cells/python-net/ar/aspose.cellsgridjs/config/load_time_out) | يضبط/يحصل على مقاطعة المهلة بالمللي ثانية في تحميل الملف، عندما تكون فترة تكلفة تحميل الملف أطول من المتوقع، فسوف يؤدي ذلك إلى ظهور استثناء.<br/> القيمة الافتراضية هي -1، مما يعني عدم تعيين مقاطعة المهلة.|
| [show_chart_sheet](/cells/python-net/ar/aspose.cellsgridjs/config/show_chart_sheet) | يحدد/يحصل على ما إذا كان سيتم عرض ورقة عمل المخطط أم لا.<br/> القيمة الافتراضية هي كاذبة .|
| [page_size](/cells/python-net/ar/aspose.cellsgridjs/config/page_size) | يحدد/يحصل على ما إذا كان سيتم ترقيم الصفحات<br/> ستحدد GridJs حجم الصف استنادًا إلى PageSize، إذا كان PageSize هو -1، فلن يتم ترقيم الصفحات<br/> القيمة الافتراضية هي -1|
| [empty_sheet_max_row](/cells/python-net/ar/aspose.cellsgridjs/config/empty_sheet_max_row) | يعين/يحصل على الصف الأقصى الافتراضي لورقة عمل فارغة.<br/> القيمة الافتراضية هي 12.|
| [empty_sheet_max_col](/cells/python-net/ar/aspose.cellsgridjs/config/empty_sheet_max_col) | يعين/يحصل على عمود الحد الأقصى الافتراضي لورقة عمل فارغة.<br/> القيمة الافتراضية هي 15.|
| [picture_cache_directory](/cells/python-net/ar/aspose.cellsgridjs/config/picture_cache_directory) | يعين/يحصل على دليل ذاكرة التخزين المؤقت للصور. (سيسري هذا عندما يكون GridJsWorkbook.CacheImp فارغًا)<br/> سيكون المسار الافتراضي هو "_piccache" داخل FileCacheDirectory.|
| [file_cache_directory](/cells/python-net/ar/aspose.cellsgridjs/config/file_cache_directory) |يحدد/يحصل على دليل ذاكرة التخزين المؤقت لملف جدول البيانات.<br/> نحتاج إلى ضبطه على مسار محدد قبل أن نستخدم GridJs.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_license](/cells/python-net/ar/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/ar/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | ترخيص المكون.|
| [set_font_folder](/cells/python-net/ar/aspose.cellsgridjs/config/set_font_folder/#str-bool) | يضبط مجلد الخطوط|
| [set_font_folders](/cells/python-net/ar/aspose.cellsgridjs/config/set_font_folders/#list-bool) | يضبط مجلدات الخطوط|



###  أنظر أيضا
* الوحدة [`aspose.cellsgridjs`](..)
