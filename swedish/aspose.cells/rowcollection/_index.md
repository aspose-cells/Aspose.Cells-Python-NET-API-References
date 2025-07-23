---
title: RowCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1240
url: /sv/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection klass
Samlar in [`Row`](/cells/python-net/sv/aspose.cells/row)-objekten som representerar de enskilda raderna i ett kalkylblad.



Typen RowCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [count](/cells/python-net/sv/aspose.cells/rowcollection/count) | Hämtar antalet rader i den här samlingen.|



Hämtar ett [`Row`](/cells/python-net/sv/aspose.cells/row)-objekt från givet radindex. Radobjektet för givet radindex kommer att instansieras om det inte existerar tidigare.
###  Indexerare
| Namn| Beskrivning|
| :- | :- |
| [index] |  |


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/sv/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Hämtar en uppräknare som itererar rader genom den här samlingen|
| [`get_row_by_index(self, index)`](/cells/python-net/sv/aspose.cells/rowcollection/get_row_by_index/#int) | Hämtar radobjektet efter positionen i listan.|
| [`clear(self)`](/cells/python-net/sv/aspose.cells/rowcollection/clear/#) | Rensa alla rader och celler.|
| [`remove_at(self, index)`](/cells/python-net/sv/aspose.cells/rowcollection/remove_at/#int) | Ta bort radobjektet vid det angivna indexet (positionen) i den här samlingen.|



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
