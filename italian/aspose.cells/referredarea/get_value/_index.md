---
title: Metodo get_value
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/referredarea/get_value/
is_root: false
---
##  get_value(self, row_offset, col_offset) {#int-int}
Ottiene il valore della cella con l'offset specificato dall'angolo superiore sinistro di quest'area.


###  ritorna

"#RIF!" se quest'area non è valida;
"#N/A" se viene fornito un offset fuori da quest'area;
Altrimenti restituisce il valore della cella nella posizione specificata.


```python

def get_value(self, row_offset, col_offset):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row_offset | int | offset della riga dalla riga iniziale di quest'area|
| col_offset | int | offset della colonna dalla riga iniziale di quest'area|


##  get_value(self, row_offset, col_offset, calculate_formulas) {#int-int-bool}
Ottiene il valore della cella con l'offset specificato dall'angolo superiore sinistro di quest'area.


###  ritorna

"#RIF!" se quest'area non è valida;
"#N/A" se viene fornito un offset fuori da quest'area;
Altrimenti restituisce il valore della cella nella posizione specificata.


```python

def get_value(self, row_offset, col_offset, calculate_formulas):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row_offset | int | offset della riga dalla riga iniziale di quest'area|
| col_offset | int | offset della colonna dalla riga iniziale di quest'area|
| calculate_formulas | bool | Se calcolarlo ricorsivamente se il riferimento specificato è una formula|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`ReferredArea`](/cells/python-net/it/aspose.cells/referredarea)
