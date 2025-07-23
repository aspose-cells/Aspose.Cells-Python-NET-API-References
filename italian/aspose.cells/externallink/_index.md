---
title: ExternalLink classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 570
url: /it/aspose.cells/externallink/
is_root: false
---
##  ExternalLink classe
Rappresenta un collegamento esterno in una cartella di lavoro.



Il tipo ExternalLink espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [type](/cells/python-net/it/aspose.cells/externallink/type) | Ottiene il tipo di collegamento esterno.|
| [path_type](/cells/python-net/it/aspose.cells/externallink/path_type) | Ottieni il tipo di percorso di questo collegamento esterno|
| [original_data_source](/cells/python-net/it/aspose.cells/externallink/original_data_source) | Rappresenta la fonte dei dati memorizzati del collegamento esterno.|
| [data_source](/cells/python-net/it/aspose.cells/externallink/data_source) | Rappresenta la fonte dati del collegamento esterno.|
| [is_referred](/cells/python-net/it/aspose.cells/externallink/is_referred) | Indica se questo collegamento esterno è referenziato da altri.|
| [is_visible](/cells/python-net/it/aspose.cells/externallink/is_visible) | Indica se questo collegamento esterno è visibile in MS Excel.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add_external_name(self, text, refer_to)`](/cells/python-net/it/aspose.cells/externallink/add_external_name/#str-str) | Aggiunge un nome esterno.|



###  Esempio

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Get External Link
externalLink = workbook.worksheets.external_links[0]
# Change External Link's Data Source
externalLink.data_source = "d:\\link.xls"

```

###  Guarda anche
* modulo [`aspose.cells`](..)
