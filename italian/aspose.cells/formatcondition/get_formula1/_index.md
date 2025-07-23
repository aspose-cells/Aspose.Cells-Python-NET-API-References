---
title: Metodo get_formula1
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/formatcondition/get_formula1/
is_root: false
---
##  get_formula1(self, is_r1c1, is_local) {#bool-bool}
Ottiene il valore o l'espressione associata a questa condizione di formato.


###  ritorna

Il valore o l'espressione associati a questa condizione di formato.


```python

def get_formula1(self, is_r1c1, is_local):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| is_r1c1 | bool | Se la formula deve essere formattata come R1C1.|
| is_local | bool | Se la formula deve essere formattata in base alle impostazioni locali.|


##  get_formula1(self, row, column) {#int-int}
Ottiene la formula della formattazione condizionale della cella.


###  ritorna

La formula.


```python

def get_formula1(self, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | Indice di riga.|
| column | int | L'indice della colonna.|


##  get_formula1(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
Ottiene il valore o l'espressione della formattazione condizionale della cella.


###  ritorna

Valore o espressione associata alla formattazione condizionale della cella.


```python

def get_formula1(self, is_r1c1, is_local, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| is_r1c1 | bool | Se la formula deve essere formattata come R1C1.|
| is_local | bool | Se la formula deve essere formattata in base alle impostazioni locali.|
| row | int | Indice di riga.|
| column | int | L'indice della colonna.|
###  Osservazioni

La cella specificata deve essere contenuta in questa formattazione condizionale, altrimenti verrà restituito null.


###  Guarda anche

* modulo [`aspose.cells`](../../)
* classe [`FormatCondition`](/cells/python-net/it/aspose.cells/formatcondition)
