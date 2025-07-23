---
title: Metodo update_custom_function_definition
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 430
url: /it/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition(self, definition) {#aspose.cells.CustomFunctionDefinition}
Aggiorna la definizione delle funzioni personalizzate.



```python

def update_custom_function_definition(self, definition):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/it/aspose.cells/customfunctiondefinition) | Definizione speciale di funzioni personalizzate in base alle esigenze specifiche dell'utente.|
###  Osservazioni

Questo metodo può essere utilizzato in alcuni scenari particolari. Ad esempio, se l'utente necessita di alcuni parametri.
di alcune funzioni personalizzate da calcolare in modalità array, quindi l'utente può fornire la propria definizione con implementata
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/it/aspose.cells/customfunctiondefinition/get_array_mode_parameters) per quelle funzioni.
Dopo l'aggiornamento dei dati delle formule, i parametri specificati verranno calcolati automaticamente in modalità array
durante il calcolo delle funzioni personalizzate corrispondenti.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
