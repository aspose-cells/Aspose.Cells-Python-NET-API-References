---
title: is_param_array_mode_required fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required fastighet

Indikerar om denna motor behöver parametern för att beräknas i arrayläge. Standardvärdet är falskt.
Om [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/sv/aspose.cells/calculationdata/get_param_value_in_array_mode) krävs vid beräkning av custom
funktioner och användaren har inte uppdaterat definitionen för dem
(av [`Workbook.update_custom_function_definition`](/cells/python-net/sv/aspose.cells/workbook/update_custom_function_definition)),
den här egenskapen måste anges som sann.

###  Anmärkningar

Om denna anpassade beräkningsmotor kräver att parametern beräknas i arrayläge,
fler stackar kommer att krävas för att cachelagra trädet för parametrar
och metoden Calculate() kan anropas rekursivt för att beräkna parameterns värde.
För prestandaövervägande, vänligen behåll den här egenskapen som standardvärde (false)
om det inte finns några särskilda krav.
###  Definition:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`AbstractCalculationEngine`](/cells/python-net/sv/aspose.cells/abstractcalculationengine)
