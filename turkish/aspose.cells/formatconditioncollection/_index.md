---
title: FormatConditionCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 730
url: /tr/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection sınıfı
Koşullu biçimlendirmeyi temsil eder.
FormatConditions en fazla üç koşullu format içerebilir.



FormatConditionCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [count](/cells/python-net/tr/aspose.cells/formatconditioncollection/count) | Koşulların sayısını alır.|
| [range_count](/cells/python-net/tr/aspose.cells/formatconditioncollection/range_count) | Koşullu biçimlendirilmiş aralıkların sayısını alır.|



Biçimlendirme koşulunu dizine göre alır.
###  Dizin oluşturucu
| İsim| Tanım|
| :- | :- |
| [index] |döndürülecek biçimlendirme koşulunun dizini.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add_condition](/cells/python-net/tr/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | Bir biçimlendirme koşulu ekler.|
| [add_condition](/cells/python-net/tr/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType) | Bir biçim koşulu ekleyin.|
| [remove_area](/cells/python-net/tr/aspose.cells/formatconditioncollection/remove_area/#int) | Koşullu biçimlendirilmiş hücre aralığını dizine göre kaldırır.|
| [remove_area](/cells/python-net/tr/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Aralıktaki koşullu biçimlendirmeyi kaldırın.|
| [add](/cells/python-net/tr/aspose.cells/formatconditioncollection/add/#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | FormatConditions'a bir biçimlendirme koşulu ve etkilenen hücre çalması ekler<br/>FormatConditions en fazla üç koşullu format içerebilir.<br/> Koşullu biçimlendirme formüllerinde diğer sayfalara referans verilmesine izin verilmez.|
| [add_area](/cells/python-net/tr/aspose.cells/formatconditioncollection/add_area/#aspose.cells.CellArea) | Koşullu biçimlendirilmiş bir hücre aralığı ekler.|
| [get_cell_area](/cells/python-net/tr/aspose.cells/formatconditioncollection/get_cell_area/#int) | Koşullu biçimlendirilmiş hücre aralığını dizine göre alır.|
| [remove_condition](/cells/python-net/tr/aspose.cells/formatconditioncollection/remove_condition/#int) | Biçimlendirme koşulunu dizine göre kaldırır.|



###  Örnek

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet.
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
