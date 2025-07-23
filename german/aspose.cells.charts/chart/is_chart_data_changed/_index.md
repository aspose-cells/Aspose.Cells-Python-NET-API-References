---
title: is_chart_data_changed Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
Erkennt, ob sich die Datenquelle eines Diagramms geändert hat.


###  Kehrt zurück

Gibt „true“ zurück, wenn sich das Diagramm geändert hat, andernfalls „false“


```python

def is_chart_data_changed(self):
    ...
```


###  Bemerkungen

Die Methode erkennt die Änderungen in der Datenquelle des Diagramms, bevor das Diagramm im Bildformat gerendert wird.
Beim ersten Aufruf von Chart.toImage werden die Quelldaten des Diagramms (z. B. XValuesParseData, ValuesParseData) aufgezeichnet.
Bevor Sie die Methode Chart.toImage erneut aufrufen, rufen Sie die Methode IsChartDataChanged auf, um zu prüfen, ob das Diagramm erneut gerendert werden muss.


###  Siehe auch
* Modul [`aspose.cells.charts`](../../)
* Klasse [`Chart`](/cells/python-net/de/aspose.cells.charts/chart)
