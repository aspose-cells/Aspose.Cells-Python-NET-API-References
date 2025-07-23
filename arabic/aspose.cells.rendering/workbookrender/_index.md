---
title: WorkbookRender صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 150
url: /ar/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender صف
 يمثل عرضًا لكتاب العمل.
يجب استخدام منشئ هذه الفئة بعد تعديل إعداد الصفحة ونمط الخلية.



يكشف النوع WorkbookRender عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | بناء WorkbookRender|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [page_count](/cells/python-net/ar/aspose.cells.rendering/workbookrender/page_count) | يحصل على إجمالي عدد صفحات المصنف.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | عرض المصنف بأكمله كصورة Tiff للبث.|
| [`to_image(self, filename)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_image/#str) | عرض المصنف بأكمله كصورة Tiff إلى ملف.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_image/#int-str) | تقديم صفحة معينة إلى ملف.|
| [`to_image(self, page_index, stream)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | عرض صفحة معينة على مجرى مائي.|
| [`to_printer(self, printer_name)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_printer/#str) | عرض المصنف على الطابعة|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_printer/#str-str) | عرض المصنف على الطابعة|
| [`to_printer(self, printer_settings)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | عرض المصنف على الطابعة|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | عرض المصنف على الطابعة|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | عرض المصنف على الطابعة|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | احصل على حجم الصفحة بالبوصة من الصورة الناتجة.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | يمكن للعميل التحكم في إعدادات الصفحة للطابعة عند طباعة كل صفحة باستخدام هذه الوظيفة.|
| [`dispose(self)`](/cells/python-net/ar/aspose.cells.rendering/workbookrender/dispose/#) | إصدار الموارد التي تم إنشاؤها واستخدامها للرسم.|



###  ملاحظات



###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](..)
