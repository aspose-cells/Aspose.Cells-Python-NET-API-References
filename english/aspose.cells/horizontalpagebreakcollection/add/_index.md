﻿---
title: add method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/horizontalpagebreakcollection/add/
is_root: false
---

## add {#int}

Adds a horizontal page break to the collection.


### Returns 


[`HorizontalPageBreak`](/cells/python-net/aspose.cells/horizontalpagebreak) object index.


```python
def add(self, row):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| row | int | Cell row index, zero based. |
### Remarks

Page break is added in the top left of the cell.
Please set a horizontal page break and a vertical page break concurrently.

## add {#str}

Adds a horizontal page break to the collection.


### Returns 


[`HorizontalPageBreak`](/cells/python-net/aspose.cells/horizontalpagebreak) object index.


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

## add {#int-int}

Adds a horizontal page break to the collection.


### Returns 


[`HorizontalPageBreak`](/cells/python-net/aspose.cells/horizontalpagebreak) object index.


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

## add {#int-int-int}

Adds a horizontal page break to the collection.


### Returns 


[`HorizontalPageBreak`](/cells/python-net/aspose.cells/horizontalpagebreak) object index.


```python
def add(self, row, start_column, end_column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| row | int | Row index, zero based. |
| start_column | int | Start column index, zero based. |
| end_column | int | End column index, zero based. |
### Remarks

This method is used to add a horizontal pagebreak within a print area.


### See Also
* module [`aspose.cells`](../../)
* class [`HorizontalPageBreak`](/cells/python-net/aspose.cells/horizontalpagebreak)
* class [`HorizontalPageBreakCollection`](/cells/python-net/aspose.cells/horizontalpagebreakcollection)
