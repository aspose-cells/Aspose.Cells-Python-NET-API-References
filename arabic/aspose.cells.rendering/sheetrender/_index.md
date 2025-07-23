---
title: SheetRender صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender صف
يمثل عرض ورقة عمل يمكنه عرض ورقة عمل لصور مختلفة مثل (BMP، PNG، JPEG، TIFF..)
يجب استخدام منشئ هذه الفئة بعد تعديل إعداد الصفحة ونمط الخلية.



يكشف النوع SheetRender عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | إنشاء SheetRender، يتطلب ورقة عمل وImageOrPrintOptions كمعلمات|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [page_count](/cells/python-net/ar/aspose.cells.rendering/sheetrender/page_count) | يحصل على إجمالي عدد الصفحات في ورقة العمل الحالية.|
| [page_scale](/cells/python-net/ar/aspose.cells.rendering/sheetrender/page_scale) | يحصل على مقياس الصفحة المحسوب للورقة.<br/> يُرجع المقياس المُعيَّن إذا كان [`PageSetup.zoom`](/cells/python-net/ar/aspose.cells/pagesetup#zoom) مُعيَّنًا. وإلا، يُرجع المقياس المحسوب وفقًا لـ [`PageSetup.fit_to_pages_wide`](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_wide) و[`PageSetup.fit_to_pages_tall`](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_tall).|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_image/#int-str) | تقديم صفحة معينة إلى ملف.|
| [`to_image(self, page_index, stream)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | عرض صفحة معينة على مجرى مائي.|
| [`to_tiff(self, stream)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | عرض ورقة العمل بأكملها كصورة Tiff للبث.|
| [`to_tiff(self, filename)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_tiff/#str) | عرض ورقة العمل بأكملها كصورة Tiff إلى ملف.|
| [`to_printer(self, printer_name)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#str) | عرض ورقة العمل على الطابعة|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#str-str) | عرض ورقة العمل على الطابعة|
| [`to_printer(self, printer_settings)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | عرض ورقة العمل على الطابعة|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | عرض ورقة العمل على الطابعة|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | عرض ورقة العمل على الطابعة|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | احصل على حجم الصفحة بالبوصة من الصورة الناتجة.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | يمكن للعميل التحكم في إعدادات الصفحة للطابعة عند طباعة كل صفحة باستخدام هذه الوظيفة.|
| [`dispose(self)`](/cells/python-net/ar/aspose.cells.rendering/sheetrender/dispose/#) | إصدار الموارد التي تم إنشاؤها واستخدامها للرسم.|



###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](..)
