---
title: get_array_mode_parameters metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters {#str}
Hämtar index för givna anpassade funktioners parametrar som behöver beräknas i arrayläge.


###  Returnerar

Index för parametrarna som behöver beräknas i arrayläge för given anpassad funktion.
Standard är null, det finns ingen parameter som behöver beräknas i arrayläge för den anpassade funktionen.


```python
def get_array_mode_parameters(self, function_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| function_name | str | Namn på den anpassade funktionen.|
###  Anmärkningar

För ett uttryck som behöver beräknas, ta A:A+B:B som ett exempel:
Generellt i värdeläge kommer det att beräknas till ett enda värde enligt aktuell cellbas.
Men i arrayläge kommer alla värden för A1+B1,A2+B2,A3+B3,... att beräknas och användas för beräkningen.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`CustomFunctionDefinition`](/cells/python-net/sv/aspose.cells/customfunctiondefinition)
