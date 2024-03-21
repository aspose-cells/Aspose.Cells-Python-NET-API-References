---
title: FindOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 660
url: /ar/aspose.cells/findoptions/
is_root: false
---
##  FindOptions صف
يمثل خيارات البحث.



يكشف النوع FindOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/findoptions/__init__/#) |إنشاء مثيل جديد لـ FindOptions|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_case_sensitive](/cells/python-net/ar/aspose.cells/findoptions/is_case_sensitive) | يشير إلى ما إذا كانت السلسلة التي تم البحث عنها حساسة لحالة الأحرف.|
| [case_sensitive](/cells/python-net/ar/aspose.cells/findoptions/case_sensitive) | يشير إلى ما إذا كانت السلسلة التي تم البحث عنها حساسة لحالة الأحرف.|
| [look_at_type](/cells/python-net/ar/aspose.cells/findoptions/look_at_type) | انظر إلى النوع.|
| [is_range_set](/cells/python-net/ar/aspose.cells/findoptions/is_range_set) | يشير إلى ما إذا كان النطاق الذي تم البحث عنه محددًا أم لا.|
| [search_next](/cells/python-net/ar/aspose.cells/findoptions/search_next) | ترتيب البحث. صحيح: البحث التالي. خطأ: البحث السابق.|
| [search_backward](/cells/python-net/ar/aspose.cells/findoptions/search_backward) | ما إذا كان البحث للخلف عن الخلايا.|
| [seach_order_by_rows](/cells/python-net/ar/aspose.cells/findoptions/seach_order_by_rows) | يشير إلى ما إذا كان ترتيب البحث حسب الصفوف أو الأعمدة.|
| [look_in_type](/cells/python-net/ar/aspose.cells/findoptions/look_in_type) | ابحث في النوع.|
| [regex_key](/cells/python-net/ar/aspose.cells/findoptions/regex_key) | يشير إلى ما إذا كان المفتاح الذي تم البحث عنه هو regex.<br/> إذا كان صحيحًا، فسيتم اعتبار المفتاح الذي تم البحث عنه بمثابة regex وتحليله. وإلا فسيتم تحليل المفتاح وفقًا للقواعد الموجودة في MS Excel.|
| [value_type_sensitive](/cells/python-net/ar/aspose.cells/findoptions/value_type_sensitive) | يشير إلى ما إذا كان نوع قيمة الخلية التي تم البحث عنها يجب أن يكون هو نفسه مع المفتاح الذي تم البحث عنه.|
| [style](/cells/python-net/ar/aspose.cells/findoptions/style) | التنسيق المطلوب البحث عنه.|
| [convert_numeric_data](/cells/python-net/ar/aspose.cells/findoptions/convert_numeric_data) | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم تحويل قيمة السلسلة التي تم البحث عنها إلى بيانات رقمية.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [get_range](/cells/python-net/ar/aspose.cells/findoptions/get_range/#) | الحصول على النطاق الذي تم البحث عنه وتعيينه.|
| [set_range](/cells/python-net/ar/aspose.cells/findoptions/set_range/#aspose.cells.CellArea) | يضبط النطاق الذي تم البحث فيه.|



###  مثال

```python
from aspose.cells import CellArea, FindOptions, LookInType, Workbook

# Instantiate the workbook object
workbook = Workbook("book1.xls")
# Get Cells collection
cells = workbook.worksheets[0].cells
# Instantiate FindOptions Object
findOptions = FindOptions()
# Create a Cells Area
ca = CellArea()
ca.start_row = 8
ca.start_column = 2
ca.end_row = 17
ca.end_column = 13
# Set cells area for find options
findOptions.set_range(ca)
# Set searching properties
findOptions.search_backward = False
findOptions.seach_order_by_rows = True
findOptions.look_in_type = LookInType.VALUES
# Find the cell with 0 value
cell = cells.find(0, None, findOptions)

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
