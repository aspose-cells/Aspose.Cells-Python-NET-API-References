---
title: Metodo subtotal
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 910
url: /it/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
Crea totali parziali per l'intervallo.



```python
def subtotal(self, ca, group_by, function, total_list):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | La gamma|
| group_by | int | Il campo in base al quale raggruppare, come offset intero in base zero|
| function | [`ConsolidationFunction`](/cells/python-net/it/aspose.cells/consolidationfunction) | La funzione del totale parziale.|
| total_list | list | Una matrice di offset di campo in base zero, che indica i campi a cui vengono aggiunti i totali parziali.|


##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
Crea totali parziali per l'intervallo.



```python
def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | La gamma|
| group_by | int | Il campo in base al quale raggruppare, come offset intero in base zero|
| function | [`ConsolidationFunction`](/cells/python-net/it/aspose.cells/consolidationfunction) | La funzione del totale parziale.|
| total_list | list | Una matrice di offset di campo in base zero, che indica i campi a cui vengono aggiunti i totali parziali.|
| replace | bool | Indica se sostituire i totali parziali correnti|
| page_breaks | bool | Indica se aggiungere un'interruzione di pagina tra i gruppi|
| summary_below_data | bool | Indica se aggiungere un riepilogo sotto i dati.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
