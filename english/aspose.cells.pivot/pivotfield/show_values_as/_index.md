---
title: show_values_as method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 160
url: /aspose.cells.pivot/pivotfield/show_values_as/
is_root: false
---

## show_values_as {#aspose.cells.pivot.PivotFieldDataDisplayFormat-int-aspose.cells.pivot.PivotItemPositionType-int}

Show value of data field as different display format when the ShowDataAs calculation is in use.



```python
def show_values_as(self, display_format, base_field, base_item_position_type, base_item):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| display_format | [`PivotFieldDataDisplayFormat`](/cells/python-net/aspose.cells.pivot/pivotfielddatadisplayformat) | The data display format type. |
| base_field | int | The index to the field which ShowDataAs calculation bases on. |
| base_item_position_type | [`PivotItemPositionType`](/cells/python-net/aspose.cells.pivot/pivotitempositiontype) | The position type of base iteam. |
| base_item | int | The index to the base item which ShowDataAs calculation bases on.<br/>Only works when baseItemPositionType is custom. |
### Remarks

Only for data field.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
