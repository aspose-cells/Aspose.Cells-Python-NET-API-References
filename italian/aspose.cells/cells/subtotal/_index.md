---
title: Metodo subtotal
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 930
url: /it/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal(self, ca, group_by, function, total_list) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
Crea subtotali per l'intervallo.



```python

def subtotal(self, ca, group_by, function, total_list):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | La gamma|
| group_by | int | Il campo in base al quale effettuare il raggruppamento, come offset intero basato su zero|
| function | [`ConsolidationFunction`](/cells/python-net/it/aspose.cells/consolidationfunction) | La funzione di subtotale.|
| total_list | list |Una matrice di offset di campo basati su zero, che indicano i campi a cui vengono aggiunti i subtotali.|


##  subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
Crea subtotali per l'intervallo.



```python

def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | La gamma|
| group_by | int | Il campo in base al quale effettuare il raggruppamento, come offset intero basato su zero|
| function | [`ConsolidationFunction`](/cells/python-net/it/aspose.cells/consolidationfunction) | La funzione di subtotale.|
| total_list | list |Una matrice di offset di campo basati su zero, che indicano i campi a cui vengono aggiunti i subtotali.|
| replace | bool | Indica se sostituire i subtotali correnti|
| page_breaks | bool | Indica se aggiungere un'interruzione di pagina tra i gruppi|
| summary_below_data | bool | Indica se aggiungere un riepilogo sotto i dati.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
