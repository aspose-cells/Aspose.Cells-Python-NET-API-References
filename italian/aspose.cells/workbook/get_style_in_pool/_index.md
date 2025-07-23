---
title: Metodo get_style_in_pool
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 200
url: /it/aspose.cells/workbook/get_style_in_pool/
is_root: false
---
##  get_style_in_pool(self, index) {#int}
Ottiene lo stile nel pool di stile.
Tutti gli stili presenti nella cartella di lavoro verranno raccolti in un pool.
Nelle celle è presente solo un semplice indice di riferimento.


###  ritorna

Lo stile nel pool corrisponde all'indice dato e può essere nullo.


```python

def get_style_in_pool(self, index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| index | int | L'indice.|
###  Osservazioni

Se si modifica lo stile restituito, verrà modificato anche lo stile di tutte le celle che fanno riferimento a questo stile.


###  Guarda anche

* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
