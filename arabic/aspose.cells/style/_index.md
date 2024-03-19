---
title: Style صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1460
url: /ar/aspose.cells/style/
is_root: false
---
##  Style صف
يمثل نمط عرض مستند Excel، مثل الخط واللون والمحاذاة والحدود وما إلى ذلك.
يحتوي الكائن Style على كافة سمات النمط (الخط وتنسيق الأرقام والمحاذاة وما إلى ذلك) كخصائص.



يكشف النوع Style عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/style/__init__/#) | تهيئة مثيل جديد للفئة [`Style`](/cells/python-net/ar/aspose.cells/style).|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [background_theme_color](/cells/python-net/ar/aspose.cells/style/background_theme_color) | الحصول على لون سمة الخلفية وتعيينه.|
| [foreground_theme_color](/cells/python-net/ar/aspose.cells/style/foreground_theme_color) | الحصول على لون السمة الأمامية وتعيينه.|
| [name](/cells/python-net/ar/aspose.cells/style/name) | الحصول على اسم النمط أو تعيينه.|
| [pattern](/cells/python-net/ar/aspose.cells/style/pattern) |الحصول على نوع نمط خلفية الخلية أو تعيينه.|
| [borders](/cells/python-net/ar/aspose.cells/style/borders) | يحصل على [`BorderCollection`](/cells/python-net/ar/aspose.cells/bordercollection) من النمط.|
| [background_color](/cells/python-net/ar/aspose.cells/style/background_color) | الحصول على لون خلفية النمط أو تعيينه.|
| [background_argb_color](/cells/python-net/ar/aspose.cells/style/background_argb_color) | الحصول على لون الخلفية وتعيينه بقيمة ARGB 32 بت.|
| [foreground_color](/cells/python-net/ar/aspose.cells/style/foreground_color) | الحصول على أو تعيين اللون الأمامي للنمط.|
| [foreground_argb_color](/cells/python-net/ar/aspose.cells/style/foreground_argb_color) | الحصول على اللون الأمامي وتعيينه بقيمة ARGB 32 بت.|
| [has_borders](/cells/python-net/ar/aspose.cells/style/has_borders) | التحقق مما إذا كانت هناك حدود تم تعيينها للنمط.|
| [parent_style](/cells/python-net/ar/aspose.cells/style/parent_style) | يحصل على النمط الأصلي لهذا النمط.|
| [is_number_format_applied](/cells/python-net/ar/aspose.cells/style/is_number_format_applied) | الإشارة إلى ما إذا كان ينبغي تطبيق تنسيق الأرقام.|
| [is_font_applied](/cells/python-net/ar/aspose.cells/style/is_font_applied) | وضح ما إذا كان يجب تطبيق تنسيق الخط.|
| [is_alignment_applied](/cells/python-net/ar/aspose.cells/style/is_alignment_applied) | وضح ما إذا كان ينبغي تطبيق تنسيق المحاذاة.|
| [is_border_applied](/cells/python-net/ar/aspose.cells/style/is_border_applied) | وضح ما إذا كان ينبغي تطبيق تنسيق الحدود.|
| [is_fill_applied](/cells/python-net/ar/aspose.cells/style/is_fill_applied) | الإشارة إلى ما إذا كان ينبغي تطبيق تنسيق التعبئة.|
| [is_protection_applied](/cells/python-net/ar/aspose.cells/style/is_protection_applied) | وضح ما إذا كان ينبغي تطبيق تنسيق الحماية.|
| [indent_level](/cells/python-net/ar/aspose.cells/style/indent_level) | يمثل مستوى المسافة البادئة للخلية أو النطاق. يمكن أن يكون عددًا صحيحًا فقط من 0 إلى 250.|
| [font](/cells/python-net/ar/aspose.cells/style/font) | يحصل على كائن [`Style.font`](/cells/python-net/ar/aspose.cells/style#font).|
| [rotation_angle](/cells/python-net/ar/aspose.cells/style/rotation_angle) | يمثل زاوية دوران النص.|
| [horizontal_alignment](/cells/python-net/ar/aspose.cells/style/horizontal_alignment) |الحصول على أو تعيين نوع المحاذاة الأفقية للنص في الخلية.|
| [vertical_alignment](/cells/python-net/ar/aspose.cells/style/vertical_alignment) | الحصول على نوع المحاذاة العمودية للنص في الخلية أو تعيينه.|
| [is_text_wrapped](/cells/python-net/ar/aspose.cells/style/is_text_wrapped) | الحصول على قيمة أو تعيينها تشير إلى ما إذا كان النص داخل الخلية ملتفًا أم لا.|
| [number](/cells/python-net/ar/aspose.cells/style/number) | الحصول على تنسيق عرض الأرقام والتواريخ أو تعيينه. تختلف أنماط التنسيق باختلاف المناطق.|
| [is_locked](/cells/python-net/ar/aspose.cells/style/is_locked) | الحصول على قيمة أو تعيينها تشير إلى إمكانية تعديل الخلية أم لا.|
| [custom](/cells/python-net/ar/aspose.cells/style/custom) | يمثل سلسلة تنسيق الأرقام المخصصة لكائن النمط هذا.<br/> إذا لم يتم تعيين تنسيق الأرقام المخصص (على سبيل المثال، تنسيق الأرقام مدمج)، فسيتم إرجاع "".|
| [culture_custom](/cells/python-net/ar/aspose.cells/style/culture_custom) | الحصول على سلسلة النمط المعتمدة على الثقافة لتنسيق الأرقام وتعيينها.<br/>إذا لم يتم تعيين تنسيق أرقام لهذا الكائن، فسيتم إرجاع القيمة null.<br/> إذا كان تنسيق الأرقام مدمجًا، فسيتم إرجاع سلسلة النمط المقابلة للرقم المدمج.|
| [invariant_custom](/cells/python-net/ar/aspose.cells/style/invariant_custom) | الحصول على سلسلة النمط المستقلة عن الثقافة لتنسيق الأرقام.<br/>إذا لم يتم تعيين تنسيق أرقام لهذا الكائن، فسيتم إرجاع القيمة null.<br/> إذا كان تنسيق الأرقام مدمجًا، فسيتم إرجاع سلسلة النمط المقابلة للرقم المدمج.|
| [is_formula_hidden](/cells/python-net/ar/aspose.cells/style/is_formula_hidden) |يمثل ما إذا كان سيتم إخفاء الصيغة عندما تكون ورقة العمل محمية.|
| [shrink_to_fit](/cells/python-net/ar/aspose.cells/style/shrink_to_fit) | يمثل ما إذا كان النص يتقلص تلقائيًا ليتناسب مع عرض العمود المتاح.|
| [text_direction](/cells/python-net/ar/aspose.cells/style/text_direction) | يمثل ترتيب قراءة النص.|
| [is_justify_distributed](/cells/python-net/ar/aspose.cells/style/is_justify_distributed) | يشير إلى ما إذا كان ينبغي استخدام الخلايا المبررة أو المحاذاة الموزعة في السطر الأخير من النص.|
| [quote_prefix](/cells/python-net/ar/aspose.cells/style/quote_prefix) | يشير إلى ما إذا كانت قيمة الخلية تبدأ بعلامة اقتباس مفردة.|
| [is_gradient](/cells/python-net/ar/aspose.cells/style/is_gradient) | يشير إلى ما إذا كان تظليل الخلية عبارة عن نمط متدرج.|
| [is_percent](/cells/python-net/ar/aspose.cells/style/is_percent) | الإشارة إلى ما إذا كان تنسيق الأرقام هو تنسيق النسبة المئوية.|
| [is_date_time](/cells/python-net/ar/aspose.cells/style/is_date_time) | الإشارة إلى ما إذا كان تنسيق الأرقام هو تنسيق تاريخ.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_border](/cells/python-net/ar/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | يحدد حدود النمط.|
| [set_border](/cells/python-net/ar/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | يحدد حدود النمط.|
| [set_pattern_color](/cells/python-net/ar/aspose.cells/style/set_pattern_color/#aspose.cells.BackgroundType-aspose.pydrawing.Color-aspose.pydrawing.Color) | يضبط لون الخلفية.|
| [copy](/cells/python-net/ar/aspose.cells/style/copy/#aspose.cells.Style) | نسخ البيانات من كائن نمط آخر|
| [update](/cells/python-net/ar/aspose.cells/style/update/#) | قم بتطبيق النمط المسمى على أنماط الخلايا التي تستخدم هذا النمط المسمى.<br/>إنه يعمل مثل النقر على زر "موافق" بعد الانتهاء من تعديل النمط.<br/> ينطبق فقط على النمط المسمى.|
| [is_modified](/cells/python-net/ar/aspose.cells/style/is_modified/#aspose.cells.StyleModifyFlag) | التحقق مما إذا كان قد تم تعديل الخصائص المحددة للنمط.<br/>يُستخدم لنمط التنسيقات الشرطية للتحقق مما إذا كان يجب استخدام الخصائص المحددة لهذا النمط عند تطبيق التنسيقات الشرطية على الخلية.|
| [set_custom](/cells/python-net/ar/aspose.cells/style/set_custom/#str-bool) | لتعيين سلسلة تنسيق الأرقام المخصصة للخلية.|
| [set_two_color_gradient](/cells/python-net/ar/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int) | يضبط التعبئة المحددة على تدرج لونين.|
| [get_two_color_gradient](/cells/python-net/ar/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.Color&-aspose.pydrawing.Color&-any-any) | احصل على إعداد التدرج ثنائي اللون.|
| [get_two_color_gradient_setting](/cells/python-net/ar/aspose.cells/style/get_two_color_gradient_setting/#) | احصل على إعداد التدرج ثنائي اللون.|
| [to_json](/cells/python-net/ar/aspose.cells/style/to_json/#) | تحويل [`Style`](/cells/python-net/ar/aspose.cells/style) إلى JSON بيانات الهيكل.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`BorderCollection`](/cells/python-net/ar/aspose.cells/bordercollection)
* فئة [`Style`](/cells/python-net/ar/aspose.cells/style)
