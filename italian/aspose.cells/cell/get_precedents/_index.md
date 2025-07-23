---
title: Metodo get_precedents
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 180
url: /it/aspose.cells/cell/get_precedents/
is_root: false
---
##  get_precedents(self) {#}
Ottiene tutti i riferimenti presenti nella formula di questa cella.


###  ritorna

Raccolta di tutti i riferimenti presenti nella formula di questa cella.


```python

def get_precedents(self):
    ...
```


###  Osservazioni

* Restituisce null se questa non è una cella formula. Tutti i riferimenti che compaiono nella formula di questa cella verranno restituiti indipendentemente dal fatto che siano referenziati o meno durante il calcolo.

Ad esempio, sebbene la cella A2 nella formula "=SE(VERO;A1;A2)" non venga utilizzata durante il calcolo,
viene comunque preso come precedente della formula. Per ottenere i riferimenti che influiscono solo sul calcolo, utilizzare [`Cell.get_precedents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_precedents_in_calculation).

* Restituisce null se questa non è una cella formula. Tutti i riferimenti che compaiono nella formula di questa cella verranno restituiti indipendentemente dal fatto che siano referenziati o meno durante il calcolo.
Ad esempio, sebbene la cella A2 nella formula "=SE(VERO;A1;A2)" non venga utilizzata durante il calcolo,
viene comunque preso come precedente della formula. Per ottenere i riferimenti che influiscono solo sul calcolo, utilizzare [`Cell.get_precedents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_precedents_in_calculation).

* Restituisce null se questa non è una cella formula. Tutti i riferimenti che compaiono nella formula di questa cella verranno restituiti indipendentemente dal fatto che siano referenziati o meno durante il calcolo.
Ad esempio, sebbene la cella A2 nella formula "=SE(VERO;A1;A2)" non venga utilizzata durante il calcolo,
viene comunque preso come precedente della formula. Per ottenere i riferimenti che influiscono solo sul calcolo, utilizzare [`Cell.get_precedents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_precedents_in_calculation).
###  Esempio

```python
from aspose.cells import CellsHelper, Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!A1"
areas = cells.get("A1").get_precedents()
for i in range(len(areas)):
    area = areas[i]
    stringBuilder = []
    if area.is_external_link:
        stringBuilder.append("[")
        stringBuilder.append(area.external_file_name)
        stringBuilder.append("]")
    stringBuilder.append(area.sheet_name)
    stringBuilder.append("!")
    stringBuilder.append(CellsHelper.cell_index_to_name(area.start_row, area.start_column))
    if area.is_area:
        stringBuilder.append(":")
        stringBuilder.append(CellsHelper.cell_index_to_name(area.end_row, area.end_column))
    print("".join(stringBuilder))

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
