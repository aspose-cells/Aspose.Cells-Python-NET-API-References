---
title: FormatCondition klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 700
url: /sv/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition klass
Representerar villkor för villkorlig formatering.



Typen FormatCondition avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [formula1](/cells/python-net/sv/aspose.cells/formatcondition/formula1) | Hämtar och anger värdet eller uttrycket som är associerat med villkorsstyrd formatering.|
| [formula2](/cells/python-net/sv/aspose.cells/formatcondition/formula2) | Hämtar och anger värdet eller uttrycket som är associerat med villkorsstyrd formatering.|
| [operator](/cells/python-net/sv/aspose.cells/formatcondition/operator) | Hämtar och anger operatortypen för villkorsstyrt format.|
| [stop_if_true](/cells/python-net/sv/aspose.cells/formatcondition/stop_if_true) |Sant, inga regler med lägre prioritet kan tillämpas över denna regel när regeln utvärderas till sant.<br/> Gäller endast för Excel 2007;|
| [priority](/cells/python-net/sv/aspose.cells/formatcondition/priority) | Prioriteten för denna villkorsstyrda formateringsregel. Detta värde används för att avgöra vilken<br/>formatet bör utvärderas och renderas. Lägre numeriska värden har högre prioritet än<br/> högre numeriska värden, där '1' är den högsta prioriteten.|
| [style](/cells/python-net/sv/aspose.cells/formatcondition/style) | Hämtar eller ställer in stilen för villkorligt formaterade cellområden.|
| [type](/cells/python-net/sv/aspose.cells/formatcondition/type) | Hämtar och anger om det villkorliga formatet är av typen.|
| [icon_set](/cells/python-net/sv/aspose.cells/formatcondition/icon_set) | Hämta den villkorliga formateringens "IconSet"-instans.<br/>Standardinstansens IconSetType är TrafficLights31.<br/> Gäller endast för typen = IconSet.|
| [data_bar](/cells/python-net/sv/aspose.cells/formatcondition/data_bar) | Hämta den villkorliga formateringens "DataBar"-instans.<br/>Standardinstansens färg är blå.<br/> Gäller endast för typen DataBar.|
| [color_scale](/cells/python-net/sv/aspose.cells/formatcondition/color_scale) | Hämta den villkorliga formateringens "ColorScale"-instans.<br/>Standardinstansen är en "grön-gul-röd" 3ColorScale.<br/> Gäller endast för typen = ColorScale.|
| [top10](/cells/python-net/sv/aspose.cells/formatcondition/top10) | Hämta den villkorliga formateringens "Top10"-instans.<br/>Standardinstansens regel markerar celler vars<br/>värdena hamnar i topp 10-klassen.<br/> Gäller endast för typen Top10.|
| [above_average](/cells/python-net/sv/aspose.cells/formatcondition/above_average) |Hämta den villkorliga formateringens "AboveAverage"-instans.<br/> Standardinstansens regel markerar celler som är<br/>över genomsnittet för alla värden inom intervallet.<br/> Gäller endast för typen = AboveAverage.|
| [text](/cells/python-net/sv/aspose.cells/formatcondition/text) | Textvärdet i en villkorsstyrd formateringsregel av typen "text innehåller".<br/>Gäller endast för typen = containsText, notContainsText, beginsWith och endsWith.<br/> Standardvärdet är null.|
| [time_period](/cells/python-net/sv/aspose.cells/formatcondition/time_period) | Den tillämpliga tidsperioden i en villkorsstyrd formateringsregel för "datum inträffar...".<br/>Gäller endast för typen = timePeriod.<br/> Standardvärdet är TimePeriodType.Today.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/formatcondition/get_formula1/#bool-bool) | Hämtar värdet eller uttrycket som är associerat med detta formatvillkor.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/sv/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Hämtar värdet eller uttrycket för cellens villkorsstyrda formatering.|
| [`get_formula1(self, row, column)`](/cells/python-net/sv/aspose.cells/formatcondition/get_formula1/#int-int) | Hämtar formeln för cellens villkorsstyrda formatering.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/formatcondition/get_formula2/#bool-bool) | Hämtar värdet eller uttrycket som är associerat med detta formatvillkor.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/sv/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Hämtar värdet eller uttrycket för cellens villkorsstyrda formatering.|
| [`get_formula2(self, row, column)`](/cells/python-net/sv/aspose.cells/formatcondition/get_formula2/#int-int) | Hämtar formeln för cellens villkorsstyrda formatering.|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Anger värdet eller uttrycket som är associerat med detta formatvillkor.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Anger värdet eller uttrycket som är associerat med detta formatvillkor.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Anger värdet eller uttrycket som är associerat med detta formatvillkor.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
