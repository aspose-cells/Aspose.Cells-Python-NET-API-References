---
title: Floor Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 170
url: /de/aspose.cells.charts/floor/
is_root: false
---
##  Floor Klasse
Kapselt das Objekt ein, das den Boden eines 3D-Diagramms darstellt.



**Nachlass:** [`Floor`](/cells/python-net/aspose.cells.charts/floor) → 
[`Area`](/cells/python-net/de/aspose.cells.drawing/area)



Der Typ Floor macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [background_color](/cells/python-net/de/aspose.cells.charts/floor/background_color) | Ruft die Hintergrundfarbe von [`Area`](/cells/python-net/de/aspose.cells.drawing/area) ab oder legt sie fest.|
| [foreground_color](/cells/python-net/de/aspose.cells.charts/floor/foreground_color) | Ruft die Vordergrundfarbe ab oder legt sie fest.|
| [formatting](/cells/python-net/de/aspose.cells.charts/floor/formatting) | Stellt die Formatierung des Bereichs dar.|
| [invert_if_negative](/cells/python-net/de/aspose.cells.charts/floor/invert_if_negative) | Wenn die Eigenschaft wahr ist und der Wert des Diagrammpunkts eine negative Zahl ist,<br/> Dabei werden Vordergrundfarbe und Hintergrundfarbe vertauscht.|
| [fill_format](/cells/python-net/de/aspose.cells.charts/floor/fill_format) | Stellt ein [`Area.fill_format`](/cells/python-net/de/aspose.cells.drawing/area#fill_format)-Objekt dar, das Füllformatierungseigenschaften für das angegebene Diagramm oder die angegebene Form enthält.|
| [transparency](/cells/python-net/de/aspose.cells.charts/floor/transparency) |Gibt den Transparenzgrad des Bereichs als Wert zwischen 0,0 (undurchsichtig) und 1,0 (durchsichtig) zurück oder legt ihn fest.|
| [border](/cells/python-net/de/aspose.cells.charts/floor/border) | Ruft die Grenze [`Line`](/cells/python-net/de/aspose.cells.drawing/line) ab oder legt sie fest.|



###  Beispiel

```python
from aspose.cells import License, Workbook
from aspose.cells.charts import ChartType
from aspose.cells.drawing import GradientPresetType, GradientStyleType
from aspose.pydrawing import Color

# Instantiate the License class
license = License()
# Pass only the name of the license file embedded in the assembly
license.set_license("Aspose.Cells.lic")
# Instantiate the workbook object
workbook = Workbook()
# Get cells collection
cells = workbook.worksheets[0].cells
# Put values in cells
cells.get("A1").put_value(1)
cells.get("A2").put_value(2)
cells.get("A3").put_value(3)
# get charts colletion
charts = workbook.worksheets[0].charts
# add a new chart
index = charts.add(ChartType.COLUMN_3D_STACKED, 5, 0, 15, 5)
# get the newly added chart
chart = charts[index]
# set charts nseries
chart.n_series.add("A1:A3", True)
# Show data labels
chart.n_series[0].data_labels.show_value = True
# Get chart's floor
floor = chart.floor
# set floor's border as red
floor.border.color = Color.red
# set fill format
floor.fill_format.set_preset_color_gradient(GradientPresetType.CALM_WATER, GradientStyleType.DIAGONAL_DOWN, 2)
# save the file
workbook.save(r"dest.xls")

```

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
* Klasse [`Area`](/cells/python-net/de/aspose.cells.drawing/area)
* Klasse [`Floor`](/cells/python-net/de/aspose.cells.charts/floor)
* Klasse [`Line`](/cells/python-net/de/aspose.cells.drawing/line)
