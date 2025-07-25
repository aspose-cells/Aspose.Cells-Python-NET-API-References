---
title: Metodo sort
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 50
url: /it/aspose.cells/datasorter/sort/
is_root: false
---
##  sort(self) {#}
Ordina i dati nell'intervallo.


###  ritorna

gli indici originali (posizione assoluta, ad esempio, la colonna A è 0, B è 1, ...) delle righe/colonne ordinate.
Se questa operazione di ordinamento non richiede lo spostamento di alcuna riga/colonna, verrà restituito null.


```python

def sort(self):
    ...
```




##  sort(self, cells, area) {#aspose.cells.Cells-aspose.cells.CellArea}
Ordina i dati dell'area.


###  ritorna

gli indici originali (posizione assoluta, ad esempio, la colonna A è 0, B è 1, ...) delle righe/colonne ordinate.
Se questa operazione di ordinamento non richiede lo spostamento di alcuna riga/colonna, verrà restituito null.


```python

def sort(self, cells, area):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/it/aspose.cells/cells) | Le celle contengono l'area dati.|
| area | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | L'area necessaria per ordinare|


##  sort(self, cells, start_row, start_column, end_row, end_column) {#aspose.cells.Cells-int-int-int-int}
Ordina i dati dell'area.


###  ritorna

gli indici originali (posizione assoluta, ad esempio, la colonna A è 0, B è 1, ...) delle righe/colonne ordinate.
Se questa operazione di ordinamento non richiede lo spostamento di alcuna riga/colonna, verrà restituito null.


```python

def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/it/aspose.cells/cells) | Le celle contengono l'area dati.|
| start_row | int | La fila iniziale dell'area.|
| start_column | int | La colonna iniziale dell'area.|
| end_row | int | La fila finale dell'area.|
| end_column | int | La colonna finale dell'area.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`DataSorter`](/cells/python-net/it/aspose.cells/datasorter)
