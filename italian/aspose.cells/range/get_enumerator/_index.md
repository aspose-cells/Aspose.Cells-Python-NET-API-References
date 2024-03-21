---
title: Metodo get_enumerator
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 100
url: /it/aspose.cells/range/get_enumerator/
is_root: false
---
##  get_enumerator {#}
Ottiene l'enumeratore per le celle in questo Range.


###  ritorna

L'enumeratore di celle


```python
def get_enumerator(self):
    ...
```


###  Osservazioni

Quando si attraversano gli elementi dall'enumeratore restituito, la raccolta di celle
non deve essere modificato (come le operazioni che causeranno la creazione di un'istanza del nuovo Cell/Riga o l'eliminazione dell'esistente Cell/Riga).
In caso contrario l'enumeratore potrebbe non essere in grado di attraversare correttamente tutte le celle (alcuni elementi potrebbero essere attraversati ripetutamente o ignorati).
###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook("template.xlsx")
cells = workbook.worksheets[0].cells
en = cells.create_range("B2:C3").get_enumerator()
for cell in en:
    print(cell.name + ": "  + str(cell.value))

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
