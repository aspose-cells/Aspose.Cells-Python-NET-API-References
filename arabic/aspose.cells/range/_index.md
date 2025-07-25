---
title: Range صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1180
url: /ar/aspose.cells/range/
is_root: false
---
##  Range صف
يقوم بتغليف الكائن الذي يمثل نطاقًا من الخلايا داخل جدول بيانات.



يكشف النوع Range عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [current_region](/cells/python-net/ar/aspose.cells/range/current_region) | يقوم بإرجاع كائن النطاق الذي يمثل المنطقة الحالية.<br/> المنطقة الحالية عبارة عن نطاق محدد بأي مجموعة من الصفوف الفارغة والأعمدة الفارغة.|
| [hyperlinks](/cells/python-net/ar/aspose.cells/range/hyperlinks) | يحصل على كافة الارتباطات التشعبية في النطاق.|
| [row_count](/cells/python-net/ar/aspose.cells/range/row_count) | يحصل على عدد الصفوف في النطاق.|
| [column_count](/cells/python-net/ar/aspose.cells/range/column_count) | يحصل على عدد الأعمدة في النطاق.|
| [name](/cells/python-net/ar/aspose.cells/range/name) | يحصل على اسم النطاق أو يعينه.|
| [refers_to](/cells/python-net/ar/aspose.cells/range/refers_to) | يحصل على النطاق الذي يشير إليه.|
| [address](/cells/python-net/ar/aspose.cells/range/address) | يحصل على عنوان النطاق.|
| [left](/cells/python-net/ar/aspose.cells/range/left) | يحصل على المسافة، بالنقاط، من الحافة اليسرى للعمود A إلى الحافة اليسرى للنطاق.|
| [top](/cells/python-net/ar/aspose.cells/range/top) | يحصل على المسافة، بالنقاط، من الحافة العلوية للصف 1 إلى الحافة العلوية للنطاق.|
| [width](/cells/python-net/ar/aspose.cells/range/width) | يحصل على عرض النطاق بالنقاط.|
| [height](/cells/python-net/ar/aspose.cells/range/height) | يحصل على عرض النطاق بالنقاط.|
| [first_row](/cells/python-net/ar/aspose.cells/range/first_row) | يحصل على مؤشر الصف الأول من النطاق.|
| [first_column](/cells/python-net/ar/aspose.cells/range/first_column) | يحصل على فهرس العمود الأول من النطاق.|
| [value](/cells/python-net/ar/aspose.cells/range/value) | يحصل على قيمة النطاق ويحددها.|
| [column_width](/cells/python-net/ar/aspose.cells/range/column_width) | تعيين أو الحصول على عرض العمود لهذا النطاق|
| [row_height](/cells/python-net/ar/aspose.cells/range/row_height) | تعيين أو الحصول على ارتفاع الصفوف في هذا النطاق|
| [entire_column](/cells/python-net/ar/aspose.cells/range/entire_column) |يحصل على كائن نطاق يمثل العمود بأكمله (أو الأعمدة) الذي يحتوي على النطاق المحدد.|
| [entire_row](/cells/python-net/ar/aspose.cells/range/entire_row) | يحصل على كائن نطاق يمثل الصف بأكمله (أو الصفوف) الذي يحتوي على النطاق المحدد.|
| [worksheet](/cells/python-net/ar/aspose.cells/range/worksheet) | يحصل على الكائن [`Range.worksheet`](/cells/python-net/ar/aspose.cells/range#worksheet) الذي يحتوي على هذا النطاق.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/ar/aspose.cells/range/auto_fill/#aspose.cells.range) | ملء النطاق المستهدف تلقائيًا.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/ar/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | ملء النطاق المستهدف تلقائيًا.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/ar/aspose.cells/range/set_style/#aspose.cells.style-bool) | تطبيق نمط الخلية.|
| [`set_style(self, style)`](/cells/python-net/ar/aspose.cells/range/set_style/#aspose.cells.style) | تعيين نمط النطاق.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/ar/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | تعيين حدود المخطط التفصيلي حول نطاق من الخلايا بنفس نمط الحدود واللون.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/ar/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | تعيين حدود المخطط التفصيلي حول نطاق من الخلايا بنفس نمط الحدود واللون.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/ar/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | تعيين حدود الخطوط حول نطاق من الخلايا.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/ar/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | تعيين حدود تفصيلية حول نطاق من الخلايا.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/ar/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | تعيين حدود تفصيلية حول نطاق من الخلايا.|
| [`copy(self, range, options)`](/cells/python-net/ar/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | نسخ النطاق باستخدام خيارات اللصق الخاصة.|
| [`copy(self, range)`](/cells/python-net/ar/aspose.cells/range/copy/#aspose.cells.range) | نسخ البيانات (بما في ذلك الصيغ)، والتنسيق، وكائنات الرسم وما إلى ذلك من نطاق المصدر.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/ar/aspose.cells/range/add_hyperlink/#str-str-str) | يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.|
| [`is_intersect(self, range)`](/cells/python-net/ar/aspose.cells/range/is_intersect/#aspose.cells.range) | يشير إلى ما إذا كان النطاق متقاطعًا.|
| [`intersect(self, range)`](/cells/python-net/ar/aspose.cells/range/intersect/#aspose.cells.range) | يقوم بإرجاع الكائن [`Range`](/cells/python-net/ar/aspose.cells/range) الذي يمثل التقاطع المستطيلي بين نطاقين.|
| [`union_rang(self, range)`](/cells/python-net/ar/aspose.cells/range/union_rang/#aspose.cells.range) | إرجاع نتيجة اتحاد نطاقين.|
| [`union_ranges(self, ranges)`](/cells/python-net/ar/aspose.cells/range/union_ranges/#list) | إرجاع نتيجة اتحاد نطاقين.|
| [`union(self, range)`](/cells/python-net/ar/aspose.cells/range/union/#aspose.cells.range) | إرجاع اتحاد نطاقين.|
| [`is_blank(self)`](/cells/python-net/ar/aspose.cells/range/is_blank/#) | يشير إلى ما إذا كان النطاق يحتوي على قيم.|
| [`merge(self)`](/cells/python-net/ar/aspose.cells/range/merge/#) |دمج مجموعة من الخلايا في خلية واحدة.|
| [`un_merge(self)`](/cells/python-net/ar/aspose.cells/range/un_merge/#) | إلغاء دمج الخلايا المدمجة في هذا النطاق.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/ar/aspose.cells/range/put_value/#str-bool-bool) | يضع قيمة في النطاق، وإذا كان ذلك مناسبًا، فسيتم تحويل القيمة إلى نوع بيانات آخر وسيتم إعادة تعيين تنسيق رقم الخلية.|
| [`apply_style(self, style, flag)`](/cells/python-net/ar/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | ينطبق التنسيقات على نطاق كامل.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/ar/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | تعيين داخل حدود النطاق.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/ar/aspose.cells/range/move_to/#int-int) | نقل النطاق الحالي إلى نطاق الوجهة.|
| [`copy_data(self, range)`](/cells/python-net/ar/aspose.cells/range/copy_data/#aspose.cells.range) | نسخ بيانات الخلية (بما في ذلك الصيغ) من نطاق المصدر.|
| [`copy_value(self, range)`](/cells/python-net/ar/aspose.cells/range/copy_value/#aspose.cells.range) | نسخ قيمة الخلية من نطاق المصدر.|
| [`copy_style(self, range)`](/cells/python-net/ar/aspose.cells/range/copy_style/#aspose.cells.range) | نسخ إعدادات النمط من نطاق المصدر.|
| [`transpose(self)`](/cells/python-net/ar/aspose.cells/range/transpose/#) | نقل (تدوير) البيانات من الصفوف إلى الأعمدة أو العكس.|
| [`get(self, row_offset, column_offset)`](/cells/python-net/ar/aspose.cells/range/get/#int-int) | أضف API for Python عبر .Net. نظرًا لأن هذا [int، int] غير مدعوم|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/ar/aspose.cells/range/get_cell_or_null/#int-int) | يحصل على الكائن [`Cell`](/cells/python-net/ar/aspose.cells/cell) أو لا شيء في هذا النطاق.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/ar/aspose.cells/range/get_offset/#int-int) | يحصل على نطاق [`Range`](/cells/python-net/ar/aspose.cells/range) عن طريق الإزاحة.|
| [`to_image(self, options)`](/cells/python-net/ar/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | تحويل النطاق إلى صورة.|
| [`to_json(self, options)`](/cells/python-net/ar/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | تحويل النطاق إلى القيمة JSON.|
| [`to_html(self, save_options)`](/cells/python-net/ar/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | تحويل النطاق إلى html .|
| [`clear(self)`](/cells/python-net/ar/aspose.cells/range/clear/#) | مسح هذا النطاق.|
| [`clear_contents(self)`](/cells/python-net/ar/aspose.cells/range/clear_contents/#) | مسح محتويات هذا النطاق.|
| [`clear_formats(self)`](/cells/python-net/ar/aspose.cells/range/clear_formats/#) | مسح تنسيقات هذا النطاق.|
| [`clear_comments(self)`](/cells/python-net/ar/aspose.cells/range/clear_comments/#) | مسح تعليقات هذا النطاق.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/ar/aspose.cells/range/clear_hyperlinks/#bool) | يزيل فقط الروابط التشعبية.|



###  ملاحظات

تشير الفئة Range إلى منطقة من جدول بيانات Excel.
باستخدام هذا، يمكنك تنسيق وتعيين قيمة النطاق.
ويمكنك أيضًا نسخ نطاق Excel بكل بساطة.

###  مثال

يوضح المثال التالي كيفية إنشاء نطاق وتعيين قيمة النطاق في Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
* فئة [`Range`](/cells/python-net/ar/aspose.cells/range)
