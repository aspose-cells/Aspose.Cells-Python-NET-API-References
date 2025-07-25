---
title: Metodo add_areas
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/validation/add_areas/
is_root: false
---
##  add_areas(self, areas, check_intersection, check_edge) {#list-bool-bool}
Applica la convalida alle aree specificate.



```python

def add_areas(self, areas, check_intersection, check_edge):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| areas | list | Le aree.|
| check_intersection | bool | Controlla l'intersezione dell'area data con le aree di convalida esistenti.<br/>Se una convalida è stata applicata in una determinata area (o parte di essa),<br/>quindi la convalida esistente dovrebbe essere rimossa per prima cosa dall'area indicata.<br/>In caso contrario, le convalide generate potrebbero risultare corrotte.<br/>Se l'utente è sicuro che tutte le aree aggiunte non intersecano nessuna area esistente,<br/> questo parametro può essere impostato su falso per valutare le prestazioni.|
| check_edge | bool | Controllare il bordo delle aree di convalida applicate.<br/>Le impostazioni interne della convalida dipendono da quello in alto a sinistra dei suoi intervalli applicati,<br/>quindi se una delle aree date diventerà la nuova area in alto a sinistra degli intervalli applicati,<br/>le impostazioni interne devono essere modificate e ricostruite, altrimenti potrebbero verificarsi risultati imprevisti.<br/>Se l'utente è sicuro che nessuna di queste aree aggiunte sia in alto a sinistra,<br/> questo parametro può essere impostato su falso per valutare le prestazioni.|
###  Osservazioni

Con questo metodo rimuoveremo tutte le vecchie convalide nell'area specificata.
Per quello in alto a sinistra degli intervalli applicati dalla convalida, innanzitutto il suo StartRow è il più piccolo,
in secondo luogo la sua StartColumn è la più piccola tra quelle aree che hanno la stessa StartRow più piccola.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Validation`](/cells/python-net/it/aspose.cells/validation)
