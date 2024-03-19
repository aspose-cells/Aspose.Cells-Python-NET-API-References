---
title: Row صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1340
url: /ar/aspose.cells/row/
is_root: false
---
##  Row صف
يمثل صفًا واحدًا في ورقة العمل.



يكشف النوع Row عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_blank](/cells/python-net/ar/aspose.cells/row/is_blank) | الإشارة إلى ما إذا كان الصف يحتوي على أية بيانات|
| [is_collapsed](/cells/python-net/ar/aspose.cells/row/is_collapsed) | ما إذا كان الصف مطويًا|
| [height](/cells/python-net/ar/aspose.cells/row/height) | الحصول على ارتفاع الصف وتعيينه بوحدة النقاط.|
| [is_hidden](/cells/python-net/ar/aspose.cells/row/is_hidden) | يشير إلى ما إذا كان الصف مخفيًا.|
| [index](/cells/python-net/ar/aspose.cells/row/index) | يحصل على فهرس هذا الصف.|
| [group_level](/cells/python-net/ar/aspose.cells/row/group_level) | الحصول على مستوى المجموعة للصف.|
| [is_height_matched](/cells/python-net/ar/aspose.cells/row/is_height_matched) | يشير إلى ما إذا كان ارتفاع الصف يطابق إعداد الخط الافتراضي الحالي للمصنف.<br/>تشير هذه الخاصية أيضًا إلى أن ارتفاع الصف "تلقائي" بدون قيمة الارتفاع المخصصة التي يحددها المستخدم.|
| [has_custom_style](/cells/python-net/ar/aspose.cells/row/has_custom_style) | يشير إلى ما إذا كان هذا الصف يحتوي على إعدادات نمط مخصصة (تختلف عن الإعداد الافتراضي الموروث من المصنف).|
| [first_cell](/cells/python-net/ar/aspose.cells/row/first_cell) | الحصول على كائن الخلية الأول في الصف.|
| [first_data_cell](/cells/python-net/ar/aspose.cells/row/first_data_cell) | الحصول على أول خلية غير فارغة في الصف.|
| [last_cell](/cells/python-net/ar/aspose.cells/row/last_cell) | الحصول على كائن الخلية الأخير في الصف.|
| [last_data_cell](/cells/python-net/ar/aspose.cells/row/last_data_cell) | الحصول على آخر خلية غير فارغة في الصف.|



يحصل على الخلية.
###  مفهرس
| اسم| وصف|
| :- | :- |
| [index] | فهرس العمود|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [get_cell_by_index](/cells/python-net/ar/aspose.cells/row/get_cell_by_index/#int) | احصل على الخلية حسب فهرس محدد في مجموعة الخلايا لهذا الصف.|
| [get_enumerator](/cells/python-net/ar/aspose.cells/row/get_enumerator/#bool-bool) | الحصول على عداد يقوم بتكرار الخلايا خلال هذا الصف.|
| [get_cell_or_null](/cells/python-net/ar/aspose.cells/row/get_cell_or_null/#int) | يحصل على الخلية أو فارغة في الفهرس المحدد.|
| [get_style](/cells/python-net/ar/aspose.cells/row/get_style/#) | يحصل على نمط هذا الصف.|
| [set_style](/cells/python-net/ar/aspose.cells/row/set_style/#aspose.cells.Style) | يحدد نمط هذا الصف.|
| [copy_settings](/cells/python-net/ar/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) | نسخ إعدادات الصف، مثل النمط، الارتفاع، الرؤية، ...إلخ.|
| [apply_style](/cells/python-net/ar/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | يطبق التنسيقات على صف كامل.|
| [equals](/cells/python-net/ar/aspose.cells/row/equals/#aspose.cells.Row) | التحقق مما إذا كان هذا الكائن يشير إلى نفس الصف مع كائن صف آخر.|



###  مثال

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
