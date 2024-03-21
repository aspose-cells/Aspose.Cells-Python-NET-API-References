---
title: is_param_array_mode_required proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 40
url: /it/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required proprietà

Indica se questo motore necessita che il parametro venga calcolato in modalità array. Il valore predefinito è falso.
Se [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/it/aspose.cells/calculationdata/get_param_value_in_array_mode) è richiesto nel calcolo personalizzato
funzioni e l'utente non ha aggiornato la loro definizione
(tramite [`Workbook.update_custom_function_definition`](/cells/python-net/it/aspose.cells/workbook/update_custom_function_definition)),
questa proprietà deve essere impostata come true.

###  Osservazioni

Se questo motore di calcolo personalizzato richiede che il parametro venga calcolato in modalità array,
saranno necessari più stack per memorizzare nella cache l'albero per i parametri
e il metodo Calculate() può essere chiamato ricorsivamente per calcolare il valore del parametro.
Per considerazioni sulle prestazioni, mantieni questa proprietà come valore predefinito (falso)
se non ci sono requisiti speciali.
###  Definizione:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`AbstractCalculationEngine`](/cells/python-net/it/aspose.cells/abstractcalculationengine)
