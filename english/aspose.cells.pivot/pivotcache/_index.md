---
title: PivotCache class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 60
url: /aspose.cells.pivot/pivotcache/
is_root: false
---

## PivotCache class

Represents the memory cache for some PivotTable reports.



The PivotCache type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [source_type](/cells/python-net/aspose.cells.pivot/pivotcache/source_type) | Gets the [`PivotTableSourceType`](/cells/python-net/aspose.cells.pivot/pivottablesourcetype). |


### Methods
| Method | Description |
| :- | :- |
| [`refresh(self, option)`](/cells/python-net/aspose.cells.pivot/pivotcache/refresh/#aspose.cells.pivot.pivottablerefreshoption) | Refreshes data from the data source and calculates data for the view of all pivottables which data source is this pivot cache. |
| [`refresh(self)`](/cells/python-net/aspose.cells.pivot/pivotcache/refresh/#) | Refreshes data from the data source and calculates data for the view of all pivottables which data source is this pivot cache. |
| [`get_pivot_tables(self)`](/cells/python-net/aspose.cells.pivot/pivotcache/get_pivot_tables/#) | Gets all pivot tables with this pivot cache. |



### Remarks 


All data will be gathered into this cache,and the pivot table only get data from this cache,not directly access data source.
If data source of some [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable)s are same, they will use a pivot cache.

### See Also
* module [`aspose.cells.pivot`](..)
* class [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable)
* class [`PivotTableSourceType`](/cells/python-net/aspose.cells.pivot/pivottablesourcetype)
