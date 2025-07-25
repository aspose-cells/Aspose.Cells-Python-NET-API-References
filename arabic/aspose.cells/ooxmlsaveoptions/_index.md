---
title: OoxmlSaveOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1050
url: /ar/aspose.cells/ooxmlsaveoptions/
is_root: false
---
##  OoxmlSaveOptions صف
يمثل خيارات حفظ ملف Office Open XML.



**الميراث:** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)



يكشف النوع OoxmlSaveOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/__init__/#) | إنشاء خيارات لحفظ ملف Office Open XML.|
| [`__init__(self, save_format)`](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) | إنشاء خيارات لحفظ ملف Office Open XML.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [save_format](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/save_format) | يحصل على تنسيق ملف الحفظ.|
| [clear_data](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/clear_data) | اجعل المصنف فارغًا بعد حفظ الملف.|
| [cached_file_folder](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/cached_file_folder) | المجلد للملفات المؤقتة التي يمكن استخدامها كذاكرة تخزين مؤقتة للبيانات.|
| [validate_merged_areas](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/validate_merged_areas) | يشير إلى ما إذا كان يجب التحقق من صحة الخلايا المدمجة قبل حفظ الملف.|
| [merge_areas](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/merge_areas) | يشير إلى ما إذا كان سيتم دمج مناطق التنسيق الشرطي والتحقق قبل حفظ الملف.|
| [create_directory](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/create_directory) | إذا كانت القيمة صحيحة ولم يكن الدليل موجودًا، فسيتم إنشاء الدليل تلقائيًا قبل حفظ الملف.|
| [sort_names](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/sort_names) |يشير إلى ما إذا كان يتم فرز الأسماء المحددة قبل حفظ الملف.|
| [sort_external_names](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/sort_external_names) | يشير إلى ما إذا كان يتم فرز الأسماء المحددة خارجيًا قبل حفظ الملف.|
| [refresh_chart_cache](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) | يشير إلى ما إذا كان يتم تحديث بيانات ذاكرة التخزين المؤقت للرسم البياني|
| [check_excel_restriction](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/check_excel_restriction) | ما إذا كان يتم التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات المرتبطة بالخلايا.<br/>على سبيل المثال، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.<br/> عند إدخال قيمة أطول من 32 كيلو بايت، سيتم اقتطاعها.|
| [update_smart_art](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/update_smart_art) | يشير إلى ما إذا كان يتم تحديث إعدادات الفن الذكي.<br/> القيمة الافتراضية هي false.|
| [encrypt_document_properties](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) | يشير إلى ما إذا كان سيتم تشفير خصائص المستند عند الحفظ كملف .xls.<br/> القيمة الافتراضية هي true.|
| [export_cell_name](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/export_cell_name) | يشير إلى ما إذا كان يتم تصدير اسم الخلية إلى ملف Excel2007 .xlsx (.xlsm، .xltx، .xltm).<br/>إذا كان من الممكن الوصول إلى ملف الإخراج بواسطة SQL Server DTS، فيجب أن تكون هذه القيمة صحيحة.<br/>سيؤدي تعيين القيمة إلى false إلى زيادة الأداء بشكل كبير وتقليل حجم الملف عند إنشاء ملف كبير.<br/> القيمة الافتراضية هي true.|
| [update_zoom](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/update_zoom) | يشير إلى ما إذا كان سيتم تحديث عامل القياس قبل حفظ الملف<br/> إذا كانت خصائص PageSetup.FitToPagesWide وPageSetup.FitToPagesTall تتحكم في كيفية قياس ورقة العمل.|
| [enable_zip64](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/enable_zip64) | استخدم دائمًا ملحقات ZIP64 عند كتابة أرشيفات zip، حتى عندما لا يكون ذلك ضروريًا.|
| [embed_ooxml_as_ole_object](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) | يشير إلى ما إذا كان يتم تضمين ملفات Ooxml الخاصة بـ OleObject ككائن ole.|
| [compression_type](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/compression_type) | يحصل على نوع الضغط لملف ooxml ويقوم بتعيينه.|
| [wps_compatibility](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions/wps_compatibility) | يشير إلى ما إذا كان يجب جعل XLS أكثر توافقًا مع WPS.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`OoxmlSaveOptions`](/cells/python-net/ar/aspose.cells/ooxmlsaveoptions)
* فئة [`SaveOptions`](/cells/python-net/ar/aspose.cells/saveoptions)
