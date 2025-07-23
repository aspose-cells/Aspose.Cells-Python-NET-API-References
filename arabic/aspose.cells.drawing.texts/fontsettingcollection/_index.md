---
title: FontSettingCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells.drawing.texts/fontsettingcollection/
is_root: false
---
##  FontSettingCollection صف
يمثل قائمة [`FontSetting`](/cells/python-net/ar/aspose.cells/fontsetting).



يكشف النوع FontSettingCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [text_alignment](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/text_alignment) |يمثل إعداد محاذاة نص الجسم.|
| [text_paragraphs](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/text_paragraphs) | يحصل على كافة الفقرات.|
| [text](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/text) | يحصل على نص الشكل ويحدده.|
| [html_string](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/html_string) | يحصل على سلسلة HTML التي تحتوي على البيانات وبعض التنسيقات بهذا الشكل ويقوم بتعيينها.|
| [capacity](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`replace(self, index, count, text)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/replace/#int-int-str) | استبدال النص.|
| [`replace(self, old_value, new_value)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/replace/#str-str) | استبدال النص.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/index_of/#aspose.cells.fontsetting-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/index_of/#aspose.cells.fontsetting-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/last_index_of/#aspose.cells.fontsetting) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/last_index_of/#aspose.cells.fontsetting-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/last_index_of/#aspose.cells.fontsetting-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`set_word_art_style(self, style)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) | تعيين نمط WordArt المحدد مسبقًا.|
| [`get_paragraph_enumerator(self)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/get_paragraph_enumerator/#) | يحصل على عداد الفقرات.|
| [`append_text(self, text)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/append_text/#str) | يضيف النص.|
| [`insert_text(self, index, text)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/insert_text/#int-str) | أدخل الفهرس في الموضع.|
| [`delete_text(self, index, count)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/delete_text/#int-int) | حذف بعض الأحرف.|
| [`format(self, start_index, length, font, flag)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/format/#int-int-aspose.cells.font-aspose.cells.styleflag) | تنسيق النص باستخدام إعدادات الخط.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.drawing.texts/fontsettingcollection/binary_search/#aspose.cells.fontsetting) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing.texts`](..)
* فئة [`FontSetting`](/cells/python-net/ar/aspose.cells/fontsetting)
