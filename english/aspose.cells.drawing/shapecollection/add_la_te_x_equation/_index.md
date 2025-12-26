---
title: add_la_te_x_equation method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 150
url: /aspose.cells.drawing/shapecollection/add_la_te_x_equation/
is_root: false
---

## add_la_te_x_equation(self, top_row, top, left_column, left, height, width, latex) {#int-int-int-int-int-int-System.String}

Adds an equation object to the worksheet using LaTeX format strings.


### Returns 





```python

def add_la_te_x_equation(self, top_row, top, left_column, left, height, width, latex):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | The top row index. |
| top | int | The vertical  offset its top row, in unit of pixel. |
| left_column | int | The left column index. |
| left | int | The horizontal offset from its left column, in unit of pixel. |
| height | int | The height of equation, in unit of pixel. |
| width | int | The width of equation, in unit of pixel. |
| latex | System.String | LaTeX format string |

### Example 


```python

#  LaTeX format string.
latex = "\\alpha +  \\frac{\\partial^2}{\\partial x_1\\partial x_2}y - \\left ( a + b \\right )+_{a}^{b}\\beta"
#  Adds an equation object to the worksheet.
textBox = shapes.add_la_te_x_equation(1, 0, 1, 0, 100, 300, latex)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ShapeCollection`](/cells/python-net/aspose.cells.drawing/shapecollection)
* class [`TextBox`](/cells/python-net/aspose.cells.drawing/textbox)
