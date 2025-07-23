---
title: Metodo add_area
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
Applica la convalida all'area.



```python

def add_area(self, cell_area):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | La zona.|
###  Osservazioni

Equivale ad usare [`Validation.add_area`](/cells/python-net/it/aspose.cells/validation/add_area)
con controllo dell'intersezione e del bordo.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
Applica la convalida all'area.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | La zona.|
| check_intersection | bool | Controlla l'intersezione dell'area data con le aree di convalida esistenti.<br/>Se una convalida è stata applicata in una determinata area (o parte di essa),<br/>quindi la convalida esistente dovrebbe essere rimossa per prima cosa dall'area indicata.<br/>In caso contrario, le convalide generate potrebbero risultare corrotte.<br/>Se l'utente è sicuro che l'area aggiunta non interseca alcuna area esistente,<br/> questo parametro può essere impostato su falso per valutare le prestazioni.|
| check_edge | bool | Controllare il bordo delle aree di convalida applicate.<br/>Le impostazioni interne della convalida dipendono da quello in alto a sinistra dei suoi intervalli applicati,<br/>quindi se l'area data diventerà la nuova area in alto a sinistra degli intervalli applicati,<br/>le impostazioni interne devono essere modificate e ricostruite, altrimenti potrebbero verificarsi risultati imprevisti.<br/>Se l'utente è sicuro che l'area aggiunta non è quella in alto a sinistra,<br/> questo parametro può essere impostato su falso per valutare le prestazioni.|
###  Osservazioni

Con questo metodo rimuoveremo tutte le vecchie convalide nell'area specificata.
Per quello in alto a sinistra degli intervalli applicati dalla convalida, innanzitutto il suo StartRow è il più piccolo,
in secondo luogo la sua StartColumn è la più piccola tra quelle aree che hanno la stessa StartRow più piccola.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Validation`](/cells/python-net/it/aspose.cells/validation)
