---
title: VbaModuleCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection classe
Rappresenta l'elenco di [`VbaModule`](/cells/python-net/it/aspose.cells.vba/vbamodule)



Il tipo VbaModuleCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | Aggiunge un modulo per un foglio di lavoro.|
| [`add(self, type, name)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | Aggiunge il modulo.|
| [`get(self, index)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/get/#int) | Ottiene [`VbaModule`](/cells/python-net/it/aspose.cells.vba/vbamodule) nell'elenco tramite l'indice.|
| [`get(self, name)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/get/#str) | Ottiene [`VbaModule`](/cells/python-net/it/aspose.cells.vba/vbamodule) nell'elenco in base al nome.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Rappresenta i dati del Designer.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Inserire il modulo utente nel progetto VBA.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | Rimuove il modulo per un foglio di lavoro.|
| [`remove_by_name(self, name)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Rimuovi il modulo dal nome|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Guarda anche
* modulo [`aspose.cells.vba`](..)
* classe [`VbaModule`](/cells/python-net/it/aspose.cells.vba/vbamodule)
