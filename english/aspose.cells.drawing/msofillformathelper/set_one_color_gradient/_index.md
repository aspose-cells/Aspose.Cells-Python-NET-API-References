﻿---
title: set_one_color_gradient method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.drawing/msofillformathelper/set_one_color_gradient/
is_root: false
---

## set_one_color_gradient {#aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}

Sets the specified fill to a one-color gradient.



```python
def set_one_color_gradient(self, color, degree, style, variant):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| color | aspose.pydrawing.Color | One gradient color. |
| degree | float | The gradient degree. Can be a value from 0.0 (dark) through 1.0 (light). |
| style | [`GradientStyleType`](/cells/python-net/aspose.cells.drawing/gradientstyletype) | Gradient shading style. |
| variant | int | The gradient variant. Can be a value from 1 through 4, corresponding to one of the four variants on the Gradient tab in the Fill Effects dialog box. If style is GradientStyle.FromCenter, the Variant argument can only be 1 or 2. |



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`MsoFillFormatHelper`](/cells/python-net/aspose.cells.drawing/msofillformathelper)
