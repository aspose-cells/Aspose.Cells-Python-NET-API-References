﻿---
title: add method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/verticalpagebreakcollection/add/
is_root: false
---

## add(column) {#int}

Adds a vertical page break to the collection.


### Returns 


[VerticalPageBreak](/cells/python-net/aspose.cells/verticalpagebreak) object index.


```python
def add(self, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| column | int | Cell column index, zero based. |
### Remarks

Page break is added in the top left of the cell.
Please set a horizontal page break and a vertical page break concurrently.

## add(cell_name) {#str}

Adds a vertical page break to the collection.


### Returns 


[VerticalPageBreak](/cells/python-net/aspose.cells/verticalpagebreak) object index.


```python
def add(self, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cell_name | str | Cell name. |
### Remarks

Page break is added in the top left of the cell.
Please set a horizontal page break and a vertical page break concurrently.

## add(row, column) {#int-int}

Adds a vertical page break to the collection.


### Returns 


[VerticalPageBreak](/cells/python-net/aspose.cells/verticalpagebreak) object index.


```python
def add(self, row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| row | int | Cell row index, zero based. |
| column | int | Cell column index, zero based. |
### Remarks

Page break is added in the top left of the cell.
Please set a horizontal page break and a vertical page break concurrently.

## add(start_row, end_row, column) {#int-int-int}

Adds a vertical page break to the collection.


### Returns 


[VerticalPageBreak](/cells/python-net/aspose.cells/verticalpagebreak) object index.


```python
def add(self, start_row, end_row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| start_row | int | Start row index, zero based. |
| end_row | int | End row index, zero based. |
| column | int | Column index, zero based. |
### Remarks

This method is used to add a vertical pagebreak within a print area.


### See Also
* module [aspose.cells](../../)
* class [VerticalPageBreak](/cells/python-net/aspose.cells/verticalpagebreak)
* class [VerticalPageBreakCollection](/cells/python-net/aspose.cells/verticalpagebreakcollection)
