---
title: refresh method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells.pivot/pivotcache/refresh/
is_root: false
---

## refresh(self) {#}

Refreshes data from the data source and calculates data for the view of all pivottables which data source is this pivot cache.



```python

def refresh(self):
    ...
```


### Remarks

If both table1 and table2 use this cache, the two table will calculated.
It's better that you can simply call [`Workbook.refresh_all`](/cells/python-net/aspose.cells/workbook/refresh_all) to refresh all pivot tables and charts in the file.

## refresh(self, option) {#aspose.cells.pivot.PivotTableRefreshOption}

Refreshes data from the data source and calculates data for the view of all pivottables which data source is this pivot cache.



```python

def refresh(self, option):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| option | aspose.cells.pivot.PivotTableRefreshOption | The options for refreshing data source of pivot table. |
### Remarks

It's better that you can simply call [`Workbook.refresh_all`](/cells/python-net/aspose.cells/workbook/refresh_all) to refresh all pivot tables and charts in the file.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotCache`](/cells/python-net/aspose.cells.pivot/pivotcache)
* class [`PivotRefreshState`](/cells/python-net/aspose.cells.pivot/pivotrefreshstate)
