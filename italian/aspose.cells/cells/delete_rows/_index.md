---
title: Metodo delete_rows
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 260
url: /it/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
Elimina più righe.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row_index | int | Indice della prima riga da eliminare.|
| total_rows | int | Numero di righe da eliminare.|
###  Osservazioni

Se l'intervallo eliminato contiene la parte superiore (non l'intera) della tabella (ListObject),
l'intervallo non può essere eliminato e non verrà fatto nulla.
Funziona allo stesso modo con MS Excel.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
Elimina più righe nel foglio di lavoro.


###  ritorna




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row_index | int | Indice della prima riga da eliminare.|
| total_rows | int | Numero di righe da eliminare.|
| update_reference | bool | Indica se aggiornare i riferimenti in altri fogli di lavoro.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
Elimina più righe nel foglio di lavoro.


###  ritorna




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row_index | int | Indice della prima riga da eliminare.|
| total_rows | int | Numero di righe da eliminare.|
| options | [`DeleteOptions`](/cells/python-net/it/aspose.cells/deleteoptions) | Opzioni per l'operazione di eliminazione|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
