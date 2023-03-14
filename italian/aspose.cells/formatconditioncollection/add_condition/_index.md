---
title: metodo add_condition
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 40
url: /it/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(type) {#FormatConditionType}
Aggiungi una condizione di formato.


###  ritorna

Indice oggetto condizione di formattazione;


```python
def add_condition(self, type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [FormatConditionType](/cells/python-net/it/aspose.cells/formatconditiontype) | Tipo di condizione del formato.|


##  add_condition(type, operator_type, formula1, formula2) {#FormatConditionType-OperatorType-str-str}
Aggiunge una condizione di formattazione.


###  ritorna

Indice oggetto condizione di formattazione;


```python
def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [FormatConditionType](/cells/python-net/it/aspose.cells/formatconditiontype) | [FormatConditionType](/cells/python-net/it/aspose.cells/formatconditiontype) di formattazione condizionale.<br/> Potrebbe essere uno dei membri di FormatConditionType.|
| operator_type | [OperatorType](/cells/python-net/it/aspose.cells/operatortype) | Il confronto [OperatorType](/cells/python-net/it/aspose.cells/operatortype).<br/> Potrebbe essere uno dei membri di OperatorType.|
| formula1 | str | Il valore o l'espressione associata alla formattazione condizionale.<br/>Se il valore di input inizia con '=', verrà preso come formula.<br/>Altrimenti verrà preso come semplice valore (testo, numero, bool).<br/> Per il valore di testo che inizia con '=', l'utente può inserirlo come formula nel formato: "=\"=...\"".|
| formula2 | str | Il valore o l'espressione associata alla formattazione condizionale.<br/>Il formato di input è lo stesso con formula1|



###  Guarda anche
* modulo [aspose.cells](../../)
* classe [FormatConditionCollection](/cells/python-net/it/aspose.cells/formatconditioncollection)
* classe [FormatConditionType](/cells/python-net/it/aspose.cells/formatconditiontype)
* classe [OperatorType](/cells/python-net/it/aspose.cells/operatortype)
