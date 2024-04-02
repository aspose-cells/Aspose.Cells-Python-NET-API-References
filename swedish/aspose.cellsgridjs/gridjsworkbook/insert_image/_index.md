---
title: insert_image metod
second_title: Aspose.Cells.GridJs for Python via .NET API Referenser
description:
type: docs
weight: 130
url: /sv/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

Infogar bild i kalkylbladet från filströmmen eller URL:en (antingen filströmmen eller URL:en ska tillhandahållas)
 eller
Infogar form, när p.type är en av AutoShapeType


###  Returnerar


JSON-formatsträngen för den infogade bilden


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| uid | str | Det unika ID:t för filcachen|
| p | str | Formatsträngen JSON för operationen som anger cellplatsen, kalkylbladets namn, övre vänstra raden, övre vänstra kolumnen för bilden, etc {name:'sheet1',ri:1,ci:1} |
| s | io.RawIOBase | Filströmmen för bildfilen|
| image_url | str | Bildfilens URL|



###  Se även
* modul [`aspose.cellsgridjs`](../../)
* klass [`GridJsWorkbook`](/cells/python-net/sv/aspose.cellsgridjs/gridjsworkbook)
