---
title: RowCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1350
url: /sv/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection klass
Samlar de [`Row`](/cells/python-net/sv/aspose.cells/row)-objekt som representerar de enskilda raderna i ett kalkylblad.



Typen RowCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [count](/cells/python-net/sv/aspose.cells/rowcollection/count) | Hämtar antalet rader i den här samlingen.|



Hämtar ett [`Row`](/cells/python-net/sv/aspose.cells/row)-objekt efter givet radindex. Radobjektet för givet radindex kommer att instansieras om det inte finns tidigare.
###  Indexerare
| namn| Beskrivning|
| :- | :- |
| [index] |  |


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [get_enumerator](/cells/python-net/sv/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Får en uppräkning som itererar rader genom denna samling|
| [get_row_by_index](/cells/python-net/sv/aspose.cells/rowcollection/get_row_by_index/#int) | Hämtar radobjektet efter positionen i listan.|
| [clear](/cells/python-net/sv/aspose.cells/rowcollection/clear/#) | Rensa alla rader och celler.|
| [remove_at](/cells/python-net/sv/aspose.cells/rowcollection/remove_at/#int) | Ta bort radobjektet vid angivet index(position) i denna samling.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Row`](/cells/python-net/sv/aspose.cells/row)
