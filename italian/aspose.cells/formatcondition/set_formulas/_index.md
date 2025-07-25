---
title: Metodo set_formulas
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells/formatcondition/set_formulas/
is_root: false
---
##  set_formulas(self, formula1, formula2, is_r1c1, is_local) {#str-str-bool-bool}
Imposta il valore o l'espressione associata a questa condizione di formato.



```python

def set_formulas(self, formula1, formula2, is_r1c1, is_local):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula1 | str | Il valore o l'espressione associati a questa condizione di formato.<br/>Se il valore di input inizia con '=', verrà interpretato come formula. Altrimenti verrà interpretato come valore semplice (testo, numero, booleano).<br/> Per i valori di testo che iniziano con '=', l'utente può inserirli come formula nel formato: "=\"=...\"".|
| formula2 | str | Il valore o l'espressione associata a questa condizione di formato. Il formato di input è lo stesso di formula1.|
| is_r1c1 | bool | Se la formula è la formula R1C1.|
| is_local | bool | Se la formula è formattata in base alle impostazioni locali.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FormatCondition`](/cells/python-net/it/aspose.cells/formatcondition)
