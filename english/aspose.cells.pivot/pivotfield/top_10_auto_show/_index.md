---
title: top_10_auto_show method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 290
url: /aspose.cells.pivot/pivotfield/top_10_auto_show/
is_root: false
---

## top_10_auto_show(self, is_auto_show, is_top, count, rank_by) {#bool-bool-int-int}

Configures Top10 AutoShow settings for this pivot field.



```python

def top_10_auto_show(self, is_auto_show, is_top, count, rank_by):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| is_auto_show | bool | true to enable AutoShow; false to disable. |
| is_top | bool | If true, shows top items; false shows bottom items. |
| count | int | Number of top/bottom items to display. |
| rank_by | int | Index of data field used for ranking. Use -1 to rank by pivot item's own values. |
### Remarks

This method configures the [`PivotFieldTop10AutoShowSettings`](/cells/python-net/aspose.cells.pivot/pivotfieldtop10autoshowsettings).


XLS binary format: AutoShow (Top10) is the native and only supported option.


XLSX (OpenXML): The underlying file format supports Top10 AutoShow, but Excel 2007 and later user interface only exposes this via Top10 filter.
If XLS compatibility is not required, it is recommended to use Top10 filter instead.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
* class [`PivotFieldTop10AutoShowSettings`](/cells/python-net/aspose.cells.pivot/pivotfieldtop10autoshowsettings)
