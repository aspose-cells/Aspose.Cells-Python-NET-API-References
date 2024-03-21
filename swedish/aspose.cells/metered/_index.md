---
title: Metered klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1090
url: /sv/aspose.cells/metered/
is_root: false
---
##  Metered klass
Ger metoder för att ställa in mätt nyckel.



Typen Metered avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cells/metered/__init__/#) | Initierar en ny instans av den här klassen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_metered_key](/cells/python-net/sv/aspose.cells/metered/set_metered_key/#str-str) | Ställer in mätt offentlig och privat nyckel.<br/> Om du köper mätlicens, när du startar ansökan, bör denna API kallas, normalt räcker detta.<br/> Om dock alltid misslyckas med att ladda upp förbrukningsdata och överskrider 24 timmar, kommer licensen att ställas in på utvärderingsstatus,<br/> för att undvika sådana fall bör du regelbundet kontrollera licensstatusen, om det är utvärderingsstatus, ring detta API igen.|
| [get_consumption_quantity](/cells/python-net/sv/aspose.cells/metered/get_consumption_quantity/#) | Får förbrukningsfilstorlek|
| [get_consumption_credit](/cells/python-net/sv/aspose.cells/metered/get_consumption_credit/#) | Får konsumtionskredit|
| [get_product_name](/cells/python-net/sv/aspose.cells/metered/get_product_name/#) | Får produktnamn|
| [is_metered_licensed](/cells/python-net/sv/aspose.cells/metered/is_metered_licensed/#) | Kontrollera om mätt är licensierat|



###  Exempel

I det här exemplet kommer ett försök att göras att ställa in mätt offentlig och privat nyckel


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Se även
* modul [`aspose.cells`](..)
