---
title: LookInType uppräkning
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 2270
url: /sv/aspose.cells/lookintype/
is_root: false
---
##  LookInType uppräkning
Representerar utseende i typ.



Typen LookInType avslöjar följande medlemmar:

###  Fält
| Fält| Beskrivning|
| :- | :- |
| FORMULAS | Hittar det sökta objektet från formel([`Cell.formula`](/cells/python-net/sv/aspose.cells/cell#formula)) om cellen är formel,<br/>annars hittar från cellens ursprungliga värde (samma som [`LookInType.ORIGINAL_VALUES`](/cells/python-net/sv/aspose.cells/lookintype#ORIGINAL_VALUES)).|
| VALUES | Hittar objekt från cellens ursprungliga värde ([`Cell.value`](/cells/python-net/sv/aspose.cells/cell#value))<br/> och formaterat värde ([`Cell.string_value`](/cells/python-net/sv/aspose.cells/cell#string_value)).|
| VALUES_EXCLUDE_FORMULA_CELL | Ignorerar celler som är formel. För de celler som inte är formel,<br/> Det är samma sak med [`LookInType.VALUES`](/cells/python-net/sv/aspose.cells/lookintype#VALUES).|
| COMMENTS | Hittar endast objekt från cellens kommentar. Ignorerar de celler som inte har någon kommentar.|
| ONLY_FORMULAS | Ignorerar celler som inte är formel. För de celler som är formel,<br/> hittar det sökta objektet från formeln ([`Cell.formula`](/cells/python-net/sv/aspose.cells/cell#formula)).|
| ORIGINAL_VALUES | Hitta objekt endast från cellens ursprungliga värde.|
| FORMATTED_VALUES | Hitta objekt endast från cellens formaterade värde ([`Cell.string_value`](/cells/python-net/sv/aspose.cells/cell#string_value)).|



###  Se även
* modul [`aspose.cells`](..)
