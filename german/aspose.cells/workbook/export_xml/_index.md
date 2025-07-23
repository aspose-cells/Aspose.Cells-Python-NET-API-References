---
title: export_xml Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 150
url: /de/aspose.cells/workbook/export_xml/
is_root: false
---
##  export_xml(self, map_name, path) {#str-str}
Exportieren Sie XML-Daten, die durch die angegebene XML-Zuordnung verknüpft sind.



```python

def export_xml(self, map_name, path):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| map_name | str | Name der zu exportierenden XML-Map|
| path | str | der Exportpfad|

###  Beispiel

Der folgende Code exportierte die durch die erste XmlMap verknüpften Daten.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
# Make sure that the source xlsx file contains a XmlMap.
xmlMap = wb.worksheets.xml_maps[0]
wb.export_xml(xmlMap.name, "output.xml")

```


##  export_xml(self, map_name, stream) {#str-io.RawIOBase}
XML-Daten exportieren.



```python

def export_xml(self, map_name, stream):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| map_name | str | Name der zu exportierenden XML-Map|
| stream | io.RawIOBase | der Exportstream|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
