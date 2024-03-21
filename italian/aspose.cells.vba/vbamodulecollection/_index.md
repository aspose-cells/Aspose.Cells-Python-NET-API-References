---
title: VbaModuleCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 20
url: /it/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection classe
Rappresenta l'elenco dello [`VbaModule`](/cells/python-net/it/aspose.cells.vba/vbamodule)



Il tipo VbaModuleCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.Worksheet) | Aggiunge un modulo per un foglio di lavoro.|
| [add](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.VbaModuleType-str) | Aggiunge modulo.|
| [copy_to](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [add_designer_storage](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [get_designer_storage](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Rappresenta i dati del Designer.|
| [add_user_form](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Inserisci il modulo utente nel progetto VBA.|
| [binary_search](/cells/python-net/it/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.VbaModule) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



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
