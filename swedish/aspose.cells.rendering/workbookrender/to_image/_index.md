---
title: to_image metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells.rendering/workbookrender/to_image/
is_root: false
---
##  to_image {#io.RawIOBase}
Gör hela arbetsboken som Tiff-bild för att streama.



```python
def to_image(self, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | strömmen av utdatabilden|


##  to_image {#str}
Rendera hela arbetsboken som Tiff-bild till en fil.



```python
def to_image(self, filename):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| filename | str | filnamnet på utdatabilden|


##  to_image {#int-str}
Gör en viss sida till en fil.



```python
def to_image(self, page_index, file_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| page_index | int | ange vilken sida som ska konverteras|
| file_name | str | filnamnet på utdatabilden|


##  to_image {#int-io.RawIOBase}
Gör en viss sida till en stream.



```python
def to_image(self, page_index, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| page_index | int | ange vilken sida som ska konverteras|
| stream | io.RawIOBase | strömmen av utdatabilden|



###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`WorkbookRender`](/cells/python-net/sv/aspose.cells.rendering/workbookrender)
