---
title: get_precedents_in_calculation Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 190
url: /de/aspose.cells/cell/get_precedents_in_calculation/
is_root: false
---
##  get_precedents_in_calculation(self) {#}
Ruft alle Präzedenzfälle (Verweise auf Zellen in der aktuellen Arbeitsmappe) ab, die von der Formel dieser Zelle während der Berechnung verwendet werden.


###  Kehrt zurück

Enumerator zum Aufzählen aller Referenzen (ReferredArea)


```python

def get_precedents_in_calculation(self):
    ...
```


###  Bemerkungen

Diese Methode funktioniert nur in der Situation, dass [`FormulaSettings.enable_calculation_chain`](/cells/python-net/de/aspose.cells/formulasettings#enable_calculation_chain)
ist für die Arbeitsmappe wahr und die Arbeitsmappe wurde vollständig berechnet.
Wenn diese Zelle keine Formel ist oder nicht auf andere Zellen verweist, wird null zurückgegeben.
###  Beispiel

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



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
