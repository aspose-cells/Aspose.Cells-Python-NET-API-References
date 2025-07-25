---
title: HorizontalPageBreak classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 760
url: /it/aspose.cells/horizontalpagebreak/
is_root: false
---
##  HorizontalPageBreak classe
Incapsula l'oggetto che rappresenta un'interruzione di pagina orizzontale.



Il tipo HorizontalPageBreak espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [start_column](/cells/python-net/it/aspose.cells/horizontalpagebreak/start_column) | Ottiene l'indice della colonna iniziale di questa interruzione di pagina orizzontale.|
| [end_column](/cells/python-net/it/aspose.cells/horizontalpagebreak/end_column) | Ottiene l'indice della colonna finale di questa interruzione di pagina orizzontale.|
| [row](/cells/python-net/it/aspose.cells/horizontalpagebreak/row) |Ottiene l'indice di riga basato su zero.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Add a page break at cell Y30
Index = worksheet.horizontal_page_breaks.add("Y30")
# get the newly added horizontal page break
hPageBreak = worksheet.horizontal_page_breaks[Index]

```

###  Guarda anche
* modulo [`aspose.cells`](..)
