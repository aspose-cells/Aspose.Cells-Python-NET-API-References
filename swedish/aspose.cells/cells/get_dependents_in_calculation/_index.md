---
title: get_dependents_in_calculation metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 400
url: /sv/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, row, column, recursive) {#int-int-bool}
Hämtar alla celler vars beräknade resultat beror på en specifik cell.


###  Returnerar

Uppräknare för att räkna upp alla beroenden (Cell objekt)


```python

def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | Radindex för den specifika cellen|
| column | int |Kolumnindex för den specifika cellen.|
| recursive | bool | Om returnerar de beroenden som inte direkt refererar till den specifika cellen<br/> men hänvisning till andra blad i den cellen.|
###  Anmärkningar

För att använda den här metoden, se till att arbetsboken har ställts in med sant värde för
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/sv/aspose.cells/formulasettings#enable_calculation_chain) och har beräknats fullständigt med denna inställning.
Om det inte finns någon formelreferens till den här cellen returneras null.
För mer information och exempel, se [`Cell.get_dependents_in_calculation`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation)


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
