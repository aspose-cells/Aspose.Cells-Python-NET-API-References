---
title: FormatConditionCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 710
url: /tr/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection sınıfı
Koşullu biçimlendirmeyi temsil eder.
FormatConditions en fazla üç koşullu biçimlendirme içerebilir.



FormatConditionCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [count](/cells/python-net/tr/aspose.cells/formatconditioncollection/count) | Koşulların sayısını alır.|
| [range_count](/cells/python-net/tr/aspose.cells/formatconditioncollection/range_count) | Koşullu biçimlendirilmiş aralıkların sayısını alır.|



Dizin bazında biçimlendirme koşulunu alır.
###  Dizinleyici
| İsim| Tanım|
| :- | :- |
| [index] | döndürülecek biçimlendirme koşulunun dizini.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_condition(self, type, operator_type, formula1, formula2)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) | Biçimlendirme koşulu ekler.|
| [`add_condition(self, type)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype) | Biçimlendirme koşulu ekleyin.|
| [`remove_area(self, index)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/remove_area/#int) | Dizine göre koşullu biçimlendirilmiş hücre aralığını kaldırır.|
| [`remove_area(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Aralıktaki koşullu biçimlendirmeyi kaldırın.|
| [`add(self, cell_area, type, operator_type, formula1, formula2)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/add/#aspose.cells.cellarea-aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) |FormatConditions'a bir biçimlendirme koşulu ve etkilenen hücre aralığı ekler<br/>FormatConditions en fazla üç koşullu biçimlendirme içerebilir.<br/> Koşullu biçimlendirme formüllerinde diğer sayfalara atıf yapılmasına izin verilmez.|
| [`add_area(self, cell_area)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/add_area/#aspose.cells.cellarea) | Koşullu biçimlendirilmiş bir hücre aralığı ekler.|
| [`get_cell_area(self, index)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/get_cell_area/#int) | Dizine göre koşullu biçimlendirilmiş hücre aralığını alır.|
| [`remove_condition(self, index)`](/cells/python-net/tr/aspose.cells/formatconditioncollection/remove_condition/#int) | Dizin bazında biçimlendirme koşulunu kaldırır.|



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
