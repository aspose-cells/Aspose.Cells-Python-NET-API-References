---
title: RowCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1350
url: /ar/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection صف
يجمع الكائنات [`Row`](/cells/python-net/ar/aspose.cells/row) التي تمثل الصفوف الفردية في ورقة العمل.



يكشف النوع RowCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [count](/cells/python-net/ar/aspose.cells/rowcollection/count) | الحصول على عدد الصفوف في هذه المجموعة.|



يحصل على كائن [`Row`](/cells/python-net/ar/aspose.cells/row) حسب فهرس الصف المحدد. سيتم إنشاء كائن الصف الخاص بفهرس الصف المحدد إذا لم يكن موجودًا من قبل.
###  مفهرس
| اسم| وصف|
| :- | :- |
| [index] |  |


###  طُرق
| طريقة| وصف|
| :- | :- |
| [get_enumerator](/cells/python-net/ar/aspose.cells/rowcollection/get_enumerator/#bool-bool) | الحصول على عداد يقوم بتكرار الصفوف خلال هذه المجموعة|
| [get_row_by_index](/cells/python-net/ar/aspose.cells/rowcollection/get_row_by_index/#int) | الحصول على كائن الصف حسب الموضع في القائمة.|
| [clear](/cells/python-net/ar/aspose.cells/rowcollection/clear/#) | مسح كافة الصفوف والخلايا.|
| [remove_at](/cells/python-net/ar/aspose.cells/rowcollection/remove_at/#int) | قم بإزالة عنصر الصف في الفهرس (الموضع) المحدد في هذه المجموعة.|



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
* الوحدة [`aspose.cells`](..)
* فئة [`Row`](/cells/python-net/ar/aspose.cells/row)
