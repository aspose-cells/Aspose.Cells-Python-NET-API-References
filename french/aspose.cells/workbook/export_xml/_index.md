---
title: méthode export_xml
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells/workbook/export_xml/
is_root: false
---
##  export_xml(self, map_name, path) {#str-str}
Exporter les données XML liées par la carte XML spécifiée.



```python

def export_xml(self, map_name, path):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| map_name | str | nom de la carte XML à exporter|
| path | str | le chemin d'exportation|

###  Exemple

Le code suivant a exporté les données liées par le premier XmlMap.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
# Make sure that the source xlsx file contains a XmlMap.
xmlMap = wb.worksheets.xml_maps[0]
wb.export_xml(xmlMap.name, "output.xml")

```


##  export_xml(self, map_name, stream) {#str-io.RawIOBase}
Exporter des données XML.



```python

def export_xml(self, map_name, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| map_name | str | nom de la carte XML à exporter|
| stream | io.RawIOBase | le flux d'exportation|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
