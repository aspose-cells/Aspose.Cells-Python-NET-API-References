---
title: Metodo add
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Aggiunge una condizione di formattazione e l'intervallo di celle interessate a FormatConditions
FormatConditions può contenere fino a tre formati condizionali.
I riferimenti ad altri fogli non sono consentiti nelle formule di formattazione condizionale.


###  ritorna

[0]:Condizione di formattazione dell'indice dell'oggetto;[1] Indice dell'intervallo di celle interessato.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) |Intervallo di celle formattato in modo condizionale.|
| type | [`FormatConditionType`](/cells/python-net/it/aspose.cells/formatconditiontype) | Tipo di formattazione condizionale. Potrebbe essere uno dei membri di FormatConditionType.|
| operator_type | [`OperatorType`](/cells/python-net/it/aspose.cells/operatortype) | Operatore di confronto. Potrebbe essere uno dei membri di OperatorType.|
| formula1 | str | Valore o espressione associati alla formattazione condizionale.|
| formula2 | str | Il valore o l'espressione associata alla formattazione condizionale|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FormatConditionCollection`](/cells/python-net/it/aspose.cells/formatconditioncollection)
