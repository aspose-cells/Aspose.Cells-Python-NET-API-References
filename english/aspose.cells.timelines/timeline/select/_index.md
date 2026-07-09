---
title: select method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells.timelines/timeline/select/
is_root: false
---

## select(self, start, end, calculate) {#System.DateTime-System.DateTime-bool}

Select item between the date time.



```python

def select(self, start, end, calculate):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| start | System.DateTime | The start date time |
| end | System.DateTime | The end date time |
| calculate | bool | Indicates whether to calculate relative pivot tables |
### Remarks

[`Timeline.current_level`](/cells/python-net/aspose.cells.timelines/timeline#current_level) must be set before calling this method.
If this method is called, [`Timeline.selection_level`](/cells/python-net/aspose.cells.timelines/timeline#selection_level) will be [`Timeline.current_level`](/cells/python-net/aspose.cells.timelines/timeline#current_level).


### See Also
* module [`aspose.cells.timelines`](../../)
* class [`Timeline`](/cells/python-net/aspose.cells.timelines/timeline)
