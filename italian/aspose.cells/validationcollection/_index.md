---
title: ValidationCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1530
url: /it/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection classe
Rappresenta la raccolta di convalida dei dati.



Il tipo ValidationCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/validationcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self)`](/cells/python-net/it/aspose.cells/validationcollection/add/#) | Aggiunge una convalida dei dati alla raccolta.|
| [`add(self, ca)`](/cells/python-net/it/aspose.cells/validationcollection/add/#aspose.cells.cellarea) | Aggiunge una convalida dei dati alla raccolta.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/validationcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/it/aspose.cells/validationcollection/remove_a_cell/#int-int) | Rimuove tutte le impostazioni di convalida sulla cella.|
| [`remove_area(self, ca)`](/cells/python-net/it/aspose.cells/validationcollection/remove_area/#aspose.cells.cellarea) | Rimuove tutte le impostazioni di convalida sull'intervallo.|
| [`get_validation_in_cell(self, row, column)`](/cells/python-net/it/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Ottiene la convalida applicata alla cella specificata.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/validationcollection/binary_search/#aspose.cells.validation) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



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
