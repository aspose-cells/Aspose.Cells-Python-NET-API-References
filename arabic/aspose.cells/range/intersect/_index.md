---
title: طريقة intersect
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 170
url: /ar/aspose.cells/range/intersect/
is_root: false
---
##  intersect(self, range) {#aspose.cells.Range}
يقوم بإرجاع الكائن [`Range`](/cells/python-net/ar/aspose.cells/range) الذي يمثل التقاطع المستطيلي بين نطاقين.


###  عائدات

إرجاع الكائن [`Range`](/cells/python-net/ar/aspose.cells/range)


```python

def intersect(self, range):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/ar/aspose.cells/range) | المدى المتقاطع.|
###  ملاحظات

إذا لم يتقاطع النطاقان، فسيتم إرجاع قيمة null.
###  مثال


```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A3:A10")
# Get intersected range of the two ranges.
intersectRange = range1.intersect(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Range`](/cells/python-net/ar/aspose.cells/range)
