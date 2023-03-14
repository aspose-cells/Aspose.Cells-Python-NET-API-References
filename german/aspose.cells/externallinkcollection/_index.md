---
title: ExternalLinkCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 570
url: /de/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection Klasse
Stellt die Sammlung externer Links in einer Arbeitsmappe dar.



Der Typ ExternalLinkCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [count](/cells/python-net/de/aspose.cells/externallinkcollection/count) | Ruft die Anzahl der tatsächlich in der Auflistung enthaltenen Elemente ab.|



Ruft das [ExternalLink](/cells/python-net/de/aspose.cells/externallink)-Element am angegebenen Index ab.
###  Indexierer
| Name| Beschreibung|
| :- | :- |
| [index] | Der nullbasierte Index des Elements.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add(file_name, sheet_names)](/cells/python-net/de/aspose.cells/externallinkcollection/add/#str-list) | Fügt einen externen Link hinzu.|
| [add(directory_type, file_name, sheet_names)](/cells/python-net/de/aspose.cells/externallinkcollection/add/#DirectoryType-str-list) | Fügen Sie einen externen Link hinzu.|
| [clear()](/cells/python-net/de/aspose.cells/externallinkcollection/clear/#) | Entfernt alle externen Links.|
| [clear(update_references_as_local)](/cells/python-net/de/aspose.cells/externallinkcollection/clear/#bool) | Entfernt alle externen Links.|
| [remove_at(index)](/cells/python-net/de/aspose.cells/externallinkcollection/remove_at/#int) | Entfernt den angegebenen externen Link aus der Arbeitsmappe.|
| [remove_at(index, update_references_as_local)](/cells/python-net/de/aspose.cells/externallinkcollection/remove_at/#int-bool) | Entfernt den angegebenen externen Link aus der Arbeitsmappe.|



###  Beispiel

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Siehe auch
* Modul [aspose.cells](..)
* Klasse [ExternalLink](/cells/python-net/de/aspose.cells/externallink)
