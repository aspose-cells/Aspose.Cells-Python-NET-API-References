---
title: QueryTable klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1230
url: /sv/aspose.cells/querytable/
is_root: false
---
##  QueryTable klass
Representerar QueryTable information.



Typen QueryTable avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [connection_id](/cells/python-net/sv/aspose.cells/querytable/connection_id) |Hämtar anslutnings-id för frågetabellen.|
| [external_connection](/cells/python-net/sv/aspose.cells/querytable/external_connection) | Får relaterad extern anslutning.|
| [name](/cells/python-net/sv/aspose.cells/querytable/name) | Får namnet på frågetabellen.|
| [result_range](/cells/python-net/sv/aspose.cells/querytable/result_range) | Får resultatets omfång.|
| [preserve_formatting](/cells/python-net/sv/aspose.cells/querytable/preserve_formatting) | Returnerar eller ställer in PreserveFormatting för objektet.|
| [adjust_column_width](/cells/python-net/sv/aspose.cells/querytable/adjust_column_width) | Returnerar eller ställer in AdjustColumnWidth för objektet.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Getting the first query table in the worksheet
qt = worksheet.query_tables[0]
# Getting display address of the query table.
address = qt.result_range.address

```

###  Se även
* modul [aspose.cells](..)
