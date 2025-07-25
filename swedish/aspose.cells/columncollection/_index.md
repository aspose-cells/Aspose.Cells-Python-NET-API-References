---
title: ColumnCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 250
url: /sv/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection klass
Samling av [`Column`](/cells/python-net/sv/aspose.cells/column)-objekten som representerar de enskilda kolumnerna (inställningarna) i ett kalkylblad.
Kolumnobjektet representerar endast inställningar som kolumnbredd, stilar etc. för hela kolumnen,
har inget att göra med det faktum att det finns icke-tomma celler (data) eller inte i motsvarande kolumn.
Och "Antal" för den här samlingen representerar endast de antal kolumnobjekt som har instansierats i den här samlingen,
har inget att göra med det faktum att det finns celler som inte är tomma (data) eller inte i kalkylbladet.



Typen ColumnCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells/columncollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells/columncollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells/columncollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`get_by_index(self, index)`](/cells/python-net/sv/aspose.cells/columncollection/get_by_index/#int) | Hämtar kolumnobjektet via indexet.|
| [`get_column_by_index(self, index)`](/cells/python-net/sv/aspose.cells/columncollection/get_column_by_index/#int) | Hämtar objektet [`Column`](/cells/python-net/sv/aspose.cells/column) efter position i listan.|
| [`get(self, column_index)`](/cells/python-net/sv/aspose.cells/columncollection/get/#int) | Lägg till API for Python via .Net.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells/columncollection/binary_search/#aspose.cells.column) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Column`](/cells/python-net/sv/aspose.cells/column)
