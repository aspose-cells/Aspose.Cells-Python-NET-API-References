---
title: ExternalLink klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 570
url: /sv/aspose.cells/externallink/
is_root: false
---
##  ExternalLink klass
Representerar en extern länk i en arbetsbok.



Typen ExternalLink avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [type](/cells/python-net/sv/aspose.cells/externallink/type) | Hämtar typen av extern länk.|
| [path_type](/cells/python-net/sv/aspose.cells/externallink/path_type) | Hämta sökvägstypen för den här externa länken|
| [original_data_source](/cells/python-net/sv/aspose.cells/externallink/original_data_source) | Representerar den lagrada datakällan för den externa länken.|
| [data_source](/cells/python-net/sv/aspose.cells/externallink/data_source) | Representerar datakällan för den externa länken.|
| [is_referred](/cells/python-net/sv/aspose.cells/externallink/is_referred) | Anger om denna externa länk refereras till av andra.|
| [is_visible](/cells/python-net/sv/aspose.cells/externallink/is_visible) | Anger om denna externa länk är synlig i MS Excel.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add_external_name(self, text, refer_to)`](/cells/python-net/sv/aspose.cells/externallink/add_external_name/#str-str) | Lägger till ett externt namn.|



###  Exempel

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Get External Link
externalLink = workbook.worksheets.external_links[0]
# Change External Link's Data Source
externalLink.data_source = "d:\\link.xls"

```

###  Se även
* modul [`aspose.cells`](..)
