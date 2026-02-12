---
title: add method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.charts/sparklinegroupcollection/add/
is_root: false
---

## add(self, type) {#aspose.cells.charts.SparklineType}

Adds an [`SparklineGroup`](/cells/python-net/aspose.cells.charts/sparklinegroup) with a [`Sparkline`](/cells/python-net/aspose.cells.charts/sparkline) to the collection.


### Returns 


[`SparklineGroup`](/cells/python-net/aspose.cells.charts/sparklinegroup) object index.


```python

def add(self, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | aspose.cells.charts.SparklineType | Specifies the type of the Sparkline group. |


## add(self, type, data_range, is_vertical, location_range) {#aspose.cells.charts.SparklineType-System.String-bool-aspose.cells.CellArea}

Adds an [`SparklineGroup`](/cells/python-net/aspose.cells.charts/sparklinegroup) with some [`Sparkline`](/cells/python-net/aspose.cells.charts/sparkline) to the collection.


### Returns 


[`SparklineGroup`](/cells/python-net/aspose.cells.charts/sparklinegroup) object index.


```python

def add(self, type, data_range, is_vertical, location_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | aspose.cells.charts.SparklineType | Specifies the type of the Sparkline group. |
| data_range | System.String | Specifies the data range of the sparkline group. |
| is_vertical | bool | Specifies whether to plot the sparklines from the data range by row or by column. |
| location_range | aspose.cells.CellArea | Specifies where the sparklines to be placed. |
### Remarks

This method will create sparklines too.
If `is_vertical` is true, the number of rows in dataRange and locationRange must be same.
If `is_vertical` is false, the number of columns in dataRange and locationRange must be same.


### See Also
* module [`aspose.cells.charts`](../../)
* class [`Sparkline`](/cells/python-net/aspose.cells.charts/sparkline)
* class [`SparklineGroup`](/cells/python-net/aspose.cells.charts/sparklinegroup)
* class [`SparklineGroupCollection`](/cells/python-net/aspose.cells.charts/sparklinegroupcollection)
