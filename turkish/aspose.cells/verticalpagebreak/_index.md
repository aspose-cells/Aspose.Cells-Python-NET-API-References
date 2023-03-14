---
title: VerticalPageBreak sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1560
url: /tr/aspose.cells/verticalpagebreak/
is_root: false
---
##  VerticalPageBreak sınıfı
Dikey bir sayfa sonunu temsil eden nesneyi kapsüller.



VerticalPageBreak türü aşağıdaki üyeleri gösterir:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [start_row](/cells/python-net/tr/aspose.cells/verticalpagebreak/start_row) | Dikey sayfa sonunun başlangıç satır dizinini alır.|
| [end_row](/cells/python-net/tr/aspose.cells/verticalpagebreak/end_row) | Dikey sayfa sonunun son satır dizinini alır.|
| [column](/cells/python-net/tr/aspose.cells/verticalpagebreak/column) | Dikey sayfa sonunun sütun dizinini alır.|



###  Örnek

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Ayrıca bakınız
* modül [aspose.cells](..)
