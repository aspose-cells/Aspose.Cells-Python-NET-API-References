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

This method only calculate data with the cached data in the [`PivotTable.pivot_cache`](/cells/python-net/aspose.cells.pivot/pivottable#pivot_cache).
So if you want to calcualte with latest data source, please use [`PivotCache.refresh`](/cells/python-net/aspose.cells.pivot/pivotcache/refresh) method to calculate.
If only the setting of pivot table is changed, [`PivotTable.calculate_data`](/cells/python-net/aspose.cells.pivot/pivottable/calculate_data) is enough.

## calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}

Calculates pivot table with options.


### Returns 


Returns all pivot tables which have been calculated.
If [`PivotTableCalculateOption.refresh_data`](/cells/python-net/aspose.cells.pivot/pivottablecalculateoption#refresh_data) is true,all pivot tables based on same pivot cache will be calculated together.


```python

def calculate_data(self, option):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| option | aspose.cells.pivot.PivotTableCalculateOption | The options for calculating the pivot table |
### Remarks

If [`PivotTableCalculateOption.refresh_data`](/cells/python-net/aspose.cells.pivot/pivottablecalculateoption#refresh_data) is true, 
this method will refresh pivot cache from data source,then calculate all pivot tables based same pivot cache.
Otherwise, only calculating with the cached data in the pivot cache.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable)
