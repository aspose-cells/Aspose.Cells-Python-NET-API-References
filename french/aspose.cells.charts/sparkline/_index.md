---
title: Sparkline classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 270
url: /fr/aspose.cells.charts/sparkline/
is_root: false
---
##  Sparkline classe
Un graphique sparkline représente un petit graphique ou un graphique dans une cellule de feuille de calcul qui fournit une représentation visuelle des données.



Le type Sparkline expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [data_range](/cells/python-net/fr/aspose.cells.charts/sparkline/data_range) | Représente la plage de données du graphique sparkline.|
| [row](/cells/python-net/fr/aspose.cells.charts/sparkline/row) | Obtient l'index de ligne du sparkline.|
| [column](/cells/python-net/fr/aspose.cells.charts/sparkline/column) | Obtient l'index de colonne du sparkline.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`to_image(self, file_name, options)`](/cells/python-net/fr/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Convertit un graphique sparkline en image.|
| [`to_image(self, stream, options)`](/cells/python-net/fr/aspose.cells.charts/sparkline/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Convertit un graphique sparkline en image.|



###  Exemple

```python
from aspose.cells import CellArea, Workbook
from aspose.cells.charts import SparklineType
from aspose.cells.rendering import ImageOrPrintOptions

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
idx = sheet.sparkline_groups.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
idx = group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
line = group.sparklines[idx]
print("Saprkline data range: "  + line.data_range + ", row: "  + str(line.row) + ", column: "  + str(line.column))
line.to_image("output.png", ImageOrPrintOptions())

```

###  Voir également
* module [`aspose.cells.charts`](..)
