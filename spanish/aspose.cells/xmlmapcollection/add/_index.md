---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/xmlmapcollection/add/
is_root: false
---
##  add(self, url) {#str}
Agregue un [`XmlMap`](/cells/python-net/es/aspose.cells/xmlmap) por la URL/ruta de un archivo xml/xsd.


###  Devoluciones

Índice de objeto [`XmlMap`](/cells/python-net/es/aspose.cells/xmlmap).


```python

def add(self, url):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| url | str | URL/ruta de un archivo xml/xsd.|

###  Ejemplo

El siguiente código agrega dos XmlMaps mediante un archivo xsd y un archivo xml.

```python
from aspose.cells import Workbook

wb = Workbook()
xmlMapCollection = wb.worksheets.xml_maps
# Add a XmlMap by a xsd file.
xmlMapCollection.add("schema.xsd")
# Add a XmlMap by a xml file.
xmlMapCollection.add("xml.xml")
wb.save("twoXmlMaps.xlsx")

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`XmlMap`](/cells/python-net/es/aspose.cells/xmlmap)
* clase [`XmlMapCollection`](/cells/python-net/es/aspose.cells/xmlmapcollection)
