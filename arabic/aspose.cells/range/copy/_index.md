---
title: طريقة copy
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 50
url: /ar/aspose.cells/range/copy/
is_root: false
---
##  copy {#aspose.cells.Range}
نسخ البيانات (بما في ذلك الصيغ)، والتنسيق، والكائنات الرسومية وما إلى ذلك من نطاق مصدر.



```python
def copy(self, range):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/ar/aspose.cells/range) |المصدر [`Range`](/cells/python-net/ar/aspose.cells/range) كائن.|

###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy {#aspose.cells.Range-aspose.cells.PasteOptions}
نسخ النطاق مع لصق الخيارات الخاصة.



```python
def copy(self, range, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/ar/aspose.cells/range) | نطاق المصدر.|
| options | [`PasteOptions`](/cells/python-net/ar/aspose.cells/pasteoptions) | لصق الخيارات الخاصة.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Range`](/cells/python-net/ar/aspose.cells/range)
