---
title: ExternalLinkCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 580
url: /de/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection Klasse
Stellt eine Sammlung externer Links in einer Arbeitsmappe dar.



Der Typ ExternalLinkCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [count](/cells/python-net/de/aspose.cells/externallinkcollection/count) | Ruft die Anzahl der Elemente ab, die tatsächlich in der Sammlung enthalten sind.|



Ruft das Element [`ExternalLink`](/cells/python-net/de/aspose.cells/externallink) am angegebenen Index ab.
###  Indexer
| Name| Beschreibung|
| :- | :- |
| [index] | Der nullbasierte Index des Elements.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/de/aspose.cells/externallinkcollection/add/#str-list) | Fügt einen externen Link hinzu.|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/de/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) | Fügen Sie einen externen Link hinzu.|
| [`clear(self)`](/cells/python-net/de/aspose.cells/externallinkcollection/clear/#) | Entfernt alle externen Links.|
| [`clear(self, update_references_as_local)`](/cells/python-net/de/aspose.cells/externallinkcollection/clear/#bool) | Entfernt alle externen Links.|
| [`remove_at(self, index)`](/cells/python-net/de/aspose.cells/externallinkcollection/remove_at/#int) | Entfernt den angegebenen externen Link aus der Arbeitsmappe.|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/de/aspose.cells/externallinkcollection/remove_at/#int-bool) | Entfernt den angegebenen externen Link aus der Arbeitsmappe.|



###  Beispiel

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`ExternalLink`](/cells/python-net/de/aspose.cells/externallink)
