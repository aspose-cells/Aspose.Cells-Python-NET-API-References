---
title: get_enumerator Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 100
url: /de/aspose.cells/range/get_enumerator/
is_root: false
---
##  get_enumerator {#}
Ruft den Enumerator für Zellen in diesem Bereich ab.


###  Kehrt zurück

Der Zellenenumerator


```python
def get_enumerator(self):
    ...
```


###  Bemerkungen

Beim Durchlaufen von Elementen durch den zurückgegebenen Enumerator die Zellsammlung
sollte nicht geändert werden (z. B. Vorgänge, die dazu führen, dass neue Cell/Zeilen instanziiert oder vorhandene Cell/Zeilen gelöscht werden).
Andernfalls kann der Enumerator möglicherweise nicht alle Zellen korrekt durchlaufen (einige Elemente werden möglicherweise wiederholt durchlaufen oder übersprungen).
###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook("template.xlsx")
cells = workbook.worksheets[0].cells
en = cells.create_range("B2:C3").get_enumerator()
for cell in en:
    print(cell.name + ": "  + str(cell.value))

```



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
