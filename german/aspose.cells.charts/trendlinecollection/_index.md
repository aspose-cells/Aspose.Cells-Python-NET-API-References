---
title: TrendlineCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 350
url: /de/aspose.cells.charts/trendlinecollection/
is_root: false
---
##  TrendlineCollection Klasse
Stellt eine Sammlung aller [`Trendline`](/cells/python-net/de/aspose.cells.charts/trendline)-Objekte für die angegebene Datenreihe dar.



Der Typ TrendlineCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.charts/trendlinecollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType) | Fügt dieser Sammlung ein [`Trendline`](/cells/python-net/de/aspose.cells.charts/trendline)-Objekt mit dem angegebenen Typ hinzu.|
| [add](/cells/python-net/de/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType-str) | Fügt dieser Sammlung ein [`Trendline`](/cells/python-net/de/aspose.cells.charts/trendline)-Objekt mit dem angegebenen Typ und Namen hinzu.|
| [copy_to](/cells/python-net/de/aspose.cells.charts/trendlinecollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [binary_search](/cells/python-net/de/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.Trendline) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
* Klasse [`Trendline`](/cells/python-net/de/aspose.cells.charts/trendline)
