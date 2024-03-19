---
title: ChartCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection Klasse
Kapselt eine Sammlung von [`Chart`](/cells/python-net/de/aspose.cells.charts/chart)-Objekten.



Der Typ ChartCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.charts/chartcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [add](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [add](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Fügt ein Diagramm mit voreingestellter Vorlage hinzu.|
| [add](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-bool-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [get](/cells/python-net/de/aspose.cells.charts/chartcollection/get/#int) | Fügen Sie API for Python über .Net. hinzu, da dieser [int index] nicht unterstützt wird|
| [get](/cells/python-net/de/aspose.cells.charts/chartcollection/get/#str) | Fügen Sie API for Python über .Net hinzu, da dieses [Zeichenfolgendiagramm] nicht unterstützt wird|
| [copy_to](/cells/python-net/de/aspose.cells.charts/chartcollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [add_floating_chart](/cells/python-net/de/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.ChartType-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [binary_search](/cells/python-net/de/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.Chart) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
* Klasse [`Chart`](/cells/python-net/de/aspose.cells.charts/chart)
