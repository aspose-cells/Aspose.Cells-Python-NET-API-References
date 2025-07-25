---
title: Metodo add_condition
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
Aggiungere una condizione di formato.


###  ritorna

Indice dell'oggetto delle condizioni di formattazione;


```python

def add_condition(self, type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/it/aspose.cells/formatconditiontype) | Tipo di condizione di formato.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Aggiunge una condizione di formattazione.


###  ritorna

Indice dell'oggetto delle condizioni di formattazione;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/it/aspose.cells/formatconditiontype) | Tipo di condizione di formato.|
| operator_type | [`OperatorType`](/cells/python-net/it/aspose.cells/operatortype) | Il tipo di operatore|
| formula1 | str | Valore o espressione associati alla formattazione condizionale.<br/>Se il valore di input inizia con '=', verrà interpretato come formula.<br/>Altrimenti verrà interpretato come un valore semplice (testo, numero, booleano).<br/> Per i valori di testo che iniziano con '=', l'utente può inserirli come formula nel formato: "=\"=...\"".|
| formula2 | str | Valore o espressione associati alla formattazione condizionale.<br/> Il formato di input è lo stesso di formula1|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FormatConditionCollection`](/cells/python-net/it/aspose.cells/formatconditioncollection)
