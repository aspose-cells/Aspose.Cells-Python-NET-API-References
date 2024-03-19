---
title: get_param_value metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value {#int}
Hämtar det representerade värdeobjektet för parametern vid ett givet index.


###  Returnerar

Det beräknade värdet för parametern.


```python
def get_param_value(self, index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | Indexet för parametern(0 baserat)|
###  Anmärkningar

För en parameter:

Om det är ett vanligt värde, returnerar det självt.


Om det är referens, returnerar det ReferredArea-objektet;


Om den refererar till datauppsättning(ar) med flera värden, returnerar den en array av objekt;



Om det är någon form av uttryck som behöver beräknas så kommer det att beräknas i värdeläge
och i allmänhet kommer ett enda värde att returneras enligt aktuell cellbas. Till exempel,
om en parameter i D2:s formel är A:A+B:B, kommer A2+B2 att beräknas och returneras.
Men om denna parameter har angetts som arrayläge
(av [`Workbook.update_custom_function_definition`](/cells/python-net/sv/aspose.cells/workbook/update_custom_function_definition)
eller [`FormulaParseOptions.custom_function_definition`](/cells/python-net/sv/aspose.cells/formulaparseoptions#custom_function_definition)),
då kommer en array(objekt[][]) att returneras vars objekt är A1+B1,A2+B2,....


###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata)
