---
title: SheetRender صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 120
url: /ar/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender صف
يمثل عرض ورقة العمل الذي يمكنه عرض ورقة العمل لصور مختلفة مثل (BMP، PNG، JPEG، TIFF..)
يجب استخدام مُنشئ هذه الفئة بعد تعديل إعداد الصفحات ونمط الخلية.



يكشف النوع SheetRender عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | يحتاج إنشاء SheetRender إلى ورقة عمل وImageOrPrintOptions كمعلمات|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [page_count](/cells/python-net/ar/aspose.cells.rendering/sheetrender/page_count) | الحصول على إجمالي عدد الصفحات لورقة العمل الحالية.|
| [page_scale](/cells/python-net/ar/aspose.cells.rendering/sheetrender/page_scale) | يحصل على مقياس الصفحة المحسوب للورقة.<br/> يُرجع المقياس المحدد إذا تم ضبط [`PageSetup.zoom`](/cells/python-net/ar/aspose.cells/pagesetup#zoom). وبخلاف ذلك، يتم إرجاع المقياس المحسوب وفقًا لـ [`PageSetup.fit_to_pages_wide`](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_wide) و[`PageSetup.fit_to_pages_tall`](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_tall).|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [to_image](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_image/#int-str) |تقديم صفحة معينة إلى ملف.|
| [to_image](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | تقديم صفحة معينة إلى دفق.|
| [to_tiff](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | قم بعرض ورقة العمل بأكملها كصورة Tiff للبث.|
| [to_tiff](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_tiff/#str) | تقديم ورقة العمل بأكملها كصورة Tiff إلى ملف.|
| [to_printer](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#str) | تقديم ورقة العمل إلى الطابعة|
| [to_printer](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#str-str) | تقديم ورقة العمل إلى الطابعة|
| [to_printer](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | تقديم ورقة العمل إلى الطابعة|
| [to_printer](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | تقديم ورقة العمل إلى الطابعة|
| [to_printer](/cells/python-net/ar/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | تقديم ورقة العمل إلى الطابعة|
| [get_page_size_inch](/cells/python-net/ar/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | احصل على حجم الصفحة بالبوصة من الصورة الناتجة.|
| [custom_print](/cells/python-net/ar/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | يمكن للعميل التحكم في إعداد صفحة الطابعة عند طباعة كل صفحة باستخدام هذه الوظيفة.|
| [dispose](/cells/python-net/ar/aspose.cells.rendering/sheetrender/dispose/#) | يطلق الموارد التي تم إنشاؤها واستخدامها للعرض.|



###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](..)
