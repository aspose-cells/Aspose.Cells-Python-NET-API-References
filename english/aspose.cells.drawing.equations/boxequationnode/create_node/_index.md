---
title: create_node method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells.drawing.equations/boxequationnode/create_node/
is_root: false
---

## create_node {#aspose.cells.drawing.equations.EquationNodeType-aspose.cells.Workbook-aspose.cells.drawing.equations.EquationNode}

Create a node of the specified type.


### Returns 


If the specified type exists, the corresponding node is returned, and if the type does not exist, a node of unknown type is returned.


```python
def create_node(self, equation_type, workbook, parent):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| equation_type | [`EquationNodeType`](/cells/python-net/aspose.cells.drawing.equations/equationnodetype) | Types of Equation Nodes |
| workbook | [`Workbook`](/cells/python-net/aspose.cells/workbook) | The workbook object associated with the equation |
| parent | [`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode) | The parent node where this node is located |



### See Also
* module [`aspose.cells.drawing.equations`](../../)
* class [`BoxEquationNode`](/cells/python-net/aspose.cells.drawing.equations/boxequationnode)
