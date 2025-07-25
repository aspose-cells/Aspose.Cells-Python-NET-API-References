---
title: copy yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells.drawing/picture/copy/
is_root: false
---
##  copy(self, source, options) {#aspose.cells.drawing.Picture-aspose.cells.CopyOptions}
Resmi kopyala.



```python

def copy(self, source, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source | [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture) | Kaynak resim.|
| options | [`CopyOptions`](/cells/python-net/tr/aspose.cells/copyoptions) | Kopyalama seçenekleri.|

###  Örnek

```python
from aspose.cells import CopyOptions, Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# insert first picture
imgIndex1 = worksheet.pictures.add(1, 1, "1.png")
# Get the inserted picture object
pic1 = worksheet.pictures[imgIndex1]
# insert second picture
imgIndex2 = worksheet.pictures.add(1, 9, "2.jpeg")
# Get the inserted picture object
pic2 = worksheet.pictures[imgIndex2]
# Copy picture 1 to picture 2.You'll get two picture 1 objects that are superimposed on top of each other.
opt = CopyOptions()
pic2.copy(pic1, opt)
# Save the excel file.
workbook.save("result.xlsx")

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture)
