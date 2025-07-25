---
title: calculate_data metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
Beräknar pivottabellens data till celler.



```python

def calculate_data(self):
    ...
```


###  Anmärkningar

Cell. Värdet i pivotområdet kunde inte returnera korrekt resultat om metoden inte anropades.
Den här metoden beräknar data med en inre pivot-cache, inte den ursprungliga datakällan.
Så om datakällan ändras, anropa först metoden RefreshData().

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
Beräkna pivottabeller med alternativ



```python

def calculate_data(self, option):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/sv/aspose.cells.pivot/pivottablecalculateoption) |  |



###  Se även
* modul [`aspose.cells.pivot`](../../)
* klass [`PivotTable`](/cells/python-net/sv/aspose.cells.pivot/pivottable)
