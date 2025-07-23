---
title: ExternalLink Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 570
url: /de/aspose.cells/externallink/
is_root: false
---
##  ExternalLink Klasse
Stellt einen externen Link in einer Arbeitsmappe dar.



Der Typ ExternalLink macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [type](/cells/python-net/de/aspose.cells/externallink/type) | Ruft den Typ des externen Links ab.|
| [path_type](/cells/python-net/de/aspose.cells/externallink/path_type) | Holen Sie sich den Pfadtyp dieses externen Links|
| [original_data_source](/cells/python-net/de/aspose.cells/externallink/original_data_source) | Stellt die gespeicherte Datenquelle des externen Links dar.|
| [data_source](/cells/python-net/de/aspose.cells/externallink/data_source) | Stellt die Datenquelle des externen Links dar.|
| [is_referred](/cells/python-net/de/aspose.cells/externallink/is_referred) | Gibt an, ob auf diesen externen Link von anderen verwiesen wird.|
| [is_visible](/cells/python-net/de/aspose.cells/externallink/is_visible) | Gibt an, ob dieser externe Link in MS Excel sichtbar ist.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add_external_name(self, text, refer_to)`](/cells/python-net/de/aspose.cells/externallink/add_external_name/#str-str) | Fügt einen externen Namen hinzu.|



###  Beispiel

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Get External Link
externalLink = workbook.worksheets.external_links[0]
# Change External Link's Data Source
externalLink.data_source = "d:\\link.xls"

```

###  Siehe auch
* Modul [`aspose.cells`](..)
