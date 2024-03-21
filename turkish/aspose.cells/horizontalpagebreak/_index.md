---
title: HorizontalPageBreak sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 780
url: /tr/aspose.cells/horizontalpagebreak/
is_root: false
---
##  HorizontalPageBreak sınıfı
Yatay sayfa sonunu temsil eden nesneyi kapsüller.



HorizontalPageBreak türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [start_column](/cells/python-net/tr/aspose.cells/horizontalpagebreak/start_column) | Bu yatay sayfa sonunun başlangıç sütunu dizinini alır.|
| [end_column](/cells/python-net/tr/aspose.cells/horizontalpagebreak/end_column) | Bu yatay sayfa sonunun son sütun dizinini alır.|
| [row](/cells/python-net/tr/aspose.cells/horizontalpagebreak/row) | Sıfır tabanlı satır dizinini alır.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Add a page break at cell Y30
Index = worksheet.horizontal_page_breaks.add("Y30")
# get the newly added horizontal page break
hPageBreak = worksheet.horizontal_page_breaks[Index]

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
