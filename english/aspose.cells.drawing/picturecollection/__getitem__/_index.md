---
title: PictureCollection indexer
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells.drawing/picturecollection/__getitem__/
is_root: false
---

## PictureCollection indexer


Gets the [`Picture`](/cells/python-net/aspose.cells.drawing/picture) element at the specified index.
### Indexer
| Name | Description |
| :- | :- |
| index | The zero based index of the element. |



### Returns 


The element at the specified index.

### Example 


```python

# get picture collection
# PictureCollection pictures = workbook.Worksheets[0].Pictures;
# add a picture
index = pictures.add(1, 1, "image.png")
# get the picture
pic = pictures[index]

```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`Picture`](/cells/python-net/aspose.cells.drawing/picture)
* class [`PictureCollection`](/cells/python-net/aspose.cells.drawing/picturecollection)
