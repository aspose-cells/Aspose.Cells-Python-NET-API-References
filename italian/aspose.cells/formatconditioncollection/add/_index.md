---
title: metodo add
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 20
url: /it/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(cell_area, type, operator_type, formula1, formula2) {#CellArea-FormatConditionType-OperatorType-str-str}
Aggiunge una condizione di formattazione e un numero di celle interessate a FormatConditions
FormatConditions può contenere fino a tre formati condizionali.
Nelle formule di formattazione condizionale non sono ammessi riferimenti agli altri fogli.


###  ritorna

[0]:Indice oggetto condizione di formattazione;[1] Indice intervallo cella interessata.


```python
def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_area | [CellArea](/cells/python-net/it/aspose.cells/cellarea) |Intervallo di celle formattato condizionale.|
| type | [FormatConditionType](/cells/python-net/it/aspose.cells/formatconditiontype) | Tipo di formattazione condizionale. Potrebbe essere uno dei membri di FormatConditionType.|
| operator_type | [OperatorType](/cells/python-net/it/aspose.cells/operatortype) | Operatore di confronto. Potrebbe essere uno dei membri di OperatorType.|
| formula1 | str | Il valore o l'espressione associata alla formattazione condizionale.|
| formula2 | str | Il valore o l'espressione associata alla formattazione condizionale|



###  Guarda anche
* modulo [aspose.cells](../../)
* classe [FormatConditionCollection](/cells/python-net/it/aspose.cells/formatconditioncollection)
