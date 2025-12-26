---
title: add method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.drawing/picturecollection/add/
is_root: false
---

## add(self, top_row, left_column, stream) {#int-int-io.RawIOBase}

Adds a picture to the collection.


### Returns 


[`Picture`](/cells/python-net/aspose.cells.drawing/picture) object index.


```python

def add(self, top_row, left_column, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| stream | io.RawIOBase | Stream object which contains the image data. |

### Example 


```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


## add(self, top_row, left_column, file_name) {#int-int-System.String}

Adds a picture to the collection.


### Returns 


[`Picture`](/cells/python-net/aspose.cells.drawing/picture) object index.


```python

def add(self, top_row, left_column, file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| file_name | System.String | Image filename. |

### Example 


```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


## add(self, top_row, left_column, bottom_row, right_column, stream) {#int-int-int-int-io.RawIOBase}

Adds a picture to the collection.


### Returns 


[`Picture`](/cells/python-net/aspose.cells.drawing/picture) object index.


```python

def add(self, top_row, left_column, bottom_row, right_column, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| bottom_row | int | Lower right row index |
| right_column | int | Lower right column index |
| stream | io.RawIOBase | Stream object which contains the image data. |

### Example 


```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, 5, 5, fs)

```


## add(self, top_row, left_column, bottom_row, right_column, file_name) {#int-int-int-int-System.String}

Adds a picture to the collection.


### Returns 


[`Picture`](/cells/python-net/aspose.cells.drawing/picture) object index.


```python

def add(self, top_row, left_column, bottom_row, right_column, file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| bottom_row | int | Lower right row index |
| right_column | int | Lower right column index |
| file_name | System.String | Image filename. |

### Example 


```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


## add(self, top_row, left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}

Adds a picture to the collection.


### Returns 


[`Picture`](/cells/python-net/aspose.cells.drawing/picture) object index.


```python

def add(self, top_row, left_column, stream, width_scale, height_scale):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| stream | io.RawIOBase | Stream object which contains the image data. |
| width_scale | int | Scale of image width, a percentage. |
| height_scale | int | Scale of image height, a percentage. |

### Example 


```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs, 50, 50)

```


## add(self, top_row, left_column, file_name, width_scale, height_scale) {#int-int-System.String-int-int}

Adds a picture to the collection.


### Returns 


[`Picture`](/cells/python-net/aspose.cells.drawing/picture) object index.


```python

def add(self, top_row, left_column, file_name, width_scale, height_scale):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| file_name | System.String | Image filename. |
| width_scale | int | Scale of image width, a percentage. |
| height_scale | int | Scale of image height, a percentage. |

### Example 


```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`Picture`](/cells/python-net/aspose.cells.drawing/picture)
* class [`PictureCollection`](/cells/python-net/aspose.cells.drawing/picturecollection)
