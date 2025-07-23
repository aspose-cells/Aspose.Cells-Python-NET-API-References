---
title: CellArea Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells/cellarea/
is_root: false
---
##  CellArea Klasse
Stellt einen Bereich von Zellen dar.



Der Typ CellArea macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/cellarea/__init__/#) | Erstellt eine neue Instanz von CellArea|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [start_row](/cells/python-net/de/aspose.cells/cellarea/start_row) | Ruft die Startzeile dieses Bereichs ab oder legt sie fest.|
| [end_row](/cells/python-net/de/aspose.cells/cellarea/end_row) | Ruft die Endzeile dieses Bereichs ab oder legt sie fest.|
| [start_column](/cells/python-net/de/aspose.cells/cellarea/start_column) | Ruft die Startspalte dieses Bereichs ab oder legt sie fest.|
| [end_column](/cells/python-net/de/aspose.cells/cellarea/end_column) | Ruft die Endspalte dieses Bereichs ab oder legt sie fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`create_cell_area(, start_row, start_column, end_row, end_column)`](/cells/python-net/de/aspose.cells/cellarea/create_cell_area/#int-int-int-int) | Erstellt einen Zellenbereich.|
| [`create_cell_area(, start_cell_name, end_cell_name)`](/cells/python-net/de/aspose.cells/cellarea/create_cell_area/#str-str) | Erstellt einen Zellenbereich.|
| [`compare_to(self, obj)`](/cells/python-net/de/aspose.cells/cellarea/compare_to/#any) | Vergleichen Sie zwei CellArea-Objekte anhand ihrer oberen linken Ecke.|



###  Beispiel

```python
from aspose.cells import CellArea

# Create Cell Area
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0

```

###  Siehe auch
* Modul [`aspose.cells`](..)
