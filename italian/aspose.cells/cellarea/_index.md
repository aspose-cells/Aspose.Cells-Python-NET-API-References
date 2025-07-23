---
title: CellArea classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 120
url: /it/aspose.cells/cellarea/
is_root: false
---
##  CellArea classe
Rappresenta un'area di cellule.



Il tipo CellArea espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/cellarea/__init__/#) | Costruisce una nuova istanza di CellArea|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [start_row](/cells/python-net/it/aspose.cells/cellarea/start_row) | Ottiene o imposta la riga iniziale di quest'area.|
| [end_row](/cells/python-net/it/aspose.cells/cellarea/end_row) | Ottiene o imposta la riga finale di quest'area.|
| [start_column](/cells/python-net/it/aspose.cells/cellarea/start_column) | Ottiene o imposta la colonna iniziale di quest'area.|
| [end_column](/cells/python-net/it/aspose.cells/cellarea/end_column) | Ottiene o imposta la colonna finale di quest'area.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`create_cell_area(, start_row, start_column, end_row, end_column)`](/cells/python-net/it/aspose.cells/cellarea/create_cell_area/#int-int-int-int) | Crea un'area cella.|
| [`create_cell_area(, start_cell_name, end_cell_name)`](/cells/python-net/it/aspose.cells/cellarea/create_cell_area/#str-str) | Crea un'area cella.|
| [`compare_to(self, obj)`](/cells/python-net/it/aspose.cells/cellarea/compare_to/#any) | Confronta due oggetti CellArea in base al loro angolo in alto a sinistra.|



###  Esempio

```python
from aspose.cells import CellArea

# Create Cell Area
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0

```

###  Guarda anche
* modulo [`aspose.cells`](..)
