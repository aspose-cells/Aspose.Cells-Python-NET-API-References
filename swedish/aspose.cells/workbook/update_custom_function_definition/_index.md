---
title: update_custom_function_definition metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 430
url: /sv/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition(self, definition) {#aspose.cells.CustomFunctionDefinition}
Uppdaterar definitionen av anpassade funktioner.



```python

def update_custom_function_definition(self, definition):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/sv/aspose.cells/customfunctiondefinition) | Särskild definition av anpassade funktioner för användarens speciella krav.|
###  Anmärkningar

Den här metoden kan användas för vissa speciella scenarier. Till exempel om användaren behöver vissa parametrar
av vissa anpassade funktioner som beräknas i arrayläge, kan användaren ange sin egen definition med implementerad
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/sv/aspose.cells/customfunctiondefinition/get_array_mode_parameters) för dessa funktioner.
Efter att formlernas data har uppdaterats kommer de angivna parametrarna att beräknas automatiskt i arrayläge.
vid beräkning av motsvarande anpassade funktioner.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
