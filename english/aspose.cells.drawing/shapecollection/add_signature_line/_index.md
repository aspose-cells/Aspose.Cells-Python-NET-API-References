---
title: add_signature_line method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 320
url: /aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---

## add_signature_line(self, top_row, left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}

Adds a Signature Line to the worksheet.


### Returns 





```python

def add_signature_line(self, top_row, left_column, signature_line):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| signature_line | aspose.cells.drawing.SignatureLine | Represents a signature line object. |

### Example 


```python
from aspose.cells.drawing import SignatureLine

wSignatureLine = SignatureLine()
wSignatureLine.allow_comments = True
wSignatureLine.email = "example@example.com"
wSignatureLine.instructions = "Sign to confirm the excel content."
wSignatureLine.is_line = True
wSignatureLine.show_signed_date = True
wSignatureLine.signer = "User"
wSignatureLine.title = "tester"
# wSignatureLine.SignatureLineType = SignatureType.Stamp;
signatureLine1 = shapes.add_signature_line(0, 0, wSignatureLine)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`Picture`](/cells/python-net/aspose.cells.drawing/picture)
* class [`ShapeCollection`](/cells/python-net/aspose.cells.drawing/shapecollection)
