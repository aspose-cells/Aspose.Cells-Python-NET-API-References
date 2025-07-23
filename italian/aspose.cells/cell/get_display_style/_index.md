---
title: Metodo get_display_style
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
Ottiene lo stile di visualizzazione di questa cella.


###  ritorna

stile di visualizzazione di questa cella


```python

def get_display_style(self):
    ...
```


###  Osservazioni

Lo stesso vale per l'utilizzo di [`BorderType.SIDE_BORDERS`](/cells/python-net/it/aspose.cells/bordertype#SIDE_BORDERS)
per [`Cell.get_display_style`](/cells/python-net/it/aspose.cells/cell/get_display_style).
Ciò significa che questo metodo controllerà e regolerà i bordi superiore/inferiore/sinistro/destro di questa cella
secondo lo stile ([`Cell.get_style`](/cells/python-net/it/aspose.cells/cell/get_style)) delle sue celle adiacenti,
ma non controllare le celle unite e non controllare lo stile di visualizzazione delle celle adiacenti.

##  get_display_style(self, include_merged_borders) {#bool}
Ottiene lo stile di visualizzazione di questa cella.


###  ritorna

stile di visualizzazione di questa cella


```python

def get_display_style(self, include_merged_borders):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| include_merged_borders | bool | Indica se controllare i bordi delle celle unite.|
###  Osservazioni

Se il flag specificato è falso, allora è lo stesso con [`Cell.get_display_style`](/cells/python-net/it/aspose.cells/cell/get_display_style).
Altrimenti è lo stesso con l'utilizzo
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
per [`Cell.get_display_style`](/cells/python-net/it/aspose.cells/cell/get_display_style).

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
Ottiene lo stile di visualizzazione di questa cella.


###  ritorna

stile di visualizzazione di questa cella


```python

def get_display_style(self, adjacent_borders):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/it/aspose.cells/bordertype) | Indica quali confini devono essere controllati e modificati<br/> in base ai confini delle celle adiacenti.|
###  Osservazioni

Se questa cella è interessata anche da altre impostazioni come la formattazione condizionale, gli oggetti elenco, ecc.,
lo stile di visualizzazione potrebbe essere diverso da [`Cell.get_style`](/cells/python-net/it/aspose.cells/cell/get_style).

Per le bandiere di regolazione dei bordi in base alle celle adiacenti,
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
indica se controllare e combinare i bordi inferiore/superiore/destro/sinistro di
le celle sinistra/destra/superiore/inferiore adiacenti a questa.

Per considerazioni sulle prestazioni e sulla compatibilità,
alcuni enum vengono utilizzati per indicare alcune operazioni speciali:

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
indica se controllare e combinare il bordo inferiore/destro delle celle unite con questa.

[`BorderType.DIAGONAL`](/cells/python-net/it/aspose.cells/bordertype#DIAGONAL) (ovvero, sia [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/it/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) che
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/it/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) sono stati impostati) indica il controllo e la combinazione dei bordi
dallo stile di visualizzazione delle celle adiacenti.

Si prega di notare che, controllando i bordi/stili delle celle adiacenti, in particolare gli stili di visualizzazione,
è un processo che richiede molto tempo. Se non è necessario ottenere i bordi per lo stile restituito,
utilizzando [`BorderType.NONE`](/cells/python-net/it/aspose.cells/bordertype#NONE) per disabilitare il processo delle celle adiacenti
fornirà prestazioni migliori.
Quando si ottengono i bordi delle celle adiacenti solo dagli stili definiti su quelle celle (senza impostare
[`BorderType.DIAGONAL`](/cells/python-net/it/aspose.cells/bordertype#DIAGONAL)), le prestazioni potrebbero anche essere migliori perché il controllo
anche lo stile di visualizzazione di una cella richiede molto tempo.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
