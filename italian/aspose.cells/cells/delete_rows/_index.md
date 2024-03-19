---
title: Metodo delete_rows
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 260
url: /it/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows {#int-int}
Elimina più righe.



```python
def delete_rows(self, row_index, total_rows):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row_index | int | L'indice della prima riga da eliminare.|
| total_rows | int | Conteggio delle righe da eliminare.|
###  Osservazioni

Se l'intervallo eliminato contiene la parte superiore (non intera) della tabella (ListObject),
Non è stato possibile eliminare il ranged e non verrà fatto nulla.
Funziona allo stesso modo con MS Excel.

##  delete_rows {#int-int-bool}
Elimina più righe nel foglio di lavoro.


###  ritorna




```python
def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row_index | int | Indice della prima riga da eliminare.|
| total_rows | int | Conteggio delle righe da eliminare.|
| update_reference | bool | Indica se aggiornare i riferimenti in altri fogli di lavoro.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
