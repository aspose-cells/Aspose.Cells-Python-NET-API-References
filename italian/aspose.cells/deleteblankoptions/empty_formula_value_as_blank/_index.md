---
title: empty_formula_value_as_blank proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
##  empty_formula_value_as_blank proprietà

Se una cella verrà considerata vuota quando è in formula e il risultato calcolato è una stringa nulla o vuota.
Il valore predefinito è falso.

###  Osservazioni

In genere l'utente dovrebbe assicurarsi che le formule siano state calcolate prima di eliminare un'operazione con questa proprietà impostata su true.
Altrimenti tutte le formule appena create dalle API normali come [`Cell.formula`](/cells/python-net/it/aspose.cells/cell#formula) verranno considerate vuote e potranno essere eliminate
perché prima del calcolo i risultati calcolati sono tutti nulli.
###  Definizione:
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`DeleteBlankOptions`](/cells/python-net/it/aspose.cells/deleteblankoptions)
