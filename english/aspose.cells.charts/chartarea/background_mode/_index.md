---
title: background_mode property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.cells.charts/chartarea/background_mode/
is_root: false
---

## background_mode property


Gets and sets the display mode of the background.
This property is only valid in Excel 2003 or earlier versions.

### Remarks 


NOTE: This member is now obsolete. Instead, 
please use ChartFrame.Area.FillFormat.FillType property. For example,
If you need to set the BackgroundMode to Opaque, you can use the following code:
Area.FillFormat.FillType = FillType.Solid;
Area.FillFormat.SolidFill.Color = Color.Red;
This property will be removed 12 months later since February 2026.
Aspose apologizes for any inconvenience you may have experienced.
### Definition:
```python
@property
def background_mode(self):
    ...
@background_mode.setter
def background_mode(self, value):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`BackgroundMode`](/cells/python-net/aspose.cells.charts/backgroundmode)
* class [`ChartArea`](/cells/python-net/aspose.cells.charts/chartarea)
