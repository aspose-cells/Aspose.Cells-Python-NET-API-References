---
title: SparklineGroup klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 290
url: /sv/aspose.cells.charts/sparklinegroup/
is_root: false
---
##  SparklineGroup klass
[`Sparkline`](/cells/python-net/sv/aspose.cells.charts/sparkline) är organiserad i en sparkline-grupp. En SparklineGroup innehåller ett variabelt antal sparkline-objekt.
En miniatyrdiagramgrupp anger typ, visningsinställningar och axelinställningar för miniatyrdiagrammen.



Typen SparklineGroup avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [preset_style](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/preset_style) | Hämtar och anger den förinställda stiltypen för miniatyrdiagramgruppen.|
| [sparkline_collection](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/sparkline_collection) | Hämtar samlingen av objektet [`Sparkline`](/cells/python-net/sv/aspose.cells.charts/sparkline).|
| [sparklines](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/sparklines) | Hämtar samlingen av objektet [`Sparkline`](/cells/python-net/sv/aspose.cells.charts/sparkline).|
| [type](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/type) | Anger sparkline-typen för sparkline-gruppen.|
| [plot_empty_cells_type](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/plot_empty_cells_type) | Anger hur man plottar tomma celler.|
| [display_hidden](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/display_hidden) | Anger om data ska visas i dolda rader och kolumner.|
| [show_high_point](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/show_high_point) | Anger om de högsta datapunkterna i miniatyrdiagramgruppen ska markeras.|
| [high_point_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/high_point_color) | Hämtar och anger färgen på de högsta datapunkterna i miniatyrdiagramgruppen.|
| [show_low_point](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/show_low_point) | Anger om de lägsta datapunkterna i miniatyrdiagramgruppen ska markeras.|
| [low_point_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/low_point_color) | Hämtar och anger färgen på de lägsta datapunkterna i miniatyrdiagramgruppen.|
| [show_negative_points](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/show_negative_points) |Anger om de negativa värdena i miniatyrbildsgruppen ska markeras med en annan färg eller markör.|
| [negative_points_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/negative_points_color) | Hämtar och anger färgen på de negativa värdena i miniatyrbildsgruppen.|
| [show_first_point](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/show_first_point) | Anger om den första datapunkten i miniatyrbildsgruppen ska markeras.|
| [first_point_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/first_point_color) | Hämtar och anger färgen på den första datapunkten i miniatyrbildsgruppen.|
| [show_last_point](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/show_last_point) | Anger om den sista datapunkten i miniatyrbildsgruppen ska markeras.|
| [last_point_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/last_point_color) | Hämtar och anger färgen på den sista datapunkten i miniatyrbildsgruppen.|
| [show_markers](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/show_markers) | Anger om varje punkt i varje linjesparkline i sparkline-gruppen ska markeras.|
| [markers_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/markers_color) | Hämtar och anger färgen på punkterna i varje linje-sparkline i sparkline-gruppen.|
| [series_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/series_color) | Hämtar och anger färgen på miniatyrdiagrammen i miniatyrdiagramgruppen.|
| [plot_right_to_left](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/plot_right_to_left) | Anger om plottdata är från höger till vänster.|
| [line_weight](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/line_weight) | Hämtar och anger linjetjockleken i varje linjesparkline i sparkline-gruppen, i enheten punkter.|
| [horizontal_axis_color](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/horizontal_axis_color) |Hämtar och anger färgen på den horisontella axeln i miniatyrbildsgruppen.|
| [show_horizontal_axis](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/show_horizontal_axis) | Anger om den horisontella axeln för miniatyrdiagrammet ska visas.<br/> Den horisontella axeln visas om miniatyrdiagrammet innehåller data som korsar nollaxeln.|
| [horizontal_axis_date_range](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/horizontal_axis_date_range) | Representerar det intervall som innehåller datumvärdena för sparkline-data.|
| [vertical_axis_max_value_type](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/vertical_axis_max_value_type) | Representerar den vertikala axelns maximala värdetyp.|
| [vertical_axis_max_value](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/vertical_axis_max_value) | Hämtar och ställer in det anpassade maxvärdet för den vertikala axeln.|
| [vertical_axis_min_value_type](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/vertical_axis_min_value_type) | Representerar den vertikala axelns minimivärdestyp.|
| [vertical_axis_min_value](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/vertical_axis_min_value) | Hämtar och ställer in det anpassade minimivärdet för den vertikala axeln.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`reset_ranges(self, data_range, is_vertical, location_range)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroup/reset_ranges/#str-bool-aspose.cells.cellarea) | Återställer dataintervallet och platsintervallet för sparkline-gruppen.<br/> Den här metoden rensar ursprungliga sparkline-objekt i gruppen och skapar nya sparkline-objekt för de nya områdena.|



###  Exempel

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_groups.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
#  Create CellsColor
clr = book.create_cells_color()
clr.color = Color.orange
group.series_color = clr
#  set the high points are colored green and the low points are colored red
group.show_high_point = True
group.show_low_point = True
group.high_point_color.color = Color.green
group.low_point_color.color = Color.red
#  set line weight
group.line_weight = 1.0
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Se även
* modul [`aspose.cells.charts`](..)
* klass [`Sparkline`](/cells/python-net/sv/aspose.cells.charts/sparkline)
