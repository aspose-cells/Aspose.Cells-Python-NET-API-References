---
title: pivot_source Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 430
url: /de/aspose.cells.charts/chart/pivot_source/
is_root: false
---
##  pivot_source Eigentum

Als Quelle dienen die Daten der PivotTable.
Wenn PivotSource nicht leer ist, ist das Diagramm ein PivotChart.

###  Bemerkungen

Wenn sich die Pivot-Tabelle „PivotTable1“ im Arbeitsblatt „Sheet1“ in der Datei „Book1.xls“ befindet.
Die PivotSource könnte „[Book1.xls]Sheet1!PivotTable1“ sein, wenn sich das Diagramm und die PivotTable nicht in derselben Arbeitsmappe befinden.
Wenn Sie diese Eigenschaft festlegen, geht die vorherige Datenquelleneinstellung verloren.
###  Definition:
```python
@property
def pivot_source(self):
    ...
@pivot_source.setter
def pivot_source(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.charts`](../../)
* Klasse [`Chart`](/cells/python-net/de/aspose.cells.charts/chart)
