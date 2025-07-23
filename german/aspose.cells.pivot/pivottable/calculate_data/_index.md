---
title: calculate_data Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
Berechnet die Daten der PivotTabelle in Zellen.



```python

def calculate_data(self):
    ...
```


###  Bemerkungen

Cell. Der Wert im Pivot-Bereich konnte nicht das richtige Ergebnis zurückgeben, wenn die Methode nicht aufgerufen wurde.
Diese Methode berechnet Daten mit einem inneren Pivot-Cache, nicht mit der ursprünglichen Datenquelle.
Wenn also die Datenquelle geändert wird, rufen Sie bitte zuerst die Methode RefreshData() auf.

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
Pivot-Tabellen mit Optionen berechnen



```python

def calculate_data(self, option):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/de/aspose.cells.pivot/pivottablecalculateoption) |  |



###  Siehe auch
* Modul [`aspose.cells.pivot`](../../)
* Klasse [`PivotTable`](/cells/python-net/de/aspose.cells.pivot/pivottable)
