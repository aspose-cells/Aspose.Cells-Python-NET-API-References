---
title: refresh_data method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 280
url: /aspose.cells.pivot/pivottable/refresh_data/
is_root: false
---

## refresh_data(self) {#}

Refreshes data from it's data source to pivot cache.



```python

def refresh_data(self):
    ...
```


### Remarks

We will gather data from data source to a pivot cache ,then calculate the data in the cache to the cells.        
And it's better that you can simply call [`Workbook.refresh_all`](/cells/python-net/aspose.cells/workbook/refresh_all) to refresh and calculate all pivot tables in the file, not to refresh one by one.
NOTE: This method is now obsolete. Instead, 
please use [`PivotCache.refresh`](/cells/python-net/aspose.cells.pivot/pivotcache/refresh) method and remove followed [`PivotTable.calculate_data`](/cells/python-net/aspose.cells.pivot/pivottable/calculate_data) 
because this pivot table will be caclualted when refreshing [`PivotTable.pivot_cache`](/cells/python-net/aspose.cells.pivot/pivottable#pivot_cache).

This method will be removed 12 months later since June 2026. 
Aspose apologizes for any inconvenience you may have experienced.

## refresh_data(self, option) {#aspose.cells.pivot.PivotTableRefreshOption}

Refreshes pivottable's data and setting from it's data source with options.



```python

def refresh_data(self, option):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| option | aspose.cells.pivot.PivotTableRefreshOption | The options for refreshing data source of pivot table. |
### Remarks

We will gather data from data source to a pivot cache ,then calculate the data in the cache to the cells.        
And it's better that you can simply call [`Workbook.refresh_all`](/cells/python-net/aspose.cells/workbook/refresh_all) to refresh and calculate all pivot tables in the file, not to refresh one by one.
NOTE: This method is now obsolete. Instead, 
please use [`PivotCache.refresh`](/cells/python-net/aspose.cells.pivot/pivotcache/refresh) method and remove followed [`PivotTable.calculate_data`](/cells/python-net/aspose.cells.pivot/pivottable/calculate_data) 
because this pivot table will be caclualted when refreshing [`PivotTable.pivot_cache`](/cells/python-net/aspose.cells.pivot/pivottable#pivot_cache) 
This method will be removed 12 months later since June 2026. 
Aspose apologizes for any inconvenience you may have experienced.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotRefreshState`](/cells/python-net/aspose.cells.pivot/pivotrefreshstate)
* class [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable)
