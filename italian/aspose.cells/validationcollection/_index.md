---
title: ValidationCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1620
url: /it/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection classe
Rappresenta la raccolta di convalida dei dati.



Il tipo ValidationCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/validationcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add](/cells/python-net/it/aspose.cells/validationcollection/add/#) | Aggiunge una convalida dei dati alla raccolta.|
| [add](/cells/python-net/it/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | Aggiunge una convalida dei dati alla raccolta.|
| [copy_to](/cells/python-net/it/aspose.cells/validationcollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [remove_a_cell](/cells/python-net/it/aspose.cells/validationcollection/remove_a_cell/#int-int) | Rimuove tutte le impostazioni di convalida sulla cella.|
| [remove_area](/cells/python-net/it/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | Rimuove tutte le impostazioni di convalida sull'intervallo.|
| [get_validation_in_cell](/cells/python-net/it/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Ottiene la convalida applicata alla cella specificata.|
| [binary_search](/cells/python-net/it/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



###  Esempio

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

###  Guarda anche
* modulo [`aspose.cells`](..)
