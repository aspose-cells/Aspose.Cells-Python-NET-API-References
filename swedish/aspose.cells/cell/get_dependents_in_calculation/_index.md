---
title: get_dependents_in_calculation metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 100
url: /sv/aspose.cells/cell/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, recursive) {#bool}
Hämtar alla celler vars beräknade resultat är beroende av denna cell.


###  Returnerar

Uppräknare för att räkna upp alla beroenden (Cell objekt)


```python

def get_dependents_in_calculation(self, recursive):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| recursive | bool | Om returnerar de beroenden som inte refererar direkt till den här cellen<br/> men hänvisning till andra blad i denna cell|
###  Anmärkningar

För att använda den här metoden, se till att arbetsboken har ställts in med sant värde för
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/sv/aspose.cells/formulasettings#enable_calculation_chain) och har beräknats fullständigt med denna inställning.
Om det inte finns någon formelreferens till den här cellen returneras null.
###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("B1").get_dependents_in_calculation(False)
print("B1's calculation dependents:")
for c in en:
    print(c.name)
en = cells.get("B2").get_dependents_in_calculation(False)
print("B2's calculation dependents:")
for c in en:
    print(c.name)

```



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
