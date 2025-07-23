---
title: calc_stack_size fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size fastighet

Stackstorleken för att beräkna celler rekursivt. Standardvärdet är 200.

###  Anmärkningar

När det finns ett stort antal celler som behöver beräknas rekursivt i beroendeträdet,
StackOverflowException kan orsakas i beräkningsprocessen.
Om så är fallet bör användaren ange ett mindre värde för den här egenskapen.
I en sådan situation bör användaren bestämma rätt värde för denna egenskap enligt faktiska formler och data.
Emellertid kan ett för litet värde orsaka prestandaförsämring för formelberäkningen och ett värde under 2.
kommer att göra det omöjligt att beräkna formeln som är beroende av en annan. Så om det angivna värdet är mindre än 2,
den kommer att återställas till 2.
###  Definition:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions)
