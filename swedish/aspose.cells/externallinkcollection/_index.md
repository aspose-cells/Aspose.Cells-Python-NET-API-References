---
title: ExternalLinkCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 600
url: /sv/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection klass
Representerar extern länksamling i en arbetsbok.



Typen ExternalLinkCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [count](/cells/python-net/sv/aspose.cells/externallinkcollection/count) | Hämtar antalet element som faktiskt finns i samlingen.|



Hämtar elementet [`ExternalLink`](/cells/python-net/sv/aspose.cells/externallink) vid det angivna indexet.
###  Indexerare
| namn| Beskrivning|
| :- | :- |
| [index] | Elementets nollbaserade index.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [add](/cells/python-net/sv/aspose.cells/externallinkcollection/add/#str-list) | Lägger till en extern länk.|
| [add](/cells/python-net/sv/aspose.cells/externallinkcollection/add/#aspose.cells.DirectoryType-str-list) | Lägg till en extern länk.|
| [clear](/cells/python-net/sv/aspose.cells/externallinkcollection/clear/#) | Tar bort alla externa länkar.|
| [clear](/cells/python-net/sv/aspose.cells/externallinkcollection/clear/#bool) | Tar bort alla externa länkar.|
| [remove_at](/cells/python-net/sv/aspose.cells/externallinkcollection/remove_at/#int) | Tar bort den angivna externa länken från arbetsboken.|
| [remove_at](/cells/python-net/sv/aspose.cells/externallinkcollection/remove_at/#int-bool) | Tar bort den angivna externa länken från arbetsboken.|



###  Exempel

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`ExternalLink`](/cells/python-net/sv/aspose.cells/externallink)
