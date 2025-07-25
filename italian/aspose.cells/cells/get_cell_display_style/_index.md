---
title: Metodo get_cell_display_style
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 320
url: /it/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
Ottieni lo stile di visualizzazione della cella specificata.


###  ritorna

lo stile di visualizzazione della cella specificata.


```python

def get_cell_display_style(self, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | indice di riga della cella specificata|
| column | int | colonna della cella data|
###  Osservazioni

Lo stesso con [`Cell.get_display_style`](/cells/python-net/it/aspose.cells/cell/get_display_style),
e lo stesso vale per l'utilizzo di [`BorderType.SIDE_BORDERS`](/cells/python-net/it/aspose.cells/bordertype#SIDE_BORDERS)
per [`Cells.get_cell_display_style`](/cells/python-net/it/aspose.cells/cells/get_cell_display_style).

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
Ottieni lo stile di visualizzazione della cella specificata.


###  ritorna

lo stile di visualizzazione della cella specificata.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | indice di riga della cella specificata|
| column | int | colonna della cella data|
| adjacent_borders | [`BorderType`](/cells/python-net/it/aspose.cells/bordertype) | Indica quali bordi devono essere controllati e modificati in base ai bordi delle celle adiacenti.<br/>Si prega di vedere la descrizione per lo stesso parametro di<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  Osservazioni

Se la cella è interessata anche da altre impostazioni come la formattazione condizionale, gli oggetti elenco, ecc.,
lo stile di visualizzazione potrebbe essere diverso da [`Cells.get_cell_style`](/cells/python-net/it/aspose.cells/cells/get_cell_style).
E poiché tali impostazioni possono essere applicate anche a celle vuote (non esistenti),
utilizzando questo metodo è possibile evitare l'istanziazione di quelle celle vuote
quindi le prestazioni saranno migliori rispetto all'ottenimento dell'istanza Cell da Cells
e poi chiamando lo [`Cell.get_display_style`](/cells/python-net/it/aspose.cells/cell/get_display_style).


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
