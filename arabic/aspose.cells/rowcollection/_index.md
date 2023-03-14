---
title: RowCollection الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1310
url: /ar/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection الدرجة
لتجميع [Row](/cells/python-net/ar/aspose.cells/row) كائنات تمثل الصفوف الفردية بورقة العمل.



يكشف نوع RowCollection الأعضاء التالية:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [count](/cells/python-net/ar/aspose.cells/rowcollection/count) | الحصول على عدد الصفوف في هذه المجموعة.|



يحصل على عنصر [Row](/cells/python-net/ar/aspose.cells/row) من خلال فهرس الصف المحدد. سيتم إنشاء كائن الصف لفهرس الصف المحدد إذا لم يكن موجودًا من قبل.
###  مفهرس
| اسم| وصف|
| :- | :- |
| [index] |  |


###  طُرق
| طريقة| وصف|
| :- | :- |
| [get_row_by_index(index)](/cells/python-net/ar/aspose.cells/rowcollection/get_row_by_index/#int) | الحصول على كائن الصف حسب الموضع في القائمة.|
| [clear()](/cells/python-net/ar/aspose.cells/rowcollection/clear/#) | امسح كل الصفوف والخلايا.|
| [remove_at(index)](/cells/python-net/ar/aspose.cells/rowcollection/remove_at/#int) | قم بإزالة الصف في الفهرس المحدد|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  أنظر أيضا
* وحدة [aspose.cells](..)
* فئة [Row](/cells/python-net/ar/aspose.cells/row)
