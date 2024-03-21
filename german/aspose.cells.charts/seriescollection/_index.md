---
title: SeriesCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 250
url: /de/aspose.cells.charts/seriescollection/
is_root: false
---
##  SeriesCollection Klasse
Kapselt eine Sammlung von [`Series`](/cells/python-net/de/aspose.cells.charts/series)-Objekten.



Der Typ SeriesCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [category_data](/cells/python-net/de/aspose.cells.charts/seriescollection/category_data) | Ruft den Bereich der Kategorieachsenwerte ab oder legt diesen fest.<br/> Es kann sich um einen Bereich von Zellen handeln (z. B. „d1:e10“).<br/> oder eine Folge von Werten (z. B. „{2,6,8,10}“).|
| [second_category_data](/cells/python-net/de/aspose.cells.charts/seriescollection/second_category_data) | Ruft den Bereich der Achsenwerte der zweiten Kategorie ab oder legt diesen fest.<br/> Es kann sich um einen Bereich von Zellen handeln (z. B. „d1:e10“).<br/> oder eine Folge von Werten (z. B. „{2,6,8,10}“).<br/> Wirkt sich nur aus, wenn einige ASeries auf der zweiten Achse dargestellt werden.|
| [is_color_varied](/cells/python-net/de/aspose.cells.charts/seriescollection/is_color_varied) |Stellt dar, ob die Farbe der Punkte variiert wird.|
| [capacity](/cells/python-net/de/aspose.cells.charts/seriescollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells.charts/seriescollection/add/#str-bool) | Fügt die Sammlung [`Series`](/cells/python-net/de/aspose.cells.charts/series) einem Diagramm hinzu.|
| [add](/cells/python-net/de/aspose.cells.charts/seriescollection/add/#str-bool-bool) | Fügt die Sammlung [`Series`](/cells/python-net/de/aspose.cells.charts/series) einem Diagramm hinzu.|
| [copy_to](/cells/python-net/de/aspose.cells.charts/seriescollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [get_series_by_order](/cells/python-net/de/aspose.cells.charts/seriescollection/get_series_by_order/#int) | Ruft das Element [`Series`](/cells/python-net/de/aspose.cells.charts/series) per Bestellung ab.|
| [change_series_order](/cells/python-net/de/aspose.cells.charts/seriescollection/change_series_order/#int-int) | Ändert direkt die Reihenfolge der beiden Serien.|
| [set_series_names](/cells/python-net/de/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | Legt den Namen aller Serien im Diagramm fest.|
| [add_r1c1](/cells/python-net/de/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | Fügt die Sammlung [`Series`](/cells/python-net/de/aspose.cells.charts/series) einem Diagramm hinzu.|
| [binary_search](/cells/python-net/de/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.Series) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
* Klasse [`Series`](/cells/python-net/de/aspose.cells.charts/series)
