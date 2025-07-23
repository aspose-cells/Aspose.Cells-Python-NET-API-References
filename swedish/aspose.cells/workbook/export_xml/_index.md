---
title: export_xml metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 150
url: /sv/aspose.cells/workbook/export_xml/
is_root: false
---
##  export_xml(self, map_name, path) {#str-str}
Exportera XML-data länkade med den angivna XML-mappningen.



```python

def export_xml(self, map_name, path):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| map_name | str | namn på XML-kartan som ska exporteras|
| path | str | exportvägen|

###  Exempel

Följande kod exporterade data som länkades av den första XmlMap.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
# Make sure that the source xlsx file contains a XmlMap.
xmlMap = wb.worksheets.xml_maps[0]
wb.export_xml(xmlMap.name, "output.xml")

```


##  export_xml(self, map_name, stream) {#str-io.RawIOBase}
Exportera XML-data.



```python

def export_xml(self, map_name, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| map_name | str | namn på XML-kartan som ska exporteras|
| stream | io.RawIOBase | exportströmmen|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
