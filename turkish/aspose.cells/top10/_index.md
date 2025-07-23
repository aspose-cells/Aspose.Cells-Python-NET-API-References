---
title: Top10 sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1460
url: /tr/aspose.cells/top10/
is_root: false
---
##  Top10 sınıfı
 Top10 koşullu biçimlendirme kuralını açıklayın.
Bu koşullu biçimlendirme kuralı, hangi hücrelerin vurgulandığını belirtir.
değerler belirtildiği gibi üst N veya alt N parantezine düşer.



Top10 türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/top10/__init__/#) | Top10'un yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_percent](/cells/python-net/tr/aspose.cells/top10/is_percent) | "En üst/en alt n" kuralının "en üst/en alt yüzde n" kuralı olup olmadığını alın veya ayarlayın.<br/> Varsayılan değer false'tur.|
| [is_bottom](/cells/python-net/tr/aspose.cells/top10/is_bottom) | "Top/bottom n" kuralının "bottom n" kuralı olup olmadığını alın veya ayarlayın.<br/> Varsayılan değer false'tur.|
| [rank](/cells/python-net/tr/aspose.cells/top10/rank) | "Top/bottom n" koşullu biçimlendirme kuralında "n" değerini al veya ayarla.<br/>IsPercent true ise değer 0 ile 100 arasında olmalıdır.<br/>Aksi takdirde 0 ile 1000 arasında olmalıdır.<br/> Varsayılan değer 10'dur.|



###  Örnek

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea.create_cell_area(0, 0, 10, 10)
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.TOP10, OperatorType.NONE, None, None)
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
top10 = fc.top10
# Set the Top N
top10.rank = 5
# Saving the Excel file
workbook.save("output.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
