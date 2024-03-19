---
title: custom_function_definition fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/formulaparseoptions/custom_function_definition/
is_root: false
---
##  custom_function_definition fastighet

Definition för att analysera anpassade funktioner.

###  Anmärkningar

För vissa speciella krav, till exempel vid beräkning av anpassad funktion i användarens anpassade motor,
vissa parametrar av den måste beräknas i array-läge, med den här egenskapen kan dessa parametrar markeras
som matrisläge när formeln analyseras. Annars måste användaren uppdatera dessa anpassade funktioner senare
[`Workbook.update_custom_function_definition`](/cells/python-net/sv/aspose.cells/workbook/update_custom_function_definition) för att få samma resultat.
###  Definition:
```python
@property
def custom_function_definition(self):
    ...
@custom_function_definition.setter
def custom_function_definition(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`CustomFunctionDefinition`](/cells/python-net/sv/aspose.cells/customfunctiondefinition)
* klass [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions)
