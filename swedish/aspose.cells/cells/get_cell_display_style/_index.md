---
title: get_cell_display_style metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 320
url: /sv/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
Hämta visningsstilen för en given cell.


###  Returnerar

visningsstilen för den givna cellen.


```python

def get_cell_display_style(self, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | radindex för given cell|
| column | int | kolumnen i den givna cellen|
###  Anmärkningar

Samma sak med [`Cell.get_display_style`](/cells/python-net/sv/aspose.cells/cell/get_display_style),
och samma sak med att använda [`BorderType.SIDE_BORDERS`](/cells/python-net/sv/aspose.cells/bordertype#SIDE_BORDERS)
för [`Cells.get_cell_display_style`](/cells/python-net/sv/aspose.cells/cells/get_cell_display_style).

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
Hämta visningsstilen för en given cell.


###  Returnerar

visningsstilen för den givna cellen.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | radindex för given cell|
| column | int | kolumnen i den givna cellen|
| adjacent_borders | [`BorderType`](/cells/python-net/sv/aspose.cells/bordertype) | Anger vilka ramar som behöver kontrolleras och justeras i enlighet med ramarna för intilliggande celler.<br/>Se beskrivningen för samma parameter som<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  Anmärkningar

Om cellen också påverkas av andra inställningar, såsom villkorsstyrd formatering, listobjekt etc.
då kan visningsstilen skilja sig från [`Cells.get_cell_style`](/cells/python-net/sv/aspose.cells/cells/get_cell_style).
Och eftersom dessa inställningar även kan tillämpas på tomma (icke-existerande) celler,
med hjälp av den här metoden kan man undvika att dessa tomma celler instansieras
så prestandan blir bättre än att hämta Cell-instansen från Cells
och sedan ringa [`Cell.get_display_style`](/cells/python-net/sv/aspose.cells/cell/get_display_style).


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
