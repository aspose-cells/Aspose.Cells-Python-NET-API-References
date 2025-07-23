---
title: Style صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1350
url: /ar/aspose.cells/style/
is_root: false
---
##  Style صف
يمثل أسلوب عرض مستند Excel، مثل الخط واللون والمحاذاة والحدود وما إلى ذلك.
يحتوي الكائن Style على كافة سمات النمط (الخط، تنسيق الأرقام، المحاذاة، وما إلى ذلك) كخصائص.



يكشف النوع Style عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/style/__init__/#) | يقوم بتهيئة مثيل جديد للفئة [`Style`](/cells/python-net/ar/aspose.cells/style).|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [background_theme_color](/cells/python-net/ar/aspose.cells/style/background_theme_color) | يحصل على لون سمة الخلفية ويحدده.|
| [foreground_theme_color](/cells/python-net/ar/aspose.cells/style/foreground_theme_color) | يحصل على لون السمة الأمامية ويحدده.|
| [name](/cells/python-net/ar/aspose.cells/style/name) | يحصل على اسم النمط أو يعينه.|
| [pattern](/cells/python-net/ar/aspose.cells/style/pattern) | يحصل على نوع نمط خلفية الخلية أو يعينه.|
| [borders](/cells/python-net/ar/aspose.cells/style/borders) | يحصل على [`BorderCollection`](/cells/python-net/ar/aspose.cells/bordercollection) من النمط.|
| [background_color](/cells/python-net/ar/aspose.cells/style/background_color) | يحصل على لون خلفية النمط أو يعينه.|
| [background_argb_color](/cells/python-net/ar/aspose.cells/style/background_argb_color) | يحصل على لون الخلفية ويضبطه بقيمة ARGB 32 بت.|
| [foreground_color](/cells/python-net/ar/aspose.cells/style/foreground_color) | يحصل على لون المقدمة للنمط أو يعينه.|
| [foreground_argb_color](/cells/python-net/ar/aspose.cells/style/foreground_argb_color) | يحصل على لون المقدمة ويضبطه بقيمة ARGB 32 بت.|
| [has_borders](/cells/python-net/ar/aspose.cells/style/has_borders) | التحقق مما إذا كانت هناك حدود تم تعيينها للنمط.|
| [parent_style](/cells/python-net/ar/aspose.cells/style/parent_style) | يحصل على النمط الأصلي لهذا النمط.|
| [is_number_format_applied](/cells/python-net/ar/aspose.cells/style/is_number_format_applied) | أشر إلى ما إذا كان ينبغي تطبيق تنسيق الأرقام.|
| [is_font_applied](/cells/python-net/ar/aspose.cells/style/is_font_applied) |أشر إلى ما إذا كان ينبغي تطبيق تنسيق الخط.|
| [is_alignment_applied](/cells/python-net/ar/aspose.cells/style/is_alignment_applied) | أشر إلى ما إذا كان ينبغي تطبيق تنسيق المحاذاة.|
| [is_border_applied](/cells/python-net/ar/aspose.cells/style/is_border_applied) | أشر إلى ما إذا كان ينبغي تطبيق تنسيق الحدود.|
| [is_fill_applied](/cells/python-net/ar/aspose.cells/style/is_fill_applied) | أشر إلى ما إذا كان ينبغي تطبيق تنسيق التعبئة.|
| [is_protection_applied](/cells/python-net/ar/aspose.cells/style/is_protection_applied) | أشر إلى ما إذا كان ينبغي تطبيق تنسيق الحماية.|
| [indent_level](/cells/python-net/ar/aspose.cells/style/indent_level) | يُمثل مستوى المسافة البادئة للخلية أو النطاق. يمكن أن يكون عددًا صحيحًا من ٠ إلى ٢٥٠ فقط.|
| [font](/cells/python-net/ar/aspose.cells/style/font) | يحصل على الكائن [`Style.font`](/cells/python-net/ar/aspose.cells/style#font).|
| [rotation_angle](/cells/python-net/ar/aspose.cells/style/rotation_angle) | يمثل زاوية دوران النص.|
| [horizontal_alignment](/cells/python-net/ar/aspose.cells/style/horizontal_alignment) | يحصل على نوع المحاذاة الأفقية للنص في خلية أو يعينه.|
| [vertical_alignment](/cells/python-net/ar/aspose.cells/style/vertical_alignment) | يحصل على نوع المحاذاة الرأسية للنص في خلية أو يعينه.|
| [is_text_wrapped](/cells/python-net/ar/aspose.cells/style/is_text_wrapped) | يحصل على قيمة أو يعينها للإشارة إلى ما إذا كان النص داخل الخلية ملفوفًا أم لا.|
| [number](/cells/python-net/ar/aspose.cells/style/number) | يُحدِّد أو يُحدِّد تنسيق عرض الأرقام والتواريخ. تختلف أنماط التنسيق باختلاف المناطق.|
| [is_locked](/cells/python-net/ar/aspose.cells/style/is_locked) | يحصل على قيمة أو يعينها للإشارة إلى ما إذا كان من الممكن تعديل الخلية أم لا.|
| [custom](/cells/python-net/ar/aspose.cells/style/custom) | يمثل تنسيق سلسلة الأرقام المخصصة لكائن النمط هذا.<br/>إذا لم يتم تعيين تنسيق الرقم المخصص (على سبيل المثال، تنسيق الرقم مدمج)، فسيتم إرجاع "".|
| [culture_custom](/cells/python-net/ar/aspose.cells/style/culture_custom) | يحصل على سلسلة النمط المعتمدة على الثقافة لتنسيق الأرقام ويقوم بتعيينها.<br/>إذا لم يتم تعيين تنسيق رقم لهذا الكائن، فسيتم إرجاع القيمة null.<br/> إذا تم تضمين تنسيق الرقم، فسيتم إرجاع سلسلة النمط المقابلة للرقم المدمج.|
| [invariant_custom](/cells/python-net/ar/aspose.cells/style/invariant_custom) | يحصل على سلسلة النمط المستقلة عن الثقافة لتنسيق الأرقام.<br/>إذا لم يتم تعيين تنسيق رقم لهذا الكائن، فسيتم إرجاع القيمة null.<br/> إذا تم تضمين تنسيق الرقم، فسيتم إرجاع سلسلة النمط المقابلة للرقم المدمج.|
| [is_formula_hidden](/cells/python-net/ar/aspose.cells/style/is_formula_hidden) | يمثل ما إذا كانت الصيغة ستكون مخفية عند حماية ورقة العمل.|
| [shrink_to_fit](/cells/python-net/ar/aspose.cells/style/shrink_to_fit) | يمثل ما إذا كان النص يتقلص تلقائيًا ليتناسب مع عرض العمود المتاح.|
| [text_direction](/cells/python-net/ar/aspose.cells/style/text_direction) | يمثل ترتيب قراءة النص.|
| [is_justify_distributed](/cells/python-net/ar/aspose.cells/style/is_justify_distributed) | يشير إلى ما إذا كان يجب استخدام محاذاة الخلايا المبررة أو الموزعة في السطر الأخير من النص.|
| [quote_prefix](/cells/python-net/ar/aspose.cells/style/quote_prefix) | يشير إلى ما إذا كانت قيمة الخلية تبدأ بعلامة اقتباس مفردة.|
| [is_gradient](/cells/python-net/ar/aspose.cells/style/is_gradient) | يشير إلى ما إذا كان تظليل الخلية عبارة عن نمط تدرج.|
| [is_percent](/cells/python-net/ar/aspose.cells/style/is_percent) | يشير إلى ما إذا كان تنسيق الرقم هو تنسيق النسبة المئوية.|
| [is_date_time](/cells/python-net/ar/aspose.cells/style/is_date_time) | يشير إلى ما إذا كان تنسيق الرقم هو تنسيق تاريخ.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/ar/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | تعيين حدود النمط.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/ar/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | تعيين حدود النمط.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/ar/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |تعيين لون الخلفية.|
| [`copy(self, style)`](/cells/python-net/ar/aspose.cells/style/copy/#aspose.cells.style) | نسخ البيانات من كائن نمط آخر|
| [`update(self)`](/cells/python-net/ar/aspose.cells/style/update/#) | قم بتطبيق النمط المسمى على أنماط الخلايا التي تستخدم هذا النمط المسمى.<br/>يعمل الأمر مثل النقر على زر "موافق" بعد الانتهاء من تعديل النمط.<br/> ينطبق فقط على النمط المسمى.|
| [`is_modified(self, modify_flag)`](/cells/python-net/ar/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | التحقق مما إذا كان قد تم تعديل خصائص النمط المحددة.<br/> يتم استخدامه لنمط ConditionalFormattings للتحقق مما إذا كان يجب استخدام الخصائص المحددة لهذا النمط عند تطبيق ConditionalFormattings على خلية.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/ar/aspose.cells/style/set_custom/#str-bool) | تعيين تنسيق سلسلة الأرقام المخصصة للخلية.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/ar/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | تعيين التعبئة المحددة إلى تدرج لوني ثنائي اللون.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/ar/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | احصل على إعداد التدرج اللوني ثنائي اللون.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/ar/aspose.cells/style/get_two_color_gradient_setting/#) | احصل على إعداد التدرج اللوني ثنائي اللون.|
| [`to_json(self)`](/cells/python-net/ar/aspose.cells/style/to_json/#) | تحويل بيانات الهيكل [`Style`](/cells/python-net/ar/aspose.cells/style) إلى JSON.|



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
