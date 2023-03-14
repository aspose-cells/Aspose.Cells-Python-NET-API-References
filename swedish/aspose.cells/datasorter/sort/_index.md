---
title: sort metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/datasorter/sort/
is_root: false
---
##  sort() {#}
Sortera data i intervallet.


###  Returnerar

de ursprungliga indexen (absolut position, till exempel kolumn A är 0, B är 1, ...) för de sorterade raderna/kolumnerna.
Om inga rader/kolumner behöver flyttas med denna sorteringsoperation, kommer null att returneras.


```python
def sort(self):
    ...
```




##  sort(cells, area) {#Cells-CellArea}
Sortera data för området.


###  Returnerar

de ursprungliga indexen (absolut position, till exempel kolumn A är 0, B är 1, ...) för de sorterade raderna/kolumnerna.
Om inga rader/kolumner behöver flyttas med denna sorteringsoperation, kommer null att returneras.


```python
def sort(self, cells, area):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cells | [Cells](/cells/python-net/sv/aspose.cells/cells) | Cellerna innehåller dataområdet.|
| area | [CellArea](/cells/python-net/sv/aspose.cells/cellarea) | Området som behövs för att sortera|


##  sort(cells, start_row, start_column, end_row, end_column) {#Cells-int-int-int-int}
Sorterar data för området.


###  Returnerar

de ursprungliga indexen (absolut position, till exempel kolumn A är 0, B är 1, ...) för de sorterade raderna/kolumnerna.
Om inga rader/kolumner behöver flyttas med denna sorteringsoperation, kommer null att returneras.


```python
def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cells | [Cells](/cells/python-net/sv/aspose.cells/cells) | Cellerna innehåller dataområdet.|
| start_row | int | Startraden i området.|
| start_column | int | Startkolumnen för området.|
| end_row | int | Den sista raden av området.|
| end_column | int | Områdets ändkolumn.|



###  Se även
* modul [aspose.cells](../../)
* klass [DataSorter](/cells/python-net/sv/aspose.cells/datasorter)
