---
title: insert_image method
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 140
url: /aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---

## insert_image(self, uid, p, s, image_url) {#System.String-System.String-io.RawIOBase-System.String}

Inserts image in the worksheet from file stream or the URL,(either the file stream or the URL shall be provided)
or
Inserts shape ,when the p.type is one of AutoShapeType


### Returns 


The JSON format string of the inserted image


```python

def insert_image(self, uid, p, s, image_url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| uid | System.String | The unique id for the file cache |
| p | System.String | The JSON format string for the operation which specify the cell location  ,the worksheet name,upper left row,upper left column for the image，etc  {name:'sheet1',ri:1,ci:1} |
| s | io.RawIOBase | The file stream of the image file |
| image_url | System.String | The URL of the image file |



### See Also
* module [`aspose.cellsgridjs`](../../)
* class [`GridJsWorkbook`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook)
