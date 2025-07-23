---
title: get_precedents_in_calculation metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 190
url: /sv/aspose.cells/cell/get_precedents_in_calculation/
is_root: false
---
##  get_precedents_in_calculation(self) {#}
Hämtar alla prejudikat (referens till celler i den aktuella arbetsboken) som används av den här cellens formel vid beräkning.


###  Returnerar

Uppräknare för att räkna upp alla referenser (ReferredArea)


```python

def get_precedents_in_calculation(self):
    ...
```


###  Anmärkningar

Den här metoden fungerar bara i situationen att [`FormulaSettings.enable_calculation_chain`](/cells/python-net/sv/aspose.cells/formulasettings#enable_calculation_chain)
är sant för arbetsboken och arbetsboken har beräknats fullständigt.
Om den här cellen inte är en formel eller om den inte refererar till några andra celler returneras null.
###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("A2").get_precedents_in_calculation()
print("A2's calculation precedents:")
for r in en:
    print(r)

```



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
