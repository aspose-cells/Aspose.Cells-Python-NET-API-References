---
title: WorksheetCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1610
url: /ar/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection صف
يقوم بتغليف مجموعة من الكائنات [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet).



يكشف النوع WorksheetCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/ar/aspose.cells/worksheetcollection/web_extension_task_panes) | يحصل على قائمة أجزاء المهام.|
| [web_extensions](/cells/python-net/ar/aspose.cells/worksheetcollection/web_extensions) | يحصل على قائمة أجزاء المهام.|
| [threaded_comment_authors](/cells/python-net/ar/aspose.cells/worksheetcollection/threaded_comment_authors) | يحصل على قائمة مؤلفي التعليقات المترابطة.|
| [is_refresh_all_connections](/cells/python-net/ar/aspose.cells/worksheetcollection/is_refresh_all_connections) | يشير إلى ما إذا كان سيتم تحديث كافة الاتصالات عند فتح الملف في MS Excel.|
| [names](/cells/python-net/ar/aspose.cells/worksheetcollection/names) | يحصل على مجموعة من كل كائنات الاسم في جدول البيانات.|
| [active_sheet_name](/cells/python-net/ar/aspose.cells/worksheetcollection/active_sheet_name) | يمثل اسم ورقة العمل النشطة عند فتح جدول البيانات.|
| [active_sheet_index](/cells/python-net/ar/aspose.cells/worksheetcollection/active_sheet_index) | يمثل فهرس ورقة العمل النشطة عند فتح جدول البيانات.|
| [dxfs](/cells/python-net/ar/aspose.cells/worksheetcollection/dxfs) | يحصل على سجلات التنسيق التفاضلية الرئيسية.|
| [xml_maps](/cells/python-net/ar/aspose.cells/worksheetcollection/xml_maps) | يحصل على خرائط XML الموجودة في المصنف ويقوم بتعيينها.|
| [built_in_document_properties](/cells/python-net/ar/aspose.cells/worksheetcollection/built_in_document_properties) | إرجاع مجموعة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty) التي تمثل كافة خصائص المستند المضمنة في جدول البيانات.|
| [custom_document_properties](/cells/python-net/ar/aspose.cells/worksheetcollection/custom_document_properties) | إرجاع مجموعة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty) التي تمثل كافة خصائص المستند المخصصة لجدول البيانات.|
| [ole_size](/cells/python-net/ar/aspose.cells/worksheetcollection/ole_size) | يحصل على الحجم المعروض ويحدده عند استخدام ملف المصنف ككائن Ole.|
| [external_links](/cells/python-net/ar/aspose.cells/worksheetcollection/external_links) |يمثل الروابط الخارجية في مصنف.|
| [table_styles](/cells/python-net/ar/aspose.cells/worksheetcollection/table_styles) | يحصل على الكائن [`WorksheetCollection.table_styles`](/cells/python-net/ar/aspose.cells/worksheetcollection#table_styles).|
| [revision_logs](/cells/python-net/ar/aspose.cells/worksheetcollection/revision_logs) | يمثل سجلات المراجعة.|
| [sensitivity_labels](/cells/python-net/ar/aspose.cells/worksheetcollection/sensitivity_labels) | يمثل جميع علامات الحساسية.|
| [capacity](/cells/python-net/ar/aspose.cells/worksheetcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|



يحصل على العنصر [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet) في الفهرس المحدد.
###  المفهرس
| اسم| وصف|
| :- | :- |
| [index] | مؤشر العنصر المبني على الصفر.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get(self, index)`](/cells/python-net/ar/aspose.cells/worksheetcollection/get/#int) | أضف API for Python عبر .Net. نظرًا لأن هذا [int index] غير مدعوم|
| [`get(self, sheet_name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/get/#str) | أضف API for Python عبر .Net. نظرًا لأن هذا [string sheetName] غير مدعوم|
| [`add(self, type)`](/cells/python-net/ar/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | إضافة ورقة عمل إلى المجموعة.|
| [`add(self)`](/cells/python-net/ar/aspose.cells/worksheetcollection/add/#) | إضافة ورقة عمل إلى المجموعة.|
| [`add(self, sheet_name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/add/#str) | إضافة ورقة عمل إلى المجموعة.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/ar/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | إضافة وظيفة إضافية إلى المصنف|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | إضافة وظيفة إضافية إلى المصنف|
| [`add_copy(self, sheet_name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/add_copy/#str) | يضيف ورقة عمل إلى المجموعة وينسخ البيانات من ورقة عمل موجودة.|
| [`add_copy(self, sheet_index)`](/cells/python-net/ar/aspose.cells/worksheetcollection/add_copy/#int) | يضيف ورقة عمل إلى المجموعة وينسخ البيانات من ورقة عمل موجودة.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/ar/aspose.cells/worksheetcollection/add_copy/#list-list) | نسخ مجموعة من أوراق العمل.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/get_range_by_name/#str) | يحصل على كائن النطاق حسب الاسم المحدد مسبقًا.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/ar/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | يحصل على [`Range`](/cells/python-net/ar/aspose.cells/range) حسب الاسم المحدد مسبقًا أو اسم الجدول|
| [`refresh_pivot_tables(self)`](/cells/python-net/ar/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | تحديث كافة الجداول المحورية في ملف Excel.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/ar/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | تحديث كافة الجداول المحورية في ملف Excel.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells/worksheetcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/ar/aspose.cells/worksheetcollection/create_range/#str-int) | إنشاء كائن [`Range`](/cells/python-net/ar/aspose.cells/range) من عنوان النطاق.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/ar/aspose.cells/worksheetcollection/create_union_range/#str-int) | إنشاء كائن [`Range`](/cells/python-net/ar/aspose.cells/range) من عنوان النطاق.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | يحصل على ورقة العمل حسب اسم الكود.|
| [`sort_names(self)`](/cells/python-net/ar/aspose.cells/worksheetcollection/sort_names/#) | فرز الأسماء المحددة.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/ar/aspose.cells/worksheetcollection/swap_sheet/#int-int) | تبديل الورقتين.|
| [`remove_by_name(self, name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/remove_by_name/#str) | إزالة ورقة حسب اسمها.(CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/ar/aspose.cells/worksheetcollection/remove_by_index/#int) | إزالة فهرس ورقة تلو الأخرى|
| [`remove_at(self, name)`](/cells/python-net/ar/aspose.cells/worksheetcollection/remove_at/#str) | يقوم بإزالة العنصر عند الاسم المحدد.|
| [`get_named_ranges(self)`](/cells/python-net/ar/aspose.cells/worksheetcollection/get_named_ranges/#) | يحصل على جميع النطاقات المحددة مسبقًا في جدول البيانات.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/ar/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | يحصل على جميع النطاقات المحددة مسبقًا في جدول البيانات.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/ar/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | تعيين الحجم المعروض عند استخدام ملف Workbook ككائن Ole.|
| [`clear_pivottables(self)`](/cells/python-net/ar/aspose.cells/worksheetcollection/clear_pivottables/#) |مسح جداول المحور من جدول البيانات.|
| [`refresh_all(self)`](/cells/python-net/ar/aspose.cells/worksheetcollection/refresh_all/#) | قم بتحديث كافة جداول البيانات المحورية والمخططات باستخدام مصدر البيانات المحورية.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty)
* فئة [`Range`](/cells/python-net/ar/aspose.cells/range)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
