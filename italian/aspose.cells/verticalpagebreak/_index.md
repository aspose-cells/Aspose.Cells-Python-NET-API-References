---
title: VerticalPageBreak classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1540
url: /it/aspose.cells/verticalpagebreak/
is_root: false
---
##  VerticalPageBreak classe
Incapsula l'oggetto che rappresenta un'interruzione di pagina verticale.



Il tipo VerticalPageBreak espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [start_row](/cells/python-net/it/aspose.cells/verticalpagebreak/start_row) | Ottiene l'indice della riga iniziale dell'interruzione di pagina verticale.|
| [end_row](/cells/python-net/it/aspose.cells/verticalpagebreak/end_row) | Ottiene l'indice della riga finale dell'interruzione di pagina verticale.|
| [column](/cells/python-net/it/aspose.cells/verticalpagebreak/column) | Ottiene l'indice di colonna dell'interruzione di pagina verticale.|



###  Esempio

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
