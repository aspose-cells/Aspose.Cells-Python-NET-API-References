---
title: RowCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1240
url: /ar/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection صف
يقوم بتجميع الكائنات [`Row`](/cells/python-net/ar/aspose.cells/row) التي تمثل الصفوف الفردية في ورقة العمل.



يكشف النوع RowCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [count](/cells/python-net/ar/aspose.cells/rowcollection/count) | يحصل على عدد الصفوف في هذه المجموعة.|



يحصل على الكائن [`Row`](/cells/python-net/ar/aspose.cells/row) بمؤشر الصف المُعطى. سيتم إنشاء كائن الصف بمؤشر الصف المُعطى إذا لم يكن موجودًا من قبل.
###  المفهرس
| اسم| وصف|
| :- | :- |
| [index] |  |


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/ar/aspose.cells/rowcollection/get_enumerator/#bool-bool) | يحصل على مُعَدِّد يكرر الصفوف عبر هذه المجموعة|
| [`get_row_by_index(self, index)`](/cells/python-net/ar/aspose.cells/rowcollection/get_row_by_index/#int) | يحصل على كائن الصف حسب الموضع في القائمة.|
| [`clear(self)`](/cells/python-net/ar/aspose.cells/rowcollection/clear/#) | مسح كافة الصفوف والخلايا.|
| [`remove_at(self, index)`](/cells/python-net/ar/aspose.cells/rowcollection/remove_at/#int) | قم بإزالة عنصر الصف عند الفهرس (الموضع) المحدد في هذه المجموعة.|



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
