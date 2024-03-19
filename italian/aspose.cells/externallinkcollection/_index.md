---
title: ExternalLinkCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 600
url: /it/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection classe
Rappresenta la raccolta di collegamenti esterni in una cartella di lavoro.



Il tipo ExternalLinkCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [count](/cells/python-net/it/aspose.cells/externallinkcollection/count) | Ottiene il numero di elementi effettivamente contenuti nella raccolta.|



Ottiene l'elemento [`ExternalLink`](/cells/python-net/it/aspose.cells/externallink) in corrispondenza dell'indice specificato.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] | L'indice in base zero dell'elemento.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add](/cells/python-net/it/aspose.cells/externallinkcollection/add/#str-list) | Aggiunge un collegamento esterno.|
| [add](/cells/python-net/it/aspose.cells/externallinkcollection/add/#aspose.cells.DirectoryType-str-list) | Aggiungi un collegamento esterno.|
| [clear](/cells/python-net/it/aspose.cells/externallinkcollection/clear/#) | Rimuove tutti i collegamenti esterni.|
| [clear](/cells/python-net/it/aspose.cells/externallinkcollection/clear/#bool) | Rimuove tutti i collegamenti esterni.|
| [remove_at](/cells/python-net/it/aspose.cells/externallinkcollection/remove_at/#int) | Rimuove il collegamento esterno specificato dalla cartella di lavoro.|
| [remove_at](/cells/python-net/it/aspose.cells/externallinkcollection/remove_at/#int-bool) | Rimuove il collegamento esterno specificato dalla cartella di lavoro.|



###  Esempio

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`ExternalLink`](/cells/python-net/it/aspose.cells/externallink)
