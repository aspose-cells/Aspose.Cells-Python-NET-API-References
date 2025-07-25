---
title: custom_function_definition proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells/formulaparseoptions/custom_function_definition/
is_root: false
---
##  custom_function_definition proprietà

Definizione per l'analisi delle funzioni personalizzate.

###  Osservazioni

Per alcuni requisiti speciali, come ad esempio quando si calcola una funzione personalizzata nel motore personalizzato dell'utente,
alcuni parametri devono essere calcolati in modalità array, utilizzando questa proprietà è possibile contrassegnare tali parametri
in modalità array durante l'analisi della formula. In caso contrario, l'utente deve aggiornare le funzioni personalizzate in un secondo momento
[`Workbook.update_custom_function_definition`](/cells/python-net/it/aspose.cells/workbook/update_custom_function_definition) per ottenere lo stesso risultato.
###  Definizione:
```python
@property
def custom_function_definition(self):
    ...
@custom_function_definition.setter
def custom_function_definition(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CustomFunctionDefinition`](/cells/python-net/it/aspose.cells/customfunctiondefinition)
* classe [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions)
