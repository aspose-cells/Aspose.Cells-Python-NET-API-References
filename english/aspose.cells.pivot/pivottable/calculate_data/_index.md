---
title: calculate_data method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---

## calculate_data(self) {#}

Calculates data of pivottable to cells.



```python

def calculate_data(self):
    ...
```


### Remarks

Cell.Value in the pivot range could not return the correct result if the method is not been called.
This method calculates data with an inner pivot cache,not original data source.
So if the data source is changed, please call RefreshData() method first.

## calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}

Calculates pivot table with options.



```python

def calculate_data(self, option):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| option | aspose.cells.pivot.PivotTableCalculateOption | The options for calculating the pivot table |
### Remarks

If PivotTableCalculateOption.RefreshData is true, 
this method will refresh pivot cache from data source,then calculate all pivot tables based same pivot cache.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable)
