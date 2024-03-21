---
title: update_custom_function_definition metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 410
url: /sv/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition {#aspose.cells.CustomFunctionDefinition}
Uppdaterar definitionen av anpassade funktioner.



```python
def update_custom_function_definition(self, definition):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/sv/aspose.cells/customfunctiondefinition) |Särskild definition av anpassade funktioner för användarens speciella krav.|
###  Anmärkningar

Denna metod kan användas för vissa speciella scenarier. Till exempel om användaren behöver några parametrar
av vissa anpassade funktioner beräknas i array-läge, sedan kan användaren tillhandahålla sin egen definition med implementerad
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/sv/aspose.cells/customfunctiondefinition/get_array_mode_parameters) för dessa funktioner.
Efter att data för formler har uppdaterats kommer de angivna parametrarna att beräknas i arrayläge automatiskt
vid beräkning av motsvarande anpassade funktioner.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
