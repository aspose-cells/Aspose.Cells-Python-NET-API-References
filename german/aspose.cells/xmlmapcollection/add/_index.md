---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/xmlmapcollection/add/
is_root: false
---
##  add(self, url) {#str}
Fügen Sie eine [`XmlMap`](/cells/python-net/de/aspose.cells/xmlmap) durch die URL/den Pfad einer XML-/XSD-Datei hinzu.


###  Kehrt zurück

[`XmlMap`](/cells/python-net/de/aspose.cells/xmlmap) Objektindex.


```python

def add(self, url):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| url | str | URL/Pfad einer XML-/XSD-Datei.|

###  Beispiel

Der folgende Code fügt zwei XmlMaps durch eine XSD-Datei und eine XML-Datei hinzu.

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



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`XmlMap`](/cells/python-net/de/aspose.cells/xmlmap)
* Klasse [`XmlMapCollection`](/cells/python-net/de/aspose.cells/xmlmapcollection)
