---
title: ExternalLinkCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 580
url: /it/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection classe
Rappresenta una raccolta di collegamenti esterni in una cartella di lavoro.



Il tipo ExternalLinkCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [count](/cells/python-net/it/aspose.cells/externallinkcollection/count) | Ottiene il numero di elementi effettivamente contenuti nella raccolta.|



Ottiene l'elemento [`ExternalLink`](/cells/python-net/it/aspose.cells/externallink) all'indice specificato.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] | Indice basato su zero dell'elemento.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/it/aspose.cells/externallinkcollection/add/#str-list) | Aggiunge un collegamento esterno.|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/it/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) | Aggiungi un collegamento esterno.|
| [`clear(self)`](/cells/python-net/it/aspose.cells/externallinkcollection/clear/#) | Rimuove tutti i link esterni.|
| [`clear(self, update_references_as_local)`](/cells/python-net/it/aspose.cells/externallinkcollection/clear/#bool) | Rimuove tutti i link esterni.|
| [`remove_at(self, index)`](/cells/python-net/it/aspose.cells/externallinkcollection/remove_at/#int) | Rimuove il collegamento esterno specificato dalla cartella di lavoro.|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/it/aspose.cells/externallinkcollection/remove_at/#int-bool) | Rimuove il collegamento esterno specificato dalla cartella di lavoro.|



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
